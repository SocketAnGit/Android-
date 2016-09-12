# Android学习计划
个人Android学习路线及学习方法改造。awesome Android by SocketAnGit
<img src="http://upload-images.jianshu.io/upload_images/1676292-e97e87fde0f2b323.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" width="100%" alt="图片来自网络"/>
<h3>一. 缘起</h3>

这篇文章出发点来自于知乎的两个问题：①、[怎样看待 12 个月内自学完成 4 年麻省理工学院计算机科学的 33 门课程的 Scott H. Young 所谓的超速学习理论和方法（费曼技巧）以及背后「Get More from Life」的理念？](https://www.zhihu.com/question/20571226)②、[你有什么相见恨晚的高效学习方法？](https://www.zhihu.com/question/50343728)
学习方法一直是困扰我很久的问题，无论是在学生时代还是后来的就业以及转行。尤其学习Android以及的一些相关的编程范式以后这个问题就更加凸显。程序员是一个需要快速获取新知识并且应用的职业，在工作中快速迭代新的知识并融入知识体系是十分重要的。在网络上收集了有关资料并应用到实际的Android学习中，觉得有必要记录下来于是有这这篇文章。

<h3>二.方法收集摘要</h3>

资料来源自[Scott的youtube](https://www.youtube.com/channel/UCDP05_kNaT6yuBI5ilxKOew)、[Scott的blog](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)、[译文一](http://article.yeeyan.org/view/94114/329073)、[译文二](http://article.yeeyan.org/view/212952/334600)以及所谓的[费曼技巧](https://www.zhihu.com/question/20576786)（未证实）
Scott的自学方法基本分三个阶段：①、概览整个科目，知道要学的大体是什么，课程讲的东西的具体应用。②、实际运用学到的东西，针对课程是做题少量的习题辅助重点是第三阶段。③、使用费曼技巧对学习到的东西查漏补缺、在查漏的过程中主动练习了很多东西，Scott针对不同科目遇到的不同问题灵活运用费曼技巧并总结出属于他的费曼技巧：
- 无法理解的概念：仔细模仿教课书提供的描述，尝试用自己的语言描述出来。如果还是有部分不懂，分成若干个小问题逐个解决最后组合成自己能描述的概念。
- 有解决步骤的问题，一些例题之类的：不光要逐步解释每个步骤，还要理解每步实现的原理最后试着用自己的方法去解决这个问题。这是所谓的how-to、why-to、do-it-yourself
- 各种公式：可以用标准费曼技巧解决，把公式分步理解尝试自己去证明它，自己做出总结。
- 需要记忆的内容：用自己的语言描述一遍，如果能在不借助外来资料的情况下解决了，这段内容基本就记住了，然后就是每隔1天、1周、1个月、三个月的周期去复习了。

<h3>三.对方法的适应改造</h3>

这是我在总结了各方面资料之后，参考Android学习的特点（主要是系统学习后还是有很多新技术需要零碎查找资料学习，光做demo不能满足实际工作需要，Android难点往往在Android之外。）自己对Android学习的总结（草创，会在实践中不断完善）：
<h4>1.</h4>总览Android开发需要知识点（部分）：
这是参照网上资料自己总结的Android知识点思维导图：

![未完成](http://upload-images.jianshu.io/upload_images/1676292-a44507fcb4a50417.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

总的来说
+ Android平台分为七大类：

 - 四大组件
 - UI设计
 - 网络
 - 线程/进程
 - 数据存储
 - 进阶

+ Android之外
 - 算法数据结构
 - 操作系统
 - 编程语言
 - 网络协议
 - 数据库
 - 测试基础
 - 其他
 - 编程范式、编程思想
 - 开源框架

这部分参考了[一张思维导图，告诉你Android新手如何快速入门](http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650662203&idx=1&sn=889fcdfa18ee2d129893bd4c85edad66&scene=1&srcid=0907LxBzHO1cTy2A0Bv6YMDc#rd)主要使用的教材：TODO

<h4>2.</h4>实际运用这些知识点，其实就是github上的开源项目和实际工作。一些常用的第三方开源框架要阅读源码并尝试在自己项目里实现对应的功能。
定一个一个小目标——单个基础实例模块的完成：

TODO
……
<h4>3.</h4>使用费曼技巧查漏，基本是一种递归思想。我初步尝试是把每个知识点用自己语言把原理描述出来，并分成模块尝试实现。尽量把项目里典型代码摘出来，能搜索出来的知识不做重点，尝试自己归纳出实现每个部分的思维原理，抽象部分构成整体这样设计模式和一些编程思想也自己归纳了。
blog
TODO
……
实际上细心的读者应该能看出来了，我这个方法的检测机制实际上就是每个部分实现后写成blog，需要写成项目的尽量上传github，这本身就是一种费曼技巧的应用。
<h3>四.总结及计划</h3>
关于Scott的方法及对他方法的改造到这里告一段落，剩下的就是不断的实践和自我的提高，我十分愿意和他一样主动学习一些感兴趣的东西并使用上自己总结的东西，尝试自己描述所学到的并且在和他人分享中提高这是一种共赢的境况。计划就是按照第三点把每个部分写成blog，并在项目里体会，逐渐形成自己的知识体系。最后用Scott的话和大家共勉
> Nobody likes studying, but everyone wants to be smart. Learning, getting to those insights and feeling smarter about a subject are immensely rewarding. 

<h3>声明:</h3>受所学限制，这篇文章是我的一次尝试、是对学习方法的探索、是对自我的挑战，所以欢迎大家批评指正，在下方留言或私信我。你的建议对我很重要，也是评判机制的一部分，我会吸收大家的建议尽量做好每一步。

<h3>参考：</h3>
+ [怎样看待 12 个月内自学完成 4 年麻省理工学院计算机科学的 33 门课程的 Scott H. Young 所谓的超速学习理论和方法（费曼技巧）以及背后「Get More from Life」的理念？](https://www.zhihu.com/question/20571226)
+ [你有什么相见恨晚的高效学习方法？](https://www.zhihu.com/question/50343728)
+ [Scott的youtube](https://www.youtube.com/channel/UCDP05_kNaT6yuBI5ilxKOew)、[Scott的blog](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)
+ [费曼技巧](https://www.zhihu.com/question/20576786)
+ [十天内掌握线性代数：惊人的超速学习实验](http://article.yeeyan.org/view/94114/329073)
+ [挑战MIT计算机科学课程之幕后花絮](http://article.yeeyan.org/view/212952/334600)
+ [一张思维导图，告诉你Android新手如何快速入门](http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650662203&idx=1&sn=889fcdfa18ee2d129893bd4c85edad66&scene=1&srcid=0907LxBzHO1cTy2A0Bv6YMDc#rd)

<h3>更新:</h3>

+ 2016年9月12日 23:52:55 上传github，建立项目
