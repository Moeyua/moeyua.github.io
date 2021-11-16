---
title: macOS Terminal Command
toc: true
tags:
  - macOS
  - Terminal
date: 2021-11-16 13:31:30
cover: https://i.loli.net/2021/11/16/1uKe4fRLcDQWr6d.png
thumbnail: https://i.loli.net/2021/11/16/1uKe4fRLcDQWr6d.png
categories: 笔记
---
换了 macOS 自然是离不开 Terminal 的，正好乘次机会把在学校没学好的 Linux 命令补回来。
这篇笔记会在我每次新用到一个命令的时候更新，在达到一定数量之后会对文档进行整理归纳。
<!-- more -->
  
# 新建文件
``` zsh
touch filie
```
# 查看端口情况
``` zsh
lsof -i :port
```
结束占用该端口的进程
``` zsh
kill -9 :port
```

