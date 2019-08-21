---
title:        "拉取分支和删除分支"
description:  ""
image:        "http://placehold.it/400x200"
author:       "yangxin"
---

技术博客
============

### 如何拉取本地不存在的分支

1. 在远程库创建分支，新建个文件，提交
2. git  branch -a  查看所有分支
3. 执行git  pull  或者git  fetch
4. 执行git checkout -b  本地分支    origin/远程分支

### 删除分支的几种方法

1.   git  branch  -d   本地分支
2.  git  branch  -dr  删除远程分支  （只能删除本地库和远程库分支之间的追踪关系）
3.  git   push   origin –delete  远程分支     （彻底删除）
4.  git  push   origin       :  远程分支 

