# JavaScript是什么
> 1. 脚本语言
> 2. 交互性
> 3. 通过事件响应等方式来操作对象以实现网页交互
# 重点
> 1. JavaScript基础语法
> 2. 对象（普通对象、浏览器对象、文档对象）
> 3. 事件响应
# 基础语法
1. 如何使用？
	1. 内部脚本
	> script标签
	> 放在任意位置
	> 多个script标签
	2. 外部脚本
	> script标签
	> src连接脚本地址
2. 输出
	> document.write()
	> console.log()
3. 变量声明 var
	> 1. var
	> 2. 弱变量
4. JavaScript中的类型
	1. 数值
	> 1/0 
	> 0.1+0.2
	2. 字符串
	> 定义的时候需要使用引号
	> 创建方式可以分为普通类型和Object
	> 单双引号需要嵌套或者转义
	3. 布尔
	> 只有true和false
	> true==1 false==0
	4. undefind
	5. NaN
	6. null
>typeof 用来判断类型
5. undefined出现的情况
	1. 声明了变量但是没有赋值
	2. 用没有返回值的函数给变量赋值，变量是undefined
	3. 没有给需要参数的函数传参，形参是undefined
	4. 越界读取数组元素
	5. 读取了对象中不存在的属性
6. 数字转字符串
	1. X.toString() --> undefined、null  error
	2. X+""
	3. String(X)
7. 字符串转数字
	1. Number(S)
	2. 减0
	3. parseInt/parseFloat
8. 其他类型转boolean
	1. Boolean()来进行转换
	2. 0 "" undefined null NaN