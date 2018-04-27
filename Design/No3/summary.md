### Introduce

用时1h左右，线上地址codeOpen: https://codepen.io/xiaosais/pen/RyoRVp; 代码地Github: 


### Done

小狗的动画效果有四个位置：

#### 耳朵

通过transform: rotate() 实现

#### 眼睛

通过transform: scale() 缩放眼睛容器的宽度实现，这种方式眼睛的定位还是在中间。

#### 脸颊

通过改变透明度实现opacity()， 同时为了效果更好一点，对脸颊盒子进行了缩放。

#### 下眼睑

通过transform: translate()实现，向上移动一个位置。

#### 嘴巴

改变border-radius实现。


#### CSS 触发transition

主要是通过元素的:hover，然后设定对用元素需要改变的属性， 注意对元素transition属性的添加。

### ToDoList

None