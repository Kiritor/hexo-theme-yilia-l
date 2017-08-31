hexo-theme-yilia-l
================
修改自yilia主题[yilia](https://github.com/litten/hexo-theme-yilia)
笔者非常喜欢yilia主题的简洁、优雅,极致的性能体验。不过其界面的排版不是非常满意,因此久自己改装了下.改了相关样式,新增了一些新鲜的功能:详细界面参考:[我的博客](http://kiritor.github.io/)
>    1. 状态栏(最近的一些状态)
>    2. 微简历(简单的介绍信息,只在首页显示)
>    3. 文章目录(只在文章显示:文章类型为post,不需要目录指定文章类型为post-noTOC)
>    4. 多说最新评论(只在首页显示)

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

## 最近修改
精简了代码,修改了文章目录显示鼠标移动样式混乱的问题,降低了代码耦合度,将配置信息剥离到主题配置文件_config.yml中,在yalia主题上新增的配置项如下:
```bash
#是否开启多说
duoshuo_shortname: kiritor
#是否开启多说最近评论:悬浮于首页
recentComment: true

#是否开启最近通知
recent: true
recentContent: 最近研究shiro中......

#是否开启微简历
resume: true
```
## 首页
![首页](https://github.com/Kiritor/hexo-theme-yilia-l/blob/master/theme-sp1.png)
详细界面参考:[我的博客](http://kiritor.github.io)
