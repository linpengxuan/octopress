---
layout: post
title: "haha 突破性进展"
date: 2012-01-04 21:06
comments: true
categories: 
---
1. 一直纠结于为何我的octopress博客出现在网络地址colors4.us/octopress而不是根目录上
1. 我就差一点点又要回到我学习程序，语言之类的老套路上去，删掉重装，我总能根据教材搞定的吧。就差一点点。
1. 直到我看见了这篇博客[Theming & Customization](http://jphenow.com/docs/theme/template/)，这让我大呼，我没有被抛弃哈哈。
1. 需要做得就是修改`Rakefile`中将`public_dir = "public/octopress"`改为`public_dir = "public/"`以及`_config.yml`中的`root: /octopress`改为`root: /`
1. 这条送给许多像我这样被octo搞死在路上的文科同学。
1. 完了别忘记来个`rake generate`等。
1. 最后在rake deploy时又出错了。说是`No such file or directory - public/octopress/.`不着急，现在知道怎么做了，改Rakefile中的`public_dir = "public/octopress`为`public_dir = "public/`即可。  

