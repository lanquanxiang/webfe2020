# 数组
## 1. 数组的初始化
1. 空白数组 var a = [];
2. 默认值得数组 var a=[1,2,3];
3. 初始化数组的时候长度没有意义。
## 2. 属性和方法
1. 长度length
2. 数组连接
3. 数组头部删除/增加
4. 数组尾部删除/增加
5. 说明
	1. push可以一次增加多个元素，多个元素之间用逗号连接
	2. push可以增加其他类型的元素，如数组、对象
	3. pop不需要参数，即使给了参数也不影响
6. join("字符") 使用给定字符来连接数组的所有元素，如果字符是","== toString()
# 字符串
## 1. 初始化
1. var a="";
2. new String
## 2. 属性和方法
1. length
2. indexOf
3. substring([start,end))
4. substr(start,length)
5. match
6. replace
7. split("字符","返回的数组元素前n个")
# Math
# Date
## 1.初始化
1. new Date()
2. new Date("年-月-日T时-分-秒");
## 2. 常用方法
1. 得到年月日时分秒
2. 得到星期
# 正则表达式
1. 初始化
```var patt = /表达式/修饰符```
2. 修饰符
	1. i 表示忽略大小写
	2. g 全局匹配
3. 元字符
	> 1. \w
	> 2. \d
	> 3. \s
4. 范围
	> 1. [1-9]
	> 2. (1|0)
5. 数量
	> 1. {n}表示n个
	> 2. {n,m} 至少n个，最多m个，m可以省略表示无穷个
6. 位置
	> 1. ^ 开头
	> 2. $ 结尾
7. 方法
	正则表达式.test("待测试字符串")