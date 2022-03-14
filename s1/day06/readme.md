# 选择器【重点】
## 常用选择器（4种）【重点】
1. 类型（标签）选择器 E{}
2. id选择器 #id{}
	> 给标签附加id，然后使用#id来声明样式
	> id是唯一的
	> 在开发中慎用
3. class选择器
	> 给标签附加class属性，然后使用.class声明
	> 不唯一
	> 通常给同一类别的标签附加class
4. 通用选择器 *
	> 选中所有
	> 清除网页默认样式
## 组合选择器（6种）【重点】
1. 组合派生选择器 E.class   eg. div.test2
	> 既要选中E，同时E标签还存在class
2. 后代选择器 E F eg. div .test2
	> 选中F，并且F是E的后代
3. 父子选择器 E>F 
	> 必须是父子关系
4. 相邻兄弟E+F 
	> 选中F
	> F和E是兄弟
	> E和F相邻
5. 通用兄弟选择器 E~F
	> 选中F
	> F和E是兄弟
6. 组合声明选择器 E,F
	> 可以E或者F
## 属性选择器（7种）
1. E[attr]  eg. .con>div>li>a[href]
	> 具备attr这种属性的E
2. E[attr="value"]【重点】
3. E[attr|="value"]
	>eg. input[type="text-password-radio"]
4. E[attr~="value"]
	>eg. input[type="text password radio"]
5. E[attr^="value"]【重点】
	> 这个值以value开头
6. E[attr$="value"]【重点】
	> 这个值以value结尾
7. E[attr*="value"]【重点】
	> 这个值包含value
## 链接伪类选择器（4种）
> 爱恨原则 love hate
1. link
2. visited
3. hover【重点】
4. active
## 伪元素选择器(6种)
1. ::first-letter
2. ::first-line
3. ::before【重点】
4. ::after【重点】
5. ::selection
6. ::placeholder
## 操作伪类选择器(7种)
1. :focus获得焦点【重点】
2. :not
3. :empty
4. :disabled
5. :read-only
6. :checkd
7. :required
## 结构伪类选择器(10种)
1. :first-child
2. :last-child
3. :nth-child(n)【重点】
4. :nth-last-child(n)
5. :only-child
6. :first-of-type
7. :last-of-type
8. :only-of-type
9. :nth-of-type(n)
10. :nth-last-of-type(n)