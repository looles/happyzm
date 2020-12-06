---
title: hexo博客常用命令
description: hexo博客搭建常用使用命令
tags:
  - hexo
  - 博客
  - 前端
categories: hexo
top: true
abbrlink: '51508521'
date: 2020-11-25 10:02:00
---

# happyzm

#### 介绍
博客

#### 软件架构
软件架构说明


#### 安装教程

1.  安装Git
2.  安装Node.js
3.  安装Hexo
4.  GitHub/Gitee创建个人仓库
5.  生成SSH添加到Github或者gitee
6.  将hexo部署到github或者gitee
7.  设置个人域名
8.  发布文章

### 标题

#### 使用说明

1.  安装hexo
npm install -g hexo-cli

2.  初始化
hexo init myblog
//这个myblog 为你的博客文件名

3.  安装依赖
cd myblog    //进入文件夹下安装依赖
npm install

4. 生成静态文章
hexo g

5.  启动本地服务，开启本地调试
hexo server

6.将hexo部署到github或者gitee
打开站点配置文件_config.yml 
 deploy:
  type: git
  repo: https://github.com/YourgithubName/YourgithubName.github.io.git // 仓库地址
  branch: master
这个时候需要先安装deploy-git ，也就是部署的命令,这样你才能用命令部署到GitHub。

npm install hexo-deployer-git --save

7. 清除之前生成的文件
hexo clean

8. 生成静态文章
hexo generate

9.部署文章，更新到github或者gitee上
hexo deploy

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

