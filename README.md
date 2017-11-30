### 自己收集的一些常用Svg-Icon，长期更新。。。

 

#### 如何使用：
将项目克隆下来，将svg目录复制到自己的项目当中，然后将svg目录当中的svg图像插入到网页中；
```bash
git clone git@github.com:jonechen1127/svg-icons.git
```
关于将SVG图像如何插入到网页中，可以参考这篇文章：
[SVG系列教程：SVG简介与嵌入HTML页面的方式](https://www.w3cplus.com/html5/svg-introduction-and-embedded-html-page.html)
 
  
#### 如何修改svg颜色及大小

* 修改颜色，打开svg目录，可以看到有很多的svg icon ，直接打开svg文件，给svg添加属性fill="color" 即可，svg 默认颜色为黑色，如已经有fill属性，直接修改其值即可。
* 修改大小，这个取决于采用哪种方式将svg插入到网页中，推荐使用img标签来插入svg。

#### 为什么不采用字体图标？

原因有两个：

* 项目很小，项目当中用到的icon只有很小一部分，这个时候采用这种直接将svg插入到网页的方式就比较方便，如果项目较大，还是采用引入字体图标这种方式吧！
* 按需定制，需要哪些图标，直接去iconfont上面下载svg格式，然后拖进svg目录即可。

#### SVG图像从哪来里？

* [iconfont](http://www.iconfont.cn/) 
* [icomoon](https://icomoon.io/)

这里推荐上面两个网站，可以直接下载svg格式的图像，如果对下载的svg图像不满意，可以借助svg工具修改一下，譬如AI、Inkscape等软件。这里推荐Inkscape，小巧方便，可以直接导入和导出svg格式。