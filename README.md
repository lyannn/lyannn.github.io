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