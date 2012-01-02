---
layout: post
title: "1st post from mac"
date: 2012-01-02 23:38
comments: true
categories: 
---
cd col*
gem install bundler;bundle install; rake install
git init
git add .
git commit -m 'first commit'
git config --global user.name "linpengxuan"
git config --global user.email linpengxuan@gmail.com
git remote add gitweb git@github.com:linpengxuan/colors4us.git
git push -u gitweb master （先定义gitweb上的colors4.git为gitweb，然后把苹果电脑里的东西master，难道是文件夹中的网站的意思吗？推到gitweb上）
因为此时直接rake deploy的话就变成用rsync了，所以我只能用采用
rake rake setup_github_pages (git@github.com:linpengxuan/colors4us.git)

rake generate;rake deploy: 很奇特地显示了To git@github.com:linpengxuan/colors4us.git
 * [new branch]      gh-pages -> gh-pages 。此时我用这个 git commit -m '2nd commit' 无法执行，我想和我刚才的变动有关系，刚才的变动是坐在gh-pages上的，而非master上，所以commit对master无效。

此时我尝试了touch README；git add .；git commit -m '3rd try'；git push gitweb master；居然可以了，还把刚才在gh－pages上新发的文章也计入了commit了。会不会是git add .的原因呢？

这样做的结果是网站http://linpengxuan.github.com/colors4us/ 没有主题，而且点击了之后无法展开文件，所以不行。

git remote -v
git branch -a

因为git branch -v中显示的是master，所以我的git push origin source无效，我改用git push origin master,就ok了。


