# Franzory.js
* * *
### 选择器
> //选择元素ID
<br>`fran.byId()  例：fran.byId("id") `
<br>参数：元素ID

> //选择某个元素
<br>`fran.dom()  例：fran.dom("#id")`
<br>参数：元素标识

> //选择全部元素
<br>`fran.domAll()  例：fran.domAll(".class")[arr]`
<br>参数：元素标识

> //选择第一个元素
<br>`fran.first()  例：fran.first(fran.dom('#id'))`
<br>参数：父元素

> //选择最后一个元素
<br>`fran.last()  例：fran.last(fran.dom('#id'))`
<br>参数：父元素

> //选择第几个元素
<br>`fran.eq()  例：fran.eq(fran.dom('#id'),1)`
<br>参数：父元素，数字

> //除了某个元素
<br>`fran.not()  例：fran.not(fran.dom('#id'),"not")`
<br>参数：父元素，不选择的子元素

> //上一个元素
<br>`fran.prev()  例：fran.prev(fran.dom('#id'))`
<br>参数：元素

> //下一个元素
<br>`fran.next()  例：fran.next(fran.dom('#id'))`
<br>参数：元素

***

### 操作节点
> //判断是否有该元素
<br>`fran.isElement()  例：fran.isElement(fran.byId("ID")) `
<br>参数：节点

***

### 操作值
> //去除文本前后的空白字符/空格
<br>`fran.trim()  例：fran.trim("  text  ") `
<br>参数：文本

> //去除文本的所有空白字符/空格
<br>`fran.trimAll()  例：fran.trimAll("  t e x t  ") `
<br>参数：文本

***

### 判断是否
> //判断是否有该元素
<br>`fran.isElement()  例：fran.isElement(fran.byId("ID")) `
<br>参数：元素

> //判断是否为数组
<br>`fran.isArray()  例：fran.isArray([1,2,3]) `
<br>参数：数组

> //判断对象是否为空
<br>`fran.isEmptyObject()  例：fran.isEmptyObject({a:1}) `
<br>参数：对象

***

### 事件
> //绑定事件
<br>`fran.addEvt()  例：fran.addEvt(fran.byId("ID"),'click',function,false)) `
<br>参数：（元素，事件名，执行，是否冒泡）

> //解绑事件
<br>`fran.rmEvt()  例：fran.rmEvt(fran.byId("ID"),'click',function,false)) `
<br>参数：（元素，事件名，执行，是否冒泡）

> //一次性事件
<br>`fran.oneEvt()  例：fran.oneEvt(fran.byId("ID"),'click',function,false)) `
<br>参数：（元素，事件名，执行，是否冒泡）
