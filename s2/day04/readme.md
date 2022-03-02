# 表单
## 作用
1. 收集信息
2. 将信息发送给服务器
## 表单的标记和属性
1. form
2. 属性
	1. action 数据提交的地址（具体到处理程序）
	2. method 提交方式 get/post
		1. 收集的信息会显示在地址栏 URL?参数=参数值&参数=参数值; post不显示提交内容
		2. get收集的信息有长度限制 post没有长度限制
		3. get将信息直接推送给服务器，速度更快
		4. get默认提交方式，如果表单中存在文件上传，必须使用post
	3. enctype [encode type]
	> 文件上传的时候必须使用该属性
## input控件
1. text
	1. value 
	2. name
2. submit
	1. value
	2. 作用：提交表单内容
3. radio
	1. 必须设置value（用户点选的控件都需要设置value）
	2. 同一组单选框需要有相同的name
	3. 增加用户提示
4. checkbox 和radio类似
5. submit
6. reset
7. button
8. image
9. file
10. hidden【掌握】
	1. 传递默认值（不需要用户关心和修改）
	2. 和disabled属性联用
## 补充内容
1. disabled属性（禁用控件：控件变成灰色，用户不能编辑，服务器不接收数据）
2. readonly属性(只读：控件颜色不改变，用户不能编辑，服务器要接收数据)
3. disabled来禁用控件，然后使用hidden将控件的值复制一遍   【应用：显示id或者唯一主键】
4. button标记
	1. 按钮上的文字是写在标签文本中的
	2. 当放在form中，相当于submit
## 其他的控件
1. 文本区域标记
	1. 默认值直接写在标签中间
	2. textarea
	3. cols
	4. rows
2. 下拉列表
	1. select
	2. option

# 框架frame
1. 浮动框架
	1. 在页面中导入一个新的页面
	2. iframe
	3. 导入网页用src
	4. 调整大小width、height
2. 拆分框架（框架集）
	1. 不允许存在body 不能和frameset一起使用
	2. 每一个部分都是一个frame
	```
	<frame src="这一部分的网页地址" />
	```
	3. 拆分列 cols="拆分的比例或者像素 25%,75%"
	4. 拆分行 rows="10%,80%,10%"
	5. 可以进行嵌套
3. 在特定frame中打开网页
