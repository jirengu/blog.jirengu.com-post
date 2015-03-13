title: "github协作博客使用说明"
date: 2015-03-10 00:55:55
tags: 使用说明
categories: 
---
## 这是什么
这是一个多人协作博客的博客库，线上博客展示地址为：http://blog.jirengu.com

该博客使用hexo搭建，博客使用文章资源目录为当前的github库。

如果你想把自己写的博客放到http://blog.jirengu.com， 只需要在当前库下建立相应的markdown文件即可。

## 怎么用

1.follow 我，后续会有很多好玩的东西

2.Fork当前的git 库。点右上角`Fork`按钮

3.会发现blog.jirengu.com-post库已经跑到自己的账号下，这时候可以在库里面新建markdown文件。比如你想写一篇博客叫`我的学习`，可以点+号，新建一个`我的学习.md`。里面的内容格式如下：

```
title: "我的学习"
tags: 若愚
categories: 技术
---
## 我的学习内容
插入图片用下面的方式
![](图片地址.png)
```
其中title是文章标题;tags标明文章是谁发的;categories用于归类，表示博客属于哪一类，作为博客的菜单栏，只允许写`技术`和`生活`。`---`这个分割线一定不要丢。分割线下面的才是博客正文。

小建议：写博客的时候要插入一张图片，这个图片会作为博客的封面图片。插入图片的方式是`![](图片地址.png)`，其中图片地址为图片的线上地址。可以随便打开一个github项目，点右侧菜单里的wiki，新建页面，把图片拖进文本输入区，会自动生成图片地址。

4.博客写好提交。

5.点pull Request,之后参考pullRequest的使用:[](https://github.com/jirengu/recommend/blob/master/README.md)

6.我这边账号收到请求后合并代码，自动提交到网站
