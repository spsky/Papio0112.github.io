### 项目来源
闲来无事，突发奇想想要弄个博客谢谢东西，作为一个程序员，感觉没有一个自己的博客都算不上一个完整的程序员。想要有一个博客可以记录自己知识点，备忘录也是不错的。

第一想到的是注册一个现成的博客，市面上的博客系统千千万，但是一个完全由自己控制的系统确是没有的，于是就想到自己开发一个，说实话，开发一个博客并不难，难的是要经常维护，以及服务器的开销。最好是有一个相当于无限流量、无限空间的免费服务器，平时也管过很多博客，发现有很多博客是GitHub的，于是开始查找github建站的攻略。

### 博客开通
经过一夜的查找以及实现，找到此开源项目[huxpro.github.io](https://github.com/Huxpro/huxpro.github.io)

fork到自己的仓库后通过查看文档进行适当的本地化修改，作者提供的文档相当详细，过程很简单。经过简单修改后博客可以说上线了。

### 主题切换
github博客的主题切换也相当简单，网页由github server通过jekyll模板生成静态页面，主题切换只需要fork别的主题到自己仓库，替换_posts文件加下的文章，并修改一下基本配置即可。

### 文章编写
github使用MarkDown语法，文章的编写是创建一个yyyy-MM-dd-title.markdown在_posts文件夹下，并从本地仓库提交至github远程仓库

简单MarkDown语法可查看[]

### 感谢
特别感谢此主题开源作者[Hux](https://github.com/Huxpro)

主题原始作者[BlackrockDigital](https://github.com/BlackrockDigital)