# CSS布局
## 盒子模型
1. 外边距
2. 内边距
3. 上右下左
## 浮动
1. float:left/right
2. 脱离文档流
3. 如果上一元素浮动，则顶部对齐
4. 如果上一元素正常，(块级)则底部对齐（行内元素）顶部对齐
5. 清除浮动 both:clear;
## 定位
1. position
2. absolute 绝对定位
	1. 脱离文档流
	2. 相对于上一个具有特殊定位的父容器进行定位
3. fixed 固定定位
	1. 脱离文档流
	2. 相对于窗体
4. relative 相对定位
	1. 不会脱离文档流
	2. 相对于原始位置
## display显示方式
1. none 消失（文档空间消失）visibility: hidden;(内容消失)
2. block （块元素显示）
3. inline (行内元素)
4. inline-block（行内块元素）能共用一行，也能像块元素一样调整宽度
# CSS变形与动画
## CSS变形 transform
1. 平移
2. 伸缩
3. 旋转
4. 倾斜
## CSS动画 Animation
1. 动画名称
	1. 动画定义 @keyframes
	2. form to
	3. 百分比
2. 动画持续时间
3. 动画运动曲线
4. 动画次数
5. 动画延迟时间