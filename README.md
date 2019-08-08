## 自定义hexo-theme-next主题
- 以修改Mist主题为例，修改网页的css时需要到G:\PortableHexo\hexo\themes\next\source\css\_schemes\Mist目录下，修改各个文件，之前以为是在main.css里修改，结果改了之后没有用。。。。。
- ![](http://ww1.sinaimg.cn/large/d2d96adbly1g56ltx9q7ej20740amaa3.jpg)
  
## 如何在文章顶部添加字数统计和阅读时长
- hexo-theme-next主题已经升级了，之前的一些教程都过时了！！！！！！还有就是搭建博客的过程中总发现教程写的一样的很多，还有一些错误的教程，烦死了，之前用的插件是hexo-wordcount，升级之后改用的是hexo-symbols-count-time插件，具体见https://github.com/theme-next/hexo-theme-next如果装了以前的插件的话，需要先卸载
- 卸载hexo-wordcount插件
- 
   `npm uninstall hexo-wordcount `
- 安装hexo-symbols-count-time插件
- 
  `npm i hexo-symbols-count-time --save`

## 如何给博客添加README.md文件
- 还有一个悲催的事情就是不知道怎么添加README.md文件，之前直接在github上写了之后，deploy之后就被删掉了。。。。。。。悲催的重新写一遍。。。。
- 在这里新增README.md文件
- ![](http://ww1.sinaimg.cn/large/d2d96adbly1g56m62m1krj206e06y749.jpg)
- 在hexo的根目录下里修改_config.yaml文件
- ![](http://ww1.sinaimg.cn/large/d2d96adbly1g56m880cvsj20bg05omx6.jpg)

## 关于添加tags
![](http://ww1.sinaimg.cn/large/d2d96adbly1g57mzdv06mj20na084aad.jpg)
https://blog.eson.org/pub/e2f6e239/



## deploy的位置——一定要在config文件的最末端

如果此段代码不在最末端，在你使用git 命令重置github 信息的时候则会出bug

![](http://ww1.sinaimg.cn/large/d2d96adbly1g5ryq2g2y3j20hh0bb0t0.jpg)

deploy代码不在最下端，且重置github信息之后样子

![](http://ww1.sinaimg.cn/large/d2d96adbly1g5rym5iqvdj20j80bzmxi.jpg)



## 同时开启两个命令行，导致google无法使用

有时我在本地测试之后，会忘记关掉命令窗口，直接开启另外一个命令窗口，好像是这个原因会导致google 一下用不了

![](http://ww1.sinaimg.cn/large/d2d96adbly1g5rz48f7s9j20hs07mt9a.jpg)

如果出了这个问题， 在cmd窗口中输入下面两个命令，然后重启电脑

```
for %i in (%windir%\system32\*.dll) do regsvr32.exe /s %i

for %i in (%windir%\system32\*.ocx) do regsvr32.exe /s %i
```



![](http://ww1.sinaimg.cn/large/d2d96adbly1g5rz7q5jhej20ov09uab3.jpg)