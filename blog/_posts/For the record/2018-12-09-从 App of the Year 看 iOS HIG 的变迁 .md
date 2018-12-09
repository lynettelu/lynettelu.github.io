---
layout: post
title: 从 App of the Year 看 iOS HIG 的变迁 
category: For the record
---

首先，HIG = Human Interface Guideline，用缩写纯粹因为标题太长了，如果不是 AOTY 太难懂我大概也会用缩写...

<br/>

自 2008 年 App Store 上线以后，每年都会有一个官方评选的 App of the Year，顾名思义，苹果觉得当年最具代表性的 app。这里的代表性，可能指是app的功能性或者纯粹只是从设计层面。

![](/images/aoty1.jpg)

今年的 AOTY 是一款叫做 Procreate 的绘图 app。

![](/images/aoty2.jpg)

仔细读一下整篇介绍文章会发现官方选择这款 app 的理由很明显；**充分拥抱 gesture interface 的同时加上自己的创新**，比如两指点触 undo，三指 redo。

<br/>

Procreate 自己也清楚知道被选上 AOTY 的理由，在 [Take our Undo Gesture](https://procreate.art/insight/2018/take-our-undo-gesture) 一文中明确表达了对 two-finger tap to undo 这一设计的自豪之情（most-stolen feature），同时也希望社群能够采纳并推广这个手势。

![](/images/procreate.jpg)

<br/>

回过头来看一下苹果自己的 undo 和 redo；HIG for iOS 里有[专门章节](https://developer.apple.com/design/human-interface-guidelines/ios/user-interaction/undo-and-redo/)来解释，但也没有很确实的执行建议，只是强烈暗示了一下 shake to undo 这个既不直接也不直觉的方式。

![](/images/undo1.png)

自带的 annotation for screenshot 里倒是出现了 undo 和 redo 的例子（右上角）；逆时针箭头表示 undo，顺时针箭头表示 redo，以按钮的形式。

![](/images/undo2.png)

而在 iOS 之前，MacOS 一直是把 undo 和 redo 放在 menu bar 里的：Edit 下的第一和第二项。

<br/>

总体来说，undo 和 redo 在移动端的出场率并不高，或者应该说是被**其他的 metaphor 所替代**了；比如返回/前进，上一步/下一步，甚至是确定/取消。不管是哪种替换，出现形式多数都是直观的按钮。



John Gruber 在最近的博客里提到了 two-finger tap 打破惯例的这件事，并表达了自己的怀疑。



> But it speaks to how weak this convention is that Procreate Pocket could do something **not just different but totally different**— multi-finger taps with no on-screen buttons — and not just get away with it but be celebrated by Apple for it.
>
>
>
> ...Or feeling utterly lost in a different app — like not knowing how to use Undo. If there’s a mistake the original HIG made, it was emphasizing “especially for beginning users”. **Seasoned users benefit too — they’re the ones whose habits and expectations are broken by apps that break conventions**.



他对 two-finger tap 存疑的理由主要有两点：一、不像按钮那样直观，二、打破惯例，用户必须重新学习这个操作。



我个人一直是持 don't reinvent the wheel (for reinventing's sake) 观点的。重点在括号里；重造轮子没关系，但重造的目的是什么？

<br/>

如果从 iOS 12 之后的一系列变化来看，gesture interface 几乎是大势所趋，连 Android 的最新版本也在积极向用手势替换常用操作的方向靠拢，这一点我在[之前的博客](https://zhuanlan.zhihu.com/p/39175151)里有提到：



> **Gesture-based interface 的核心是effortless**；点选的操作需要分配更多的注意力到控件位置，然后实施手指的准确位移；手势操作容错率更高之外，操作量更少，而且对用户来说是一类肌肉记忆。



另外，就如 Gruber 提到的手机端屏幕尺寸的天然限制；on-screen button会占用较多黄金地理位置。而 iOS 也好 Material Design 也好，受 Metro UI 的影响，整体风格也是越来越轻量，常用操作在视觉上简化的同时会渐渐隐形直至消失自然也不奇怪，物理 Home 键在 iPhone 10 上就已经消失了。



可以认为，如果一定要在 Efficiency or Obviousness 里选择一个的话，苹果会选择前者。

<br/>

Fin.