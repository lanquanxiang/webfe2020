# DOM
## 1. 查询
## 2. 增加
1. 创建节点
2. 将节点添加在页面上
> 批量增加
1. 创建文档碎片
2. 将节点追加在碎片中
3. 将碎片追加在文档中
## 3. 删除
```ele.parentNode.removeChild(ele);```
## 4. 修改
1. 修改文本
2. 修改属性
# BOM
## 1. 属性
window.location.href = URL
## 2. 方法
1. open/close
	var win = open(url,"窗口的参数(大小、位置)")
	win.close();
2. 交互框
	1. 警告框 
	2. 确认框 boolean
	3. 询问框 string
3. 计时器
	1. 只执行一次
	```var time = setTimeOut(函数'fun1()'/fun1,毫秒单位的时间);```
	```clearTimeOut(time);```
	2. 周期性执行
	```var time = setInterval(函数'fun1()'/fun1,毫秒单位的时间);```
	```clearInterval(time);```
4. 窗口的历史记录
	1. window.history
	2. 前进 window.history.forward()
	3. 后退 window.history.back()
5. cookie
	document.cookie