# 事件响应
## 1. 三要素
1. 事件源（按钮）
2. 事件（单击）
3. 事件处理程序（f1/f2/f3）
## 2. 如何让事件源和事件绑定在一起？
1. 直接在标签中添加事件`<button onclick="f1()"></button>`
2. 使用JS来进行事件绑定
	1. 获得事件源（元素）
	2. 给元素的某个事件赋值（事件处理程序[函数]）
		`ele.onclick=function(){}`
		```
			ele.onclick = f1;
			var f1 = function(){}
			function f1(){
				
			}
		```
## 事件模型
1. event表示事件
2. event.target表示触发事件的事件源
3. event.type表示事件的名字
# 事件
1. 