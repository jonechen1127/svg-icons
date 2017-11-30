### 自己收集的一些常用Svg-Icon，长期更新。。。

本人收集的一些常用svg-icon，长期更新中

#### 如何使用：
将项目克隆下来，将 svg 目录复制到自己的项目当中，然后将 svg 目录当中的 svg 头像插入到网页中；
```bash
git clone git@github.com:jonechen1127/svg-icons.git
```
关于将SVG图像如何插入到网页中，有以下多种方法可供参考:
 

* 使用<iframe>元素来嵌入SVG图像
* 使用<img>元素来嵌入SVG图像
* 将SVG图像作为背景图像嵌入
* 直接使用<svg>元素
* 使用<embed>元素来嵌入SVG图像
* 使用<object>元素来嵌入SVG图像










#### 如何修改svg颜色及大小

* 修改颜色，打开svg目录，可以看到有很多的svg icon ，直接打开svg文件，给svg添加属性 fill="color" 即可，svg 默认颜色为黑色，如已经有fill属性，直接修改其值即可。
* 修改大小，这个取决于采用哪种方式将svg 插入到网页中，推荐使用 img 标签来插入svg。

#### 为什么不采用字体图标？

原因有两个：
1、项目很小，项目当中用到的icon只有很小一部分，这个时候采用这种直接将svg插入到网页的方式就比较方便；

2、按需定制，需要哪些图标，直接去iconfont上面下载svg格式，然后拖进svg目录即可。
