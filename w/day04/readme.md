# 表单
## 概述
1. 收集信息
2. 发送给服务器
## 标记
1. form
2. 属性
	1. action 具体发送的路径
	2. method 发送的方式（HTTP：get/post）
		> 区别
		> 1. 收集的信息会显示在地址栏(get) post不显示  	-->对于敏感信息不建议使用get
		> 2. 收集的信息有长度限制(get) post没有限制		-->上传文件必须使用post
		> 3. get提交方式比post快		-->默认是get
	3. enctype编码(encode)方式=MIME
		> 文件上传时必须修改此属性
## 收集信息的控件
1. 输入控件input【重点】
	1. 语法
	2. 属性
		1. name：参数的名字（没有此项，数据无法提交）
		2. type：控件类型
			1. 4个框
			2. 4个按钮
			3. 2个域
	3. text/password
		1. value 默认值
		2. size 调整宽度
		3. radio 单选
			1. 用户点选的控件，必须设置value
			2. 用户点选的控件，建议设置用户提示
			3. 提示和值要一致
			4. 对于单选（必须）:用一组单选，必须设置相同的name
			5. checked属性 默认被选中
		4. checkbox 复选
			1. 1-3、5和单选一样
			2. 4建议
		5. button 普通按钮
			1. value 按钮上的文字
			2. 没有任何代码/响应，空白按钮
			3. 补充 ```<button>按钮上的文字</button>```
		6. submit 提交按钮
			1. 将表单数据进行提交（发送信息给服务器）
		7. reset 
			1. 将表单数据清空
		8. image = submit
			1. src="图像地址"
		9. 文件域
		10. hidden【掌握】
			1. 传递默认值
			2. 传递被禁用的值 + disabled
2. textarea
	```
		<textarea>默认值</textarea>
	```
3. select
	1. 选项option
	2. size
	3. selected
## 补充的属性
1. disabled属性
	1. 变成灰色
	2. 用户不允许修改，服务器不能读取（如果这个值需要，就用hidden复制一遍）
2. readonly属性
	1. 不改变样式
	2. 用户不能修改，服务器可以读取