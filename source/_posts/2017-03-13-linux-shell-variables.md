---
title: Shell 变量
date: 2017-03-13 21:41:44
tags:
- Shell
- Linux
categories:
- Technique
- Linux
- Shell
---

学习某种编程语言，首先要掌握的就是该语言的变量的使用，Shell 也不例外。

<!--more-->

---

## 环境变量

\W 表示只显示路径的最后一个目录:
PS1='\[\e]0;\u@\h: \W\a\]${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\W\[\033[00m\]\$ '

调用变量时，不要将变量名与其他字符紧挨着。

## 位置参数

for 循环中 $@ 用 "" 括起来。如果不的话，可能造成直的变化。BUT WHY ???
