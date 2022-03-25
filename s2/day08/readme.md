# CSS布局
## 盒子模型
1. 外边距
2. 内边距
3. 装饰顺序：上右下左
## 浮动
1. float：left/right
2. 脱离文档流
3. 上一个正常的块级元素底部
4. 清除浮动clear: both
## 定位（特殊定位）
1. relative 相对定位
> 相对的是原本的位置
> 1. 只有具有特殊定位的元素才允许移动
> 2. 不会脱离文档流
2. absolute 绝对定位
> 1. 相对于具有特殊定位的父容器
> 2. 脱离文档流
> 子绝父相
3. fixed 固定定位
> 1. 相对窗体
> 2. 脱离文档流
## display显示
1. block
2. inline
3. inline-block
4. none 元素消失，文档流消失
> 隐藏元素
> visibility: hidden; 元素消失，但是文档流存在