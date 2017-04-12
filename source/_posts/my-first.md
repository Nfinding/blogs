---
title: my_first
date: 2017-04-12 21:04:36
tags:
---

###学习目标：
学会使用git，体验正真项目中是如何进行代码共享与版本控制的
知识点：

##一、git
什么是git
Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目（源代码管理工具）
git安装
#1.下载安装包（https://git-scm.com/download/win）
#2.双击安装包，解压到你想安装的目录
#3.配置环境变量（GIT_HOME= git rootHome ，path=%GIT_HOME%\bin;）
git常用命令

#1.git init
在项目根目录执行该命令，会生成一个.git文件夹（隐藏的），用于记录你的项目文件变更
#2.git status
查看 文件状态
#3.git add [filename/./--all] 让git跟踪文件
#4.  ,gitignore(git忽略清单)
#5.配置git用户信息
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
#6.git commit -m “这里写提交原因”把代码提交到本地
#7.git log 显示所有的提交日志（提交原因、提交时间、提交人、每次提交的唯一标识---哈希值）
8.git reset --hard "哈希值前4位" 回退到某个节点
9.git remote add origin 你的仓库地址（如：https://github.com/shaokunpeng/demo1.git）
10.git push -u origin master
##二、分支（branch）
#1.什么是分支
我们可以针对不同的分支，进行编码、撤销
#2.常用命令
git branch 查看分支
git branch "branchName" 创建分支
git checkout "branchName" 切换分支
git clone git地址：从远程下载
git push origin 分支名称  提交到远程分支
git push origin :分支名称 删除远程分支

##三、github
1.github是一个源代码托管网站（git）
2.是免费的（不是完全免费）
##四、gh-pages
一个特殊的分支，用于展示使用（yourName.github.io/projectName）
##五、hexo
hexo安装
1.npm install hexo-cli -g
2.hexo init 博客根目录名称
3. cd 博客根目录
4. hexo server 
##练习
1.在昨天项目基础上，使用git版本控制工具，练习版本控制的基本命令（git init、git status、git add 、git commit等），实现代码的跟踪、提交、回撤等。
2.创建github账号，创建一个项目。
3.代码上传到git服务器，创建多个分支，并针对不同的分支进行代码提交。
4.创建gh-pages分支，尝试通过 用户名.github.io/项目名称访问gh-pages分支里的页面。
5.使用hexo博客框架，在本地搭建一个博客系统，使用博客系统发布一篇文章。
