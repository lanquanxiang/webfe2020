# 表格
## 概述
1. 作用
	1. 排版
	2. 显示列表信息
2. 标记
	1. table
	2. tr
	3. td
	4. caption
	5. border
	6. width
	7. height
3. 其他属性
	1. 边框合并
	2. 合并行
	3. 和并列
	4. 行高
	5. 列宽
## 结构标记
1. thead
2. tbody
3. tfoot

# 表单
## 概述
1. 收集信息
2. 将信息发送给服务器
## 标记和属性
1. 标记form
2. 属性
	1. action 数据发送地址
	2. method
		1. get
		2. post
	3. enctype编码方式【文件上传 必须属性】
## 提交方式的区别
1. get显示在地址栏(url?参数=参数值) post地址栏不显示
2. get提交方式数据有长度限制，post没有限制
3. get主动推送 get速度相对post较快
4. get默认提交方式
## input
1. 语法
```<input name="" type="/>"```
2. type
	1. 4个框
	2. 4个按钮
	3. 2个域
3. 注意事项
	1. size可以用来设置text的宽度
	2. value可以用来设置默认值
	3. 单选框
		1. 必须设置value
		2. 需要在标签后面写上提示
		3. 同一组单选必须有相同的name
	4. 按钮
		1. 普通按钮
		2. 按钮```<button></button>```
		> 在表单中单击之后相当于submit
	5. hidden
		1. 传递默认值（不需要用户关心和修改的）
		2. disabled不可用 + hidden
	6. 其他属性
		1. disabled 禁用输入控件（用户不可改，服务器不可读【hidden】）
		2. readonly（用户不可改，服务器可读） 样式上没有变化
