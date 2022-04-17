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