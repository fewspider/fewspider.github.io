---
layout: post
category : mood
title:  "关于这个主题"
date: 2013-08-03 03:51:16 -0700
tags : [ log, theme, css, jekyll ]
---
今天比较忙的是折腾这个主题的社交网络那部分的倒影效果，看到别人的主题都好美，就不断地把一些比较好看的元素添加进来。顺便说说这个主题的由来。
<!-- more -->

这个主题最早的设计模板是点点网（其实也就是模仿tumblr的国内一网站 其中一个主题，主要是看中她侧边栏的布局设计，就从那边开始制作的。那个主题最大的特点就是左侧边栏是固定的，只有右边的会改变一些东西，比如说文章啦、图片啦（主要是块状分布，由大大小小的矩形构成。

因为要给主题弄个树状的导航，弄到最后，发现左侧边栏那边的树状导航，一展开有些部分就会无法显示，超出了div的高度，于是就加了个滚动条，让她可以显示全部的分类文章。

按着这个思路也将右边的文章内容部分采用跟左侧边栏一样的滚动条，这样就不会将超出div高度的内容覆盖掉了。

本来打算用frame来处理这两个结构，后来发现overflow就可以作出类似的效果。果断选择后者，前者有很多麻烦的地方和缺点。其实我只需要那个滚动条啦，没必要浪费那么多脑细胞去纠结frame。

大概弄好最开始想要的布局和功能，接下来就是优化各部分的细节问题。这边比较琐碎，就不说了。

这个站点的本体是jekyll-bootstrap，还有其他类似的静态网站生成工具，比如Hexo、Octopress啦，看着也差不多，可能效率会比较高点。不过暂时感觉jekyll还可以，Hexo过段时间可能会尝试下（可能这篇文章发表后，就华丽丽地将右下角改成Powered by Hexo了，Node.js还是值得一试的。

最最最开始接触博客的时候，也打算自己写个主题。毕竟别人的避免不了重复嘛，有时就跟碰到撞衫一样尴尬。见过一个童鞋的主题，至少有6、7个人跟他一样。个人觉得blog应该个性化一点。

以前有很多地方不懂，修改主题，把主题改残了也是常有的事。最近接触得比较多，也就知道肿么弄了。

想做和去做，还是有很大不同的。

独立完成一个主题，成就感还是蛮不错的，哈哈哈。


