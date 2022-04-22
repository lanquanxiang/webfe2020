# DOM基础
## 元素的构成
```<标签 属性="属性值">文本</标签>```
## 获得元素的方法
1. `document.getElementById("id")`
2. `document.getElementsByClassName("class")`
3. `document.getElementsByName("name")`
4. `document.getElementsByTagName("tagname")`
5. `document.querySelector("selector")`
6. `document.querySelectorAll("selector")`
## 修改元素内容
1. 文本
```ele.innerHTML或ele.innerText```
2. 值
```ele.value```
3. 属性
```
ele.getAttribute("属性名");
ele.setAttribute("属性名","属性值");
ele.removeAttribute("属性名");
```
## 节点的增加
1. 创建节点
2. 将节点增加到网页中
> 注意
> 1. 如果是批量新增，建议使用文档碎片
> 2. 如果要在ele元素之前追加新元素
```ele.parentNode.inserBefore(newEle,ele);```
## 节点的删除
```ele.parentNode.removeChild(ele);```

# BOM
## 1. 属性
window.location.href
## 2. 方法
1. open/close
	1. var win = window.open(url,窗口的名称,窗口的特征参数[窗口的大小、位置等]);
	2. win.close();
2. 计时器
	1. var t = setTimeOut(fun/"fun()",time[毫秒]);
	2. clearTimeOut(t);
	3. var t = setInterVal(fun/"fun()",time[毫秒]);
	4. clearInterVal(t);
3. 交互框
	1. 警告框 
	2. 确认框 `boolean flag = confirm("问题[是/否]？");`
	3. 询问框 `String ans = confirm("简答题？");`