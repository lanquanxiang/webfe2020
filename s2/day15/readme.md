# jQuery
## 1. 概念
1. 脚本库
2. 方便开发（提高效率）
3. 快速的获得网页对象、具有大量封装的常用方法
## 2. 使用
1. 下载
2. 引入
## 3. 函数工厂$()
1. 封装对象
	1. 将DOM对象封装为jQuery包装集-->$(document)
	2. 将jQuery包装集变为DOM对象 
	--> $(document)[0]或者$(document).get(0) = document
2. 获取对象 $(选择器) 
	1. $("div").get(0)	DOM
	2. $("div").eq(0)   jQuery
	3. E F 后代 E>F E+F E~F E.F E,F
## 4. jQuery的事件
1. 页面就绪事件
2. 修改文本
	jquery.html("新的文本");
	var 文本 = jquery.html();
3. 修改值 val()
4. 修改CSS css()
5. 常用事件
	1. click() 模拟用户操作
	2. click(function(){})绑定事件
6. 表单元素过滤器（文本框元素、密码框元素）
7. 表单状态过滤器（默认选中元素、不可用元素）
8. 元素内容过滤器（空元素）
9. 元素结构过滤器（奇数偶数个元素）