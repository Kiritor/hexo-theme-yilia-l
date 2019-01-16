hexo-theme-yilia-l
================
修改自yilia主题[yilia](https://github.com/litten/hexo-theme-yilia)
笔者非常喜欢yilia主题的简洁、优雅,极致的性能体验。不过其界面的排版不是非常满意,因此久自己改装了下.改了相关样式,新增了一些新鲜的功能:详细界面参考:[我的博客](http://kiritor.github.io/)
>    1. 状态栏(最近的一些状态)
>    2. 微简历(简单的介绍信息,只在首页显示)
>    3. 文章目录(只在文章显示:文章类型为post,不需要目录指定文章类型为post-noTOC)
>    4. 借助valine使用评论系统

## 使用
### 安装
```bash
$ git clone https://github.com/Kiritor/hexo-theme-yilia-l.git themes/yilia-l
```
### 配置
修改修改hexo根目录下的 _config.yml ： theme: yilia-l
### 更新
```bash
cd themes/yilia-l
git pull
```

## 主题配置项
```bash
# Header
menu:
  #主页: /archives
  关于我: /resume
  #主页: /
  前端开发: /categories/front
  工作日志: /categories/work
  点滴生活: /categories/life

subnav:
  github: "https://github.com/Kiritor"
  weibo: "http://weibo.com/3206206100/profile?topnav=1&wvr=6"
  rss: "/atom.xml"
  zhihu: "http://www.zhihu.com/people/kiritor"
  #douban: "#"
  #mail: "#"
  #facebook: "#"
  #google: "#"
  #twitter: "#"
  #linkedin: "#"

rss: /atom.xml

# Content
excerpt_link: More
archive_yearly: true #按年存档
fancybox: true
mathjax: false

# Miscellaneous
google_analytics: ''
favicon: /img/favicon.ico

#你的头像url
avatar: "http://kiritor.github.io/img/lcore.jpg"

#是否开启分享
socialShare: true

#是否开启云标签
tagcloud: true

#是否开启评论
valine: true
#是否开启多说最近评论:悬浮于首页(目前弃用多说)
#recentComment: false

#是否开启捐赠
donate: true

#是否开启站内搜索
search: true

#是否开启目录
toc: true

#是否开启最近通知
recent: true
recentContent: 最近打算回归学习,记录一点东西,慢慢找回写博客的习惯...

#是否开启微简历
resume: false

#是否开启友情链接
#不开启——
friends: false
#开启——
#friends:
  #奥巴马的博客: http://localhost:4000/
  #卡卡的美丽传说: http://localhost:4000/
   #本泽马的博客: http://localhost:4000/
  #吉格斯的博客: http://localhost:4000/
  #习大大大不同: http://localhost:4000/
  #托蒂的博客: http://localhost:4000/

#是否开启“关于我”。
#不开启——
#aboutme: false
#开启——
aboutme: 乐于分享,喜欢环境音乐,爱看动漫,偶尔写写技术博客的小程一枚...
```
常用的配置不在讲解，一些特别的配置如下:
### TOC
通过如下配置开启文章目录,需要注意的是所有文章都会开启
```bash
toc: true
```
Tips: 如果某个文章不需要目录,可以指定文章layout: post-noTOC实现
```bash
layout: post-noTOC
title: 第一次面试官经历
date: 2017-03-01 22:07:40
```
### 社会化分享
通过如下配置开启社会化分享,需要注意的是所有文章都会开启
```bash
socialShare: true
```
### valine评论
基于相关原因，弃用多说，采用valine构建评论系统，关于valine可自行查阅。通过如下配置开启评论(全局文章)
```bash
#是否开启评论
valine: true
```
Tips: 如果某些文章不想开启评论效果，可在新建文章时,指定comment: false,操作如下:
```bash
layout: post-noTOC
comment: false
title: 第一次面试官经历
date: 2017-03-01 22:07:40
category: work
tags: 面试
top: true
---
......
```
### 捐赠
通过如下配置，可开启捐赠(全局)
```bash
#是否开启捐赠
donate: true
```
Tips: 如果某些文章不想开启捐赠,可在新建文章是，指定donate: false,操作如下:
```bash
layout: post-noTOC
donate: false
title: 第一次面试官经历
date: 2017-03-01 22:07:40
category: work
tags: 面试
top: true
---
```
## 首页
![首页](https://github.com/Kiritor/hexo-theme-yilia-l/blob/master/theme-sp1.png)
详细界面参考:[我的博客](http://kiritor.github.io)
