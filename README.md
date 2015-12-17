# SVerticalTextView
智能可以支持垂直排列的Android TextView。
原理是重写View，计算文字大小之后，一个个重排的。类似于活字印刷术的印版。。。

### 优点：

比网上现存的所有假垂直排版要更灵活，

支持自动换行，

横竖排列切换，

自动缩放，

字体切换，

文字阴影等。

### 缺点：

由于继承的View，所以很多TextView特性没有，比如Html标签之类的。
 ![image](https://github.com/h3clikejava/SVerticalTextView/blob/master/pic.png)
