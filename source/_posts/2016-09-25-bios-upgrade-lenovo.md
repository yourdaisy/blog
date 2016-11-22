---
title: 笔记本升级 BIOS
date: 2016-09-12 22:00:57
tags:
- BIOS
categories:
- Technique
- BIOS
---
本文记录了我给自己的联想笔记本升级 BIOS 过程，仅供参考。

<!--more-->

---

我在浏览 Lenovo 美国官网的时候，发现同型号的联想电脑该网站提供的驱动更新比联想大陆官网要新，顿时感觉联想不厚道啊，新东西居然不给祖国人民使用。于是我认真比对了联想大陆和美国两个网站的驱动版本，发现 BIOS 是可以更新的。由于我的操作系统是 Windows 10，其他驱动就不考虑了，毕竟可以自动更新。早就在网上了解到，电脑升级 BIOS 是有风险的，于是我谷歌和百度查看下该型号电脑有没有人升级成功过，搜索结果让我有了升级的信心和勇气，现在什么年代了，安装个软件还能让电脑变石头？

首先下载相应版本的 BIOS 升级软件，由于没有 Windows 10 版本，可以选择 Windows 8.1 版本。共下载2个可执行文件：5fcn95ww_public_64bit.exe 和 5fcn95ww_private_64bit.exe。
然后开始安装:
1. 安装 5fcn95ww_public_64bit.exe。
2. 在安装期间不要关闭电脑。
3. 电脑会自动重启以使升级生效。
4. 安装 5fcn95ww_private_64bit.exe。
5. 同样，在安装期间不要关闭电脑，电脑会自动重启以使升级生效。

**注：如果在第4步中出现版本老的提示而无法继续，请到 BIOS 设置界面将 BIOS Back Flash 设置为 Enabled，然后继续从第4步操作**

使用了很长一段时间，并没有出现什么问题。总之，听别人说一万句，不如自己动一次手。