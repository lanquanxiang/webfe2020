# 数组
## 1. 初始化
1. 没有初始值 var a = [];
2. 有初始值 var a=[值1,值2];
## 2. 属性和方法
1. 长度 length
2. 数组连接 a = a.concat(b)
3. 删除数组开头的元素 shift
4. 删除数组尾部的元素 pop
5. 向数组的头部增加元素 unshift
6. 向数组的尾部增加元素 push
7. 将数组转换为字符串 join("连接符") 如果连接符是","== toString()
# String
## 1. 初始化
1. var s= "";
2. var s = new String("");
## 2. 属性和方法
1. 长度
2. 位置 charAt  indexOf
3. 截取 substring(start,end) substr(start,length)
4. 匹配 match search replace
5. 将字符串转换为数组 split("分隔符")
# Math
# Date
# RegExp
1. 初始化 var reg=/表达式/修饰符
2. 修饰符
	1. /表达式/g 全局匹配
	2. /表达式/i 忽略大小写
3. 位置修饰符
	1. ^开头
	2. $结尾
3. 元字符（*）
	1. \d表示任意数字
	2. \w表示任意数字、字母、下划线
	3. \s表示空白符
	4. 说明：特殊字符需要进行转义 \. \[ \]
4. 量词修饰符
	1. {n} 表示出现n次
	2. {n,m} 表示最少出现n次，最多出现m次，如果可以出现无穷次{n,}
	3. ?={0,1}
	4. +={1,}
	5. *={0,}
5. 检测是否匹配方法
	reg.test(str)使用正则表达式reg来检测str是否符合要求
6. 范围
	1. [0-9]  [a-z] [A-Z] [A-z]
	2. (x|y)