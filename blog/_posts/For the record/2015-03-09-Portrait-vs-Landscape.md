---
layout: post
title: Portrait vs Landscape
category: For the record
---

![set](/images/portraitinlandscape.jpg)


###Page Orientation

Page Orientation即页面方向，指的是矩形平面以长边为底还是以短边为底，分为Portrait（纵向）和Landscape（横向）两类。

从英文可知这两者最早的定义皆出自绘画，Portrait指的是人物画像，Landscape指的则是风景画。扩展到其他领域后，Portrait主要应用于报纸书籍及移动设备，而Landscape主要应用于视频播放，如电视、影院等。



###人眼对Portrait和Landscape的感知

Portrait和Landscape的划分反应了一个视觉的事实，即人类从左至右视物比自上而下更多，眼球转动范围内的横向双眼视物为114度，而纵向的则在60度左右。所以人类的视域（Field of View）范围可见下图，本身就接近Landscape。

![set](/images/fieldofview.png)

因Landscape能容纳更多信息，电视和电影都是横向的，其中影院剧幕的发展越来越趋向于超宽屏。这里要提一句，早期的生产技术限制让电视较接近正方，是因为更容易制造。

到了读字，情况又有所不同。人类的视线更擅长纵向追踪物体，横向线性跟踪读取一个个文字效率不高且容易错位，使得文字排版会固定行宽；最终报纸和书籍等大部分以文字为主体的印刷品多为Portrait，即使出现了Landscape的排版，那也是两栏式的。

总结起来就是，Portrait适合读字，Landscape则适合读图。



###电脑显示器是怎么回事

第一台(?)图形化界面个人电脑Xerox Alto象征了GUI时代的开始（Thank God UI设计师有饭吃了），它的显示屏其实是Portrait的。

![set](/images/xeroxalto.JPG)

为什么Alto用的Portrait已不可考，个人猜测是因为个人电脑的原始需求来自辅助办公，写写文章、填填表格什么的。

Portrait一度风光无两，70年后期到80年早期的IBM PC多为Portrait，但随着大批量生产的趋势，Landscape逐渐走向舞台中央倒也无可厚非，当时已广为普及的电视机作为电脑显示屏的替代品已有相当规模且价格实惠，而电视几乎都是Landscape的。早期显示屏长宽比多数是4:3的理由也出于此，没错，因为主流电视机比例是4:3。

>...the portrait display faded away while common landscape-display televisions were appropriated for use as an inexpensive early microcomputer display.



###手持设备很纠结

技术发展到今天，从台式电脑到笔记本再到智能手机，普通用户能明显感知到的差异在于尺寸。手持设备顾名思义「一手可持」，人类手掌的生理特性让历史的荣光再次回到了Portrait。

![set](/images/multidevice.jpg)

一份对互联网行业的调查结果表明多数人认为近两年业界的重点在于跨多种设备的连贯（consistency）上。

如上图所示，笔记本对台式的绝大多数特性继承良好，但移动设备如智能手机和平板则不同。除了基于不同操作系统、基于原生或者浏览器等特征外，最直观的是显示内容的多寡，而且一个Landscape的页面并不是顺时针转个九十度就能变成Portrait的。

响应式设计（responsive design）这一解决方案应运而生，一定程度上解决了不同屏宽下的展示问题，但一来最小元素的物理属性是天生的，二来宽度解决了还有高度。文字为主的新闻类网站积极投入响应式的怀抱的同时，图片、视频为主的网站陷入两难，权衡之后更多还是选择开发原生app，干脆基于Portrait小屏幕重新设计界面。一时间Mobile first成了当年的buzzword。

![set](/images/Multi-devices.jpg)

关于最小元素的限制如上图所示，一张16:10的图片在台式和笔记本上均可全屏显示，而在Portrait比例的移动设备上同比压缩后，留出了上下两截浪费掉的空间，这是响应式设计解决不了的。

不知是否受笔记本的影响（而笔记本显示器又可能是受高清电视的影响），2010年起持续热销的Samsung Galaxy S系列使用的都是笔记本主流宽屏比的16:9，而发售于2012年的iPhone 5，一改前代1G到4s的4:3，同样转向了16:9。

当大家都用一样的比率后，翻转设备也许能得到不错的结果。

![set](/images/Multi-devices2.jpg)



###小结

Portrait和Landscape本身就是从特定场景中自然而然出现的解决方案：画风景的时候画布竖着天空和大地占的空间太大不好看，那就横过来；画人的时候画布横着那下半身就没了，那就竖着。当无法改变显示内容的时候，那就改变显示设备本身的属性，这种打破问题框架的思路倒也挺有趣。但当显示内容本身多样且多变时，又要怎么办？


###Next Part：Aspect Ratio Evolution



Fin.
