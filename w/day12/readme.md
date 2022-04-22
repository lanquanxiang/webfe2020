# DOM
## 1. 节点的获取
1. document.getElementById("id")
2. document.getElementsByClassName("class")
3. document.getElementsByName("name")
4. document.getElementsByTagName("tagname")
5. document.querySelector("selector")
6. document.querySelectorAll("selector")
## 2. 节点的修改
```<div 属性>文本</div>```
1. 修改文本
	ele.innerHTML或ele.innerText = newText
2. 修改属性
	1. ele.setAttribute()
	2. ele.getAttribute()
	3. ele.removeAttribute()
## 3. 节点的增加
1. 创建节点createElement
2. 将这个节点增加在页面上appendChild
> 补充的知识
> 1. 批量新增
> 2. 兄弟节点的追加（了解）
向ref这个节点的前面追加节点newEle
> `ref.parentNode.inserBefore(newEle,ref);`
## 4. 节点的删除
`ele.parentNode.removeChild(ele);`
> 了解
> 1. 节点的克隆
> 2. 节点的替换

# BOM
## 1. window的常用属性
1. document
2. location.href表示当前网址（读/写）
改变URL能够实现网页跳转
`window.location.href=新的网址;`
## 2. 计时器
1. var t = setTimeOut(fun,time);
> t 表示计时器本身，可以用来清除计时器
> fun 表示的是回调函数（执行的程序） 可以写表达式"fun()"
> eval("fun()")== fun
2. 清除TimeOut
`clearTimeOut(t);`
3. var t = setInterVal(fun,time);
4. clearInterVal(t); 清除计时器
> 补充知识：JS执行机制
## 3. 打开和关闭窗口
1. var win = open("url","name","特征值[窗口的大小或位置]");
2. win.close();
> JS只能关闭自身打开的窗口，不能关闭用户打开的
## 4. 交互框
1. alert("警告的话");
2. boolean confirm("是还是否?");
3. string prompt("简答题?","默认答案");
> 补充知识（了解）
> 1. 控制浏览器前进和后退
> 2. （实用）保存表单数据