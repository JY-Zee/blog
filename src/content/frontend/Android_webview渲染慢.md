---
title: 'Android webview 渲染慢'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 08 2022'
heroImage: '/blog-placeholder-3.jpg'
---

<!-- # Android webview 渲染慢 -->

android webview 渲染长文字的html时候，上下滑动快的情况下，会出现滑动尾部的文字渲染不出来，渲染慢的情况

有可能是因为webview没有开启gpu加速，使用gpu渲染，页面会流畅，并且帧数会提高。

如果没有使用gpu加速，就默认是cpu渲染，有些机型cpu性能差，则会出现帧数底，渲染慢的问题

![image.png](image.png)

参考：
[](https://blog.csdn.net/ForeverCjl/article/details/120283859)