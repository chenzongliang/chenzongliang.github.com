---
layout: post
title: 如何提交博客文章
category: 博客
tags: Blog
description: 如何提交github博客文章
---

## 编写文章
首先在Windows下使用MarkdownPad工具编辑文章，MarkdownPad下载地址：[点击链接下载](http://markdownpad.com/)

## 使用Git工具提交文件
添加当前所有修改文件
    
    git add .

提交当前文件到本地仓库

    git commit -a -m 'add files'

提交本地仓库代码到远端git服务器

    git push origin master

## 图片无法显示问题
首先将图片上传到github仓库：

    https://github.com/chenzongliang/chenzongliang.github.com/blob/master/images/head.jpg

如果需要在markdown中能显示，需要将路径中的blob修改成raw：

    https://github.com/chenzongliang/chenzongliang.github.com/raw/master/images/head.jpg

具体显示效果如下：

![个人头像](https://github.com/chenzongliang/chenzongliang.github.com/raw/master/images/head.jpg)

怎么样，效果还不错吧！
