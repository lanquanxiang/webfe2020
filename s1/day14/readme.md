# Ajax
1. Ajax的开发
2. text数据的解析
3. xml的编写与数据解析
4. json的编写的数据解析
## Ajax的开发
1. 初始化核心(XMLHttpRequest)对象
```var xhr = new XMLHttpRequest();```
2. 创建请求
```xhr.open("get/post",url,true|false);```
3. 发送请求
```xhr.send();```
4. 解析数据并修改网页内容
``
xhr.onreadstatechange = function(){
	if(xhr.readystate==4&&xhr.status==200){
		var data = xhr.responseText;|xhr.responseXML;
		/*使用JS来展示数据*/
	}
	
}
```
```
	var data = xhr.responseText;|xhr.responseXML;
	/*使用JS来展示数据*/
```
## XML请求
1. 编写规则
	1. 所有的标记必须成对出现
	2. 必须要有根标记
	3. 标签可以自定义，但是不要使用特殊字符，建议不要使用关键字
	4. 属性必须要加引号

## JSON请求
1. 编写规则