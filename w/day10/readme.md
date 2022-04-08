# number
1. 以0开头的是八进制，以0x是十六进制
2. 使用e来进行科学计数法表示
3. 浮点数是不精确0.1+0.2
4. NaN 
	> 操作数两端存在NaN
	> 不定式 0/0
	> 存在复数的情况
5. 无穷大 infinity
# string
1. 赋值的时候可以用单引号也可以用双引号
2. 如果字符串中本身就有单双引号，需要注意正确嵌套
3. 如果存在特殊字符，建议使用转移字符
# boolean
1. true false
2. 0 1
```
var a = new String("123"); 
var b = new Boolean(true);
var a = String("123"); =="123"
```
# 相互转换
## 数字转字符串
1. toString() // undefined、null不可用
2. +""
3. String()
## 字符串转数字
1. parseInt/parseFloat
2. -0
3. Number()
## 其他类型转boolean
1. 只有5个false:0 、""、undefined、Null、NaN
# 函数
## 函数的定义
1. 函数声明
2. 函数表达式
3. 构造方法
## 函数的调用
1. 在script中通过**函数名()**来调用
2. 事件响应
3. 超链接调用href=URL
# object
## 创建
1. new
2. ={}
# undefined
1. 定义了变量但是没有赋值，变量的值是undefined
2. 使用了无返回值的函数为变量赋值，变量的值是undefined
3. 没有给需要参数的函数传递参数，形参是undefined
4. 访问了数组不存在的元素，得到undefined
5. 访问了对象不存在的属性，得到undefined