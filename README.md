# Franzory.js
* * *
### 选择器
> //选择元素ID                          `fran.byId()  例：fran.byId("id") `  参数：元素ID

***

### 操作节点
> //判断是否有该元素                     `fran.isElement()  例：fran.isElement(fran.byId("ID")) `  参数：节点

***

### 操作值
> //去除文本前后的空白字符/空格           `fran.trim()  例：fran.trim("  text  ") `  参数：文本

> //去除文本的所有空白字符/空格           `fran.trimAll()  例：fran.trimAll("  t e x t  ") `  参数：文本

***

### 判断是否
> //判断是否有该元素                      `fran.isElement()  例：fran.isElement(fran.byId("ID")) `  参数：元素

> //判断是否为数组                        `fran.isArray()  例：fran.isArray([1,2,3]) `  参数：数组

> //判断对象是否为空                      `fran.isEmptyObject()  例：fran.isEmptyObject({a:1}) `  参数：对象

***

### 事件
> //绑定事件      `fran.addEvt()  例：fran.addEvt(fran.byId("ID"),'click',function,false)) `  参数：（元素，事件名，执行，是否冒泡）

> //解绑事件      `fran.rmEvt()  例：fran.rmEvt(fran.byId("ID"),'click',function,false)) `  参数：（元素，事件名，执行，是否冒泡）

> //一次性事件    `fran.oneEvt()  例：fran.oneEvt(fran.byId("ID"),'click',function,false)) `  参数：（元素，事件名，执行，是否冒泡）
