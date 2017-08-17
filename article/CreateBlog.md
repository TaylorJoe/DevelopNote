# 快速创建一个属于自己的博客

在清明三天假期中利用休息时间模仿 [GcsSloop](http://www.gcssloop.com/) 的博客创建了一个属于自己的博客，希望自己以后可以在这个 Blog 上记录一些开发中的问题。
这个 Blog 是用 Coding 和 Jekyll 搭建的，整体来说还是比较容易的。[Coding](https://coding.net/) 是一个类似 [GitHub](https://github.com/) 的代码托管。
之所以利用 Coding 是因为它的访问速度在国内比 GitHub 要快许多。

首先在 [Coding](https://coding.net/) 上创建一个属于自己的账号，在创建的账号下新建一个项目。

![](http://ww1.sinaimg.cn/large/ee14e49dly1fec88omlpkj219q0wmae4.jpg)

按照上图创建好了项目

使用 git 把项目 clone 到本地。这里我使用的 Jekyll 的主题是使用 GcsSloop的[Gcs-Vno-Jekyll](https://github.com/GcsSloop/Gcs-Vno-Jekyll) ，
Gcs-Vno-Jekyll 是 GcsSloop 基于 onevcat 大神的 [OneV-s-Den](https://github.com/onevcat/OneV-s-Den) 修改而来的.

我们把 [Gcs-Vno-Jekyll](https://github.com/GcsSloop/Gcs-Vno-Jekyll) clone 到之前项目的目录下，把所有文件添加到版本库推送到 Coding.net。
在项目的「Pages 服务」设置中，选择部署来源为 master 分支，点击「保存」按钮。 稍等片刻即可完成部署并通过 {user_name}.coding.me/{project_name} 访问您的网站.

这里我用的 WebStorm 打开之前的项目，项目的结构如下图

![](http://ww1.sinaimg.cn/large/ee14e49dly1fec9ptk55pj20ju0nu40i.jpg)

然后修改 _config.yml 文件中的内容就可以改变主页中的信息,如下图：

![](http://ww1.sinaimg.cn/large/ee14e49dly1fec9ynmmaoj21ee0todn0.jpg)

修改其中的内容就可以改变首页中的信息

修改头像和背景图需要修改 assets/siteinfo 下的 avatar 和 background-cover 即可。

修改网址图标则需要修改 _includes/head.html 中的：

![](http://ww1.sinaimg.cn/large/ee14e49dly1feca5t21yyj21c0036gnb.jpg)

修改上图中的两个 href 。这里我利用的新浪图床生成的图片地址。

最后需要添加文章是在 _posts 下创建 年-月-日-描述.md格式的文章，内容可以如下图：

![](http://ww1.sinaimg.cn/large/ee14e49dly1fecadc0589j21k00zsdqh.jpg)

修改其中的内容即可，修改完之后push到master分支。一般过上几分钟去自己的 blog {user_name}.coding.me/{project_name} 访问即可看到效果。

希望大家都能创建一个属于自己的博客，分享更多的技术文章，与大家共同进步！！！

******
