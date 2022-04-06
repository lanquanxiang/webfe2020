# 数值类型
1. 0x和0开头的特殊进制
2. 科学计数法e
3. js中数据不是精确的
4. 0.1+0.2！=0.3
## NaN
1. 操作数两边存在非数字
2. 不定式
3. NaN==NaN  false
## Infinity
> 1/0
# string 字符串
1. 单双引号声明
2. 单双引号可以嵌套（一层）
3. 多层使用转义字符
# boolean
1. false或true
2. 参与运算时true==1，false==0
3. ```0 '' null undefined NaN```是false
# 类型转换
1. Number()/Boolean()
2. parseInt/parseFloat()解析
## 数字转字符串
1. toString() //undefined、null不可以调用此方法
2. +""
3. String()
## 字符串转数字
1. parseInt/parseFloat()
2. -0
3. Number()
## 转boolean
1. Boolean()
2. 只有五种是false
# function
## 定义
1. function
2. 形参前面不加var
3. 如果函数有返回值return
## 其他定义方式
1. 函数声明
2. 函数表达式（变量）
## 函数的调用
1. body中调用
2. 事件响应
3. 超链接
## 函数的形参与返回值
1. 形参的个数可以和实参不一致
2. 如果形参不能接收到值，undefined
3. 如果使用没有返回值的函数给变量赋值，值改变为undefined
# object对象
1. ```var obj = {}```
2. ```obj.属性```
# undefined
1. 声明了变量，但是没有赋值，变量的值是undefined
2. 使用了没有返回值的函数给变量赋值，变量值改变为undefined
3. 没有给需要参数的形参赋值，形参是undefined
4. 读取了越界的数组元素，元素的值是undefined
5. 读取了对象不存在的属性，值是undefined