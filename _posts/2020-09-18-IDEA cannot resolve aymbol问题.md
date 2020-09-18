---
layout:     post
title:      IDEA错误的报cannot resolve symbol问题
subtitle:   
date:       2020-09-18
author:     Bowen
header-img: img/post-bg-ios9-web.jpg
catalog:    true
tags:
    - IDEA
---
最近遇到了好几次IDEA的"Cannot resolve symbol ***"问题，类和类中的方法明明都存在的，方法签名也没有问题，maven编译也没有问题，可以确定代码是没有问题的，但IDEA就是一直报错，说无法解析符号，尝试了重启ide和电脑后依然无法解决，重装IDEA也没有，最后通过清空了IDEA的缓存在解决，方式如下：

File -> Invalidate Cashes/Restart

<img src = 'https://ftp.bmp.ovh/imgs/2020/09/f0b659961646138c.png' width="200" height="350"/>

<img src = 'https://ftp.bmp.ovh/imgs/2020/09/4afd2f85d35f5cde.png' />