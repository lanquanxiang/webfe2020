# CSS选择器
## 常用选择器(4种)[掌握]
1. `*` 通配符
	> 选中所有元素
	> 应用：消除默认样式 或者 添加全局样式
2. E 标签选择器
	> 选中E这种标签
3. id选择器
	> 声明  #id{}
	> id是唯一的
	> 需要给标签附加id属性
4. class选择器
	> 声明 .class{}
	> class表示一类，不唯一
	> 需要给标签添加class属性
## 组合选择器(6种)[掌握]
1. 后代选择器 E F   eg. div .red
	> 选中F
	> F 必须是E的后代
	> 后代: body
2. 父子选择器 E>F 
	> 选中F
	> F必须是E的儿子
3. 相邻兄弟选择器 E+F
	> 选中F
	> F必须是E的兄弟
	> F和E必须是相邻的 (老大和老二)
	> 选中的F是在E的后面
4. 通用兄弟选择器 E~F
	> 选中F
	> F必须是E的兄弟
	> 选中的F是在E的后面
5. 派生选择器（并且选择器） EF
	> 既要匹配E也要匹配F eg. div.red
6. 或者选择器E,F
	> 选中E或者F  eg. div,.red
## 属性选择器(7种)
1. E[attr] [掌握]
	> 选中E
	> 具备attr这种属性
2. E[attr=value][掌握]
	> 选中E
	> 具备attr这种属性，且属性值是value
3. E[attr|=value]
	> 选中E
	> 具备attr这种属性，且属性值存在value列表中
	> value列表：value1-value2-value3
4. E[attr~=value]
	> 选中E
	> 具备attr这种属性，且属性值存在value列表中
	> value列表（空格隔开）：value1 value2 value3
5. E[attr^=value][掌握]
	> 选中E
	> 具备attr这种属性，且属性值以value开头
	> eg. a[href^="https"]
6. E[attr$=value][掌握]
	> 选中E
	> 具备attr这种属性，且属性值以value结尾
	> eg. img[src$="png"]
7. E[attr*=value][掌握]
	> 选中E
	> 具备attr这种属性，且属性值包含value
## 链接伪类(4种)
> 爱恨原则 love hate
1. :link
2. :visted
3. :hover[掌握]
4. :active
## 伪元素选择器(6种)
1. ::first-line
2. ::first-letter
3. ::after[掌握]
4. ::before[掌握]
5. ::selection （被选中的文本）
6. ::placeholder （提示文本）
## 状态伪类选择器(7种)
1. :focus 获得焦点[掌握]
2. :not(selector) 否定
3. :is(selector) 
4. :checked
5. :disabled
6. :read-only
7. :empty 元素没有任何内容
## 结构伪类选择器(10种)
1.  E:first-child
2.  E:last-child
3.  E:only-child
4.  E:nth-child(n)[掌握]
	> 可以是具体的值
	> 表达式 2n
5.  E:nth-last-child(n)
6.  E:first-of-type
7.  E:last-of-type
8. E:only-of-type
9. E:nth-of-type(n)
10. E:nth-last-of-type(n)