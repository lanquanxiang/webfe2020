# Ajax
1. 异步的JavaScript和XML（保存数据）
2. 无刷新更新页面内容
3. JavaScript向服务器发起（同步/异步）--> 服务器响应数据（text/xml/JSON）-->DOM解析数据并更新网页
# 知识
1. 如何发起请求（同步/异步）
	1. 同步：如果数据对后续渲染影响非常大
	2. 异步：影响不大，或者数据量很大
2. 如何获得text数据并显示在页面上
3. 如何编写xml并解析xml数据然后显示
4. 如何编写json并解析json数据然后显示
## 实现Ajax
1. 初始化核心对象
` var xhr  =  new XMLHttpRequest();`
2. 创建请求
` xhr.open("get|post",url,true|false);`
3. 发送请求
` xhr.send();`
4. 接收响应数据并解析然后显示在网页上
```
var textdata = xhr.responseText;
var xmldata = xhr.responseXML;
var jsondata = JSON.parse(xhr.responseText);
```
## text的同步异步请求
## XML的编写与解析
1. xml的编写规则
	1. 自定义任意标记，建议不要使用特殊字符
	2. 必须具有唯一的根标记（树形结构）
	3. 严格遵守标记成对，属性值必须要有引号
2. xml属性存储和文本存储
## JSON的编写与解析
1. json的编写规则
	1. {}表示对象
	2. []表示数组
	3. {名字:值,名字:值}
2. 优点
	1. 存在结构
	2. 比xml更容易解析（对象）  访问属性： obj.属性名  或  obj["属性名"]