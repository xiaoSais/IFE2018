
### Introduce 

约1h完成，作业线上地址 https://codepen.io/xiaosais/pen/erdZWj

### Done

好久之前学过CSS3，但有些属性不用真的很容易忘，今天学习的内容主要是transform属性，现在正好趁着这个机会复习一下，CSS3的大部分新增的属性为了兼容低版本的浏览器都要加前缀。

```
    -webkit-transform: (兼容webkit内核浏览器 chrome | safari)
    -moz-transform: (兼容Firefox内核浏览器)
    -o-transform: (兼容opera浏览器)
    -ms-transform: (兼容IE浏览器)
    transform: (CSS3标准)
```



#### transform属性
transform属性是CSS3新增一个属性，主要用于元素的2D或者3D变换，兼容性最低支持到IE9（需要增加-ms前缀）。

##### rotate(20deg)

正数表示该元素按照中心顺时针旋转一个角度，负数表示该元素逆时针旋转一个角度。

#### skew(x, y) | skewX(x) | skewY(y)

rotate将元素旋转一个角度，旋转中心默认是元素的中心，但是也可以调整变化中心。

skew是改变元素的形状，将该元素向x | y 轴一个方向进行扭曲。我的理解是旋转对称轴，元素不跟着旋转。x 数值为正代表垂直方向上的对称轴逆时针旋转， y 数值为正代表水平方向上的对称轴顺时针旋转一个角度， 为负时旋转方向相反。

#### scale(x, y) | scaleX(x) | scaleY(y) 

将一个元素x方向和y方向进行缩放，值为1的时候代表不改变大小，否则按照设定的值进行x | y轴的缩放。如果scale()只有一个值代表<b>同时对水平方向和竖直方向进行相应比例的缩放。</b>这一点和skew不同。

#### translate(x, y) | translateX(x) | translateY(y)

将一个元素向x | y 方向平移一段距离。其中x,y可以是任何css单位。x正方向为向右， y正方向为向下。

#### transform-origin()

在没设置transform-origin属性的时候，所有的图像变换方式都是基于元素中心的，通过这个属性，可以改变元素的变换中心。原则上有九个可以选择的位置，它的值分别是right(右中) | left(左中) | top(上中) | right top(右上) | left top(左上) | center(中心，默认) | bottom(下中) | bottom left(左下) | right bottom(右下)

### ToDolist

None