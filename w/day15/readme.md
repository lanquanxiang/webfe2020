# jQuery
## 1. 概述
1. 脚本库
2. 减轻工作量、提高效率
3. ```<script src=""></script>```
## 2. jQuery的使用
1. 工厂函数和筛选器
	· $("selector") 例如 $("#id")   $("div")
	· $(DOM对象)  将DOM对象转换为jQuery对象
	· jQuery对象[0] 将jQuery对象转换为DOM对象
2. 索引器
	· jquerys.eq(0) jQuery对象
	· jquerys.get(0) 或 jquerys[0]  DOM对象
3. 说明
	· 如果包装集中只有一个元素，可以不使用筛选器
	· 如果有多个元素，不适用是筛选器，则对每一个元素都进行相同操作
## 3. 重要方法
1. 页面加载事件
	· onload = function(){} 和 ready(function(){})
2. 修改元素文本
	· 获取文本的内容
	dom.innerHTML    jqery.html()
	dom.innerText	 jquery.text()	
	· 修改文本的内容
	dom.innerHTML="新的文本"    jqery.html("新的文本")
3. 获取和修改值
	dom.value   			jquery.val()
	dom.value = "新的值"		jquery.val("新的值")
4. 事件触发
	dom.onchange = function(){}
	jquery.change(function(){})
5. 补充内容
	1. 修改属性
	2. 修改css
	3. jquery筛选器
		· 表单选择器
		· 属性选择器
		· 内容选择器
		· 结构选择器
	4. 常用事件（链式语法）
6. 事件绑定
	1. <button onclick="fun()"></button>
	2. document.querySelector("button").onclick = fun;
	3. document.querySelector("button").addEventListener("click",fun,true);
	4. $("button").click(fun);
	5. $("button").bind("click",fun);