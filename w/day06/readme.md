# CSS选择器
## 常用选择器（4）【重点】
1. `*` 通配符选择器
	> 选中网页中所有元素
	> 清除浏览器默认样式
	> 为网页设置统一样式
2. E 标签选择器
	> 选中某个标签的所有元素
	> eg. div
3. id选择器 
	> id是唯一的
	> 需要给标签附加id属性 id="test1"
	> 样式声明 #test1{}
	> 不要用纯数字
4. class选择器
	> 需要给标签附加class属性 class="test2"
	> 样式声明 .test2{}
	> 不要用纯数字
## 组合选择器（6）【重点】
1. E F 后代选择器
	> 选中F
	> F是E的后代（F被包含在E中）
	> eg. div span a li
2. E>F 父子选择器
	> 选中F
	> F是E的儿子
	> eg. ul>li>ol>li
3. E+F 相邻兄弟选择器
	> 选中F
	> F是E的相邻兄弟
	> F在E的后面
4. E~F 通用兄弟选择器
	> 选中F
	> F是E的兄弟
	> F在E的后面
5. EF并且选择器(派生选择器)
	> 既要满足E也要满足F
	> eg. divp(×) div.test2
6. E,F 或者选择器（组合声明）
	> E或者F
	> 对E和F进行同时声明
## 属性选择器（7）
1. E[attr]【重点】
	> 选中E
	> 存在attr这种属性
2. E[attr="value"]【重点】
	> 选中E
	> 存在attr这种属性
	> 属性值必须是value
3. E[attr|="values"]
	> 选中E
	> 存在attr这种属性
	> 属性值必须是values的值列表中
	> 列表是用-隔开的  eg. div-span-p
4. E[attr~="values"]
	> 选中E
	> 存在attr这种属性
	> 属性值必须是values的值列表中
	> 列表是用空格隔开的  eg. "div span p"
5. E[attr^="value"]【重点】
	> 选中E
	> 存在attr这种属性
	> 属性值必须是以value开头
	> eg. a[href^="https"] "选出所有安全超链接，并且给这种超链接添加绿色的背景"
6. E[attr$="value"]【重点】
	> 选中E
	> 存在attr这种属性
	> 属性值必须是以value结尾
	> eg. a[href$="doc"]
7. E[attr*="value"]【重点】
	> 选中E
	> 存在attr这种属性
	> 属性值包含value
## 链接伪类选择器（4）
> 爱恨原则 love hate
1. :link 超链接点击之前
2. :visited 超链接点击之后
3. :hover 鼠标悬停【重点】
4. :active 点击的一瞬间
> 上述顺序不能随便变动
## 伪元素选择器（6）
1. ::first-line
2. ::first-letter
3. ::after【重点】
4. ::before【重点】
> content:"文本内容"
> content:url()
5. ::selection
6. ::placeholder
## 状态伪类选择器（7）
1. :focus 获得焦点【重点】
2. :is(selector)
3. :not(selector)
4. :only-read
5. :disabled
6. :checked
7. :empty 空标签【重点】
## 结构伪类选择器（10）
1.  E:first-child
2.  E:last-child
3.  E:only-child
4.  E:nth-child(n)【重点】
	> 1. 可以是固定值
	> 2. 表达式 2n
5.  E:nth-last-child(n)
6.  E:first-of-type
7.  E:last-of-type
8. E:only-of-type
9. E:nth-of-type(n)【重点】
10. E:nth-last-of-type(n)