#
# frame
1. iframe 浮动框架
	1. src
	2. width
	3. height
2. frameset
	1. frameset 不能和body一起使用
	2. frame 
	3. cols
	4. rows
3. 应用
	1. 框架页面（删除body，frameset代替）
	2. 进行页面分割
	```
	<frameset rows="10%,90%">
		<frame src="top.html" />
		<frameset cols="20%,50%,30%">
			<frame src="top.html" />
			<frame src="top.html" />
			<frame src="top.html" />
		</frameset>
	</frameset>
	```
	3. 设计单独的每一个页面
	4. 为frame命名，然后超链接中target在指定frame中打开