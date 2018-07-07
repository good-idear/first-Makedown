# 暑期封训第一周总结
这个星期看了许多的网页模板，也试着写设计师给的模板，感觉自己还是非常垃圾的。有许多的CSS3的页面效果都不能实现。也看了CSS3的伪元素::after和::before,有些时候使用这些伪元素，十分方便，可以少敲代码，而且还达到同样的效果。
这里就有一个利用[::after](https://cssanimation.rocks/cn/pseudo-elements/)的例子，学习之后还发现有个background里面还有一个渐变的api[linear-gradient](http://www.runoob.com/cssref/func-linear-gradient.html)属性。又顿时觉得CSS3真是强大。
其中还有一些导航栏的CSS３动画十分不错，[动态导航](http://web.book.51xueweb.cn/anli/13/13-18.html#),感觉第二个效果不错，就写了第二个，还是蛮不错的。
还有一个就是将图片文字进行像素化，组成新的图案。（还没做过成品）
实现思路就是：基于canvas的3D粒子旋转算法+依赖getImageData来获取文字或者图片的像素信息。具体看岑安大牛的博客->[3D粒子效果](http://www.cnblogs.com/hongru/archive/2012/03/28/2420415.html).我就不写了。
