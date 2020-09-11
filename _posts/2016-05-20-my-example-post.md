---
layout: page
title:  "Sample"
subtitle: "A longer explanation of stuff"
date:   2016-05-20 21:21:21 +0530
categories: ["general"]
---

# 搭建个人技术博客

 使用Github Paper+Jekyll 快速部署个人博客

- Github Paper
    - 定义：给所有用户的一个个人主页
    - 如何访问：域名:用户名.github.io
    - 如何编写主页：搭建一个用个人域名为项目名的远程版本仓库，只需要向该远程仓库中的master分支提交代码即可（该代码中必须有一个文件，叫index.html文件）
- jekyll
    - 定义：可以将master语法自动编译成html语法的一个工具
    - 安装：不需要我们自己安装，在GitHub网站中预安装的，
    - 使用：不用人为使用，当你请求个人域名的时候GitHub会读取仓库（以个人域名命名的那个远程版本仓库）中的master分支中的代码，如果该代码为markdown语法为自动调用Jekyll将其编译为html代码并返回客户端

- 建立一个个人域名为项目的远程管理仓库
- 访问一个网址：主题网址：http://jekyllthemes.org/选择一个主题，将其代码复制至我们仓库中的master分支
- 以上两步可以合并为一步，在主题仓库中点击fork，点击setting设置仓库名，即可
- 将远程版本库中的代码克隆到本地
    - 点击头像，点code，复制链接git clone -b master https://github.com/zuimiluren/zuimiluren.github.io.git myblog
    - 从远程版本库中克隆下来的代码会自动创建本地版本仓库
- 修改配置文件以及页面内容
- 书写博客