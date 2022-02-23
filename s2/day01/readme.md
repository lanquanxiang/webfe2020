# 概述
## 工具
1. HBuilder
2. Chrome
3. gitee/github
4. markdown
## 架构模式
1. B/S 浏览器/服务器
> 教务系统
> 京东网页版
2. C/S 客户端/浏览器
> QQ
> 王者荣耀
3. 优缺点
	1. 开发和维护成本 B/S相对更低
	2. 客户端负载 C/S能够承担一定的运算和负载
	3. C/S相对更安全 （专人使用）
## 网页呈现过程
1. URL[掌握]解析
2. 域名解析DNS
3. 建立连接TCP三次握手
4. 提供服务 响应页面
5. 浏览器来渲染页面[面试]
## URL格式
1. 格式
	```
		协议://主机地址:端口号/目录名/文件名?参数=参数值&参数=参数值#书签
	```
2. 协议
	1. HTTP 超文本传输协议 protocol
	2. HTTPs 安全的HTTP
	3. FTP 文件传输协议
3. 端口号
	1. 80 HTTP
	2. 8080 Tomcat
	3. 3306 MySQL
4. 默认首页index.XXX
5. 不要使用中文或者特殊字符来作为项目名或者文件名
## URI
1. URI 统一资源标识(id)
2. URN 统一资源命名(name)
## 服务器状态码
1. 404 not found
2. 500 error
## 浏览器
1. safari
2. opera
## 开发技术
1. HTML
2. CSS
3. JavaScript
## MIME 多用途互联网邮件扩展类型[掌握]
1. 文本	text
2. 图像	image
3. 音频	audio
4. 视频	video
5. 信息	message
6. 应用	application
7. 多部分媒体 mutilpart
## 媒体的表示
1. 顶级（一级）媒体类型/二级类型
2. 例如
	> image/jpeg

# HTML概述
## HTML
1. 超文本标记语言
2. 特点
	1. 不编译，解释执行
	2. 不区分大小写
	3. 不识别不可见字符，解析为一个空白符
3. 版本
	1. HTML5
	> 声明 
	`<!doctype html> `
	2. HTML4.01
4. 标签/标记
	1. 单标记
	2. 双标记
