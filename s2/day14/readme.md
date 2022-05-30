# Ajax
1. 异步的JavaScript和XML
2. 无刷新更新页面
应用：验证码
## 优缺点
# 内容
1. Ajax的开发（与服务器进行通信，并且取回数据更新页面）
2. 异步和同步两种请求方式
3. text文本数据获取（字符串【没有结构】）
4. xml数据的获取与解析
5. JSON数据的获取与解析【主流】
## Ajax的开发
1. 初始化核心对象XMLHTTPRequest
` var xhr = new XMLHttpRequest(); `
2. 创建请求（同步和异步）
` xhr.open("get|post",URL,true|false);`
3. 发送请求
` xhr.send();`
4. 接受服务器数据（text、xml、json）并更新网页（DOM）
## 接收数据
1. text数据
	`var data = xhr.responseText;`
1. XML数据
	`var data = xhr.responseXML;`
## 异步请求
1. 同步和异步的使用
	1. 同步：数据量小或者对后续内容影响较大
	2. 异步：数据量大或者对后续内容影响不大
2. 异步请求
	1. 设置核心对象状态改变时触发函数
	2. 只有当请求完成&&服务器正常才处理
## xml数据
1. 如何编写xml
	1. 标记可以完全自定义，建议不要使用特殊字符
	2. 所有的标记必须成对出现
	3. 必须要具有唯一的根标记
	4. 属性必须要加引号
2. xml的书写
	1. 将数据存储在文本中
	2. 将数据存储在属性中
## JSON数据
1. 如何编写JSON（JavaScript Object Note）
	1. []数组
	2. {}对象
	3. "name":"value","name":"value"