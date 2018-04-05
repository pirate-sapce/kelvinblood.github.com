---
layout: post
title: Linux开发模式带给创业者的启示
category: tech
tags: rss philosophy startup
---

本文来自《MacTalk 人生元编程》的作者，池建强。原文戳[这里](http://macshuo.com/?p=1279)。其实不好意思，第一次池建强讲的人生的道理就和编程一样（大概是这个意思）的时候，心里其实是有一些共鸣的，刚上大学的时候也有过类似的感觉，本来嘛，作为程序员习惯性地将事情代入编程也是常有的事。

这篇文章也有些共鸣和收获，于是转载下来，时时常拂拭，瞄上几眼，喵(●ↀωↀ●)✧


十五年前，我第一次在工作中使用 Linux 的时候，并不知道这个操作系统会对我的生活和职业产生多么大的影响。十五年后，我在「Linus，一生只为寻找欢笑」一文中写到：

当大家使用 Google 搜索时，使用 Kindle 阅读时，使用淘宝购物时，使用 QQ 聊天时，很多人并不知道，支撑这些软件和服务的，是后台成千上万台 Linux 服务器，它们时时刻刻都在进行着忙碌的运算和数据处理，确保数据信息在人、软件和硬件之间安全的流淌。

Linux 不仅仅从技术层面影响人们的生活，其本身就产生了很多有意思的话题和文化，我读了不少 Unix/Linux 相关的书籍，很多技术内容已经忘得一干二尽，但那些话题、模式和文化，却像醇香的好酒、美丽的传说，历久弥新，不断的为我带来思考和启发……

## 1、最初的想法，并不是决定性的

Linux 并不是凭空创造出来的，当年林纳斯（Linus）只是觉得迷你版 Unix 操作系统 Minix 的终端太难用了，既不能登录学校里的 Unix Server，也没法上网。这种功能缺陷对林纳斯这样的极客来说是无法接受的，于是他决定从硬件层面开始，重新为 Minix 设计一个终端仿真器。

当时是三月，也可能是四月，就算彼得盖坦街上的白雪已经化成了雪泥我也不知道，当然我也并不关心。大部分时间我都穿着睡衣趴在相貌平平的计算机前面噼噼啪啪的敲打键盘，窗户上的窗帘遮得严严实实，把阳光和外部世界与我隔离开来。 经过不眠不休的编程之后，终端仿真器做出来了，但那个时候林纳斯已经意识到自己的雄心壮志远不止于此，神山上的另一座圣杯「操作系统」已经向他发出了召唤，于是始有 Linux。

另一个伟大的操作系统 Macintosh，同样起步于一个微小的项目，期间历经换帅、更名、争吵、妥协，最终与 NextStep 经过长达四年的整合才形成现代的经典操作系统 OS X（参见《MacTalk·人生元编程》）。

几乎所有成功的产品都是边走边看做出来的。伟大的梦想，常常始于微不足道。

所以，很多人问我如何找到一份长期稳定的工作时，如何开启一个能够带来巨大成功的项目时，我只能说，最初的想法，并不是一切，开始去做就好了。


## 2、好的软件产品，常常源于开发者自身的需求

林纳斯为给自己开发终端仿真器最终做出了让其名垂青史的 Linux 操作系统，沃兹因为热爱计算机设计出了 Apple I，乔布斯想把1000首歌装进口袋推出了 iPod。

如果有什么工作能让你保持长久的热情，那一定是做自己需要的产品。当年我们在给程序员开发工具平台的时候，我要求每个工具研发人员都使用我们自己开发出来的工具，而不是仅仅把工具推给测试人员和项目组的程序员。过了一段时间，我发现那个 IDE 突然增加了很多「善解人意」并「出人意料」的功能。

如果有一天放下现在的工作，我一定会找一件足以让我穷尽半生去探索和追求的事情，用「术」解决问题，用「道」创造解决问题的方法，顺便改变生活。

## 3、优秀的程序员知道如何编程，卓越的程序员知道合理复用

林纳斯并没有尝试从零开始编写 Linux，而是以重用 Minix 的代码和理念作为开始，虽然在 Linux 最终的版本中几乎所有 Minix 代码都被移除或重写了，但它在 Linux 成长初期确实起到了类似脚手架的作用。

卓越的程序员通常都很懒，我们把这种懒叫做「建设性懒惰」，因为他们知道，很多时候我们要的都是最终的结果，而不是勤奋的过程。如果有可以复用的基础，显然比从零开始更具有建设性。

在开源社区澎湃发展的今天，我们有了更多的技术选择。所以，当你拿到一个轮子的需求时，去社区里找找问问，如果有可以复用的东西，就不要再费劲去造一个新轮子，况且你无法保证自己造的轮子比旧轮子好用。

我从来不是卓越的程序员，我只是模仿他们。

## 4、如果你有正确的态度，有趣的事情自然会找到你

林纳斯从写下第一行 Linux 代码的开始，就保持了一个开放的态度，可以说，Linux 一诞生就被打上了开源的烙印，这一点对其后续的发展起到了至关重要的作用。因为开放和开源，Linux 吸引了全球的开源爱好者和顶级黑客，无数卓越的程序员为 Linux 贡献了源代码，同时，林纳斯在开源协作方面也展现出了编程之外的天赋，他井井有条的运作着庞大的开源社区，回复邮件，发起讨论，阅读代码，合并分支，Linux 操作系统在开源社区的推动和林纳斯的调教下以惊人的速度发展。

从来没有一款如此复杂的软件系统是以这种松散的方式构建的。几千名散落在世界各地的开发者，凭借着脆弱的互联网建立关系，他们利用业余时间，构建出了一个鬼斧神工般的操作系统，随即这个系统又成为互联网的基石，其间沧海桑田，让人叹为观止。

一切都源于开放的态度。我对这一点深有体会，从写下第一条 MacTalk 推送开始，我只想向世界传递我的讯息，结果各种有趣的人和事纷至沓来。但行好事，莫问前程。

为什么要登山？因为山在远方。为什么要阅读？因为历史在书里。为什么要写作？因为思想流淌在心头和指尖。就是如此。

## 5、如果你对一件事情不感兴趣了，最好的做法是找到一个有能力的接棒者

每个人的兴趣都会转移，林纳斯也不例外。在 Linux 进入稳定发展的阶段，他把更多的精力放到了开源社区上，但是这并没有降低 Linux 操作系统的代码质量，因为他找到了更多的顶级源代码贡献者。

在软件开发的项目中我们同样会遇到类似的问题。某个功能的开发者突然对该功能失去了兴趣，这时候我们就有责任为这个功能找到一个可以胜任的接棒者，而不是强迫原来的开发者在原地踏步。

很多时候，我们厌倦了一件事情，并不是能力缺失，而是因为已经洞悉了这件事的所有秘密，于是转身离去，开辟新的征程……

## 6、把早期用户当做你的合作者或开发者，这是提高代码质量和产品质量的有效途径。

林纳斯把 Linux 的源代码放到网上之后，很快就收获了一批既是开发者又是合作者的用户，他选取了其中五人组成了核心开发小组，除了 Linux 内核建设的最终决定权属于林纳斯之外，一切都是开放的，这五个人承担了绝大多数关键的开发和组织工作，在各自的领域组织自己的用户和开发者，推进 Linux 有条不紊的向前发展。

这些合作者和开发者就像筑巢的蜂群一样，围绕着 Linux 辛勤的工作，看起来杂乱无章，实际上细致严密，因为任何人的工作都在阳光下进行，没一个错误的产生和修复是隐藏在暗影中的。一个人的代码出了漏洞，立刻有另一个人冲上去打补丁，打完之后，两人交换眼神，握手，然后转身投入下一轮的开发和测试中。

通常一个几十人的项目组就能把整个公司搞的鸡犬不宁，这种事我们见的太多了，但是林纳斯却依赖自己的早期用户构建了历史上最大的合作项目，成千上万的开发者依赖邮件列表和相互之间制定的规则进行交流和研发，同时开展的项目经常超过4000个。

如果你找到了产品的早期合作者用户，那么你的项目已经成功了50%。 「即便是高层次的设计，如果能有很多合作开发者在你产品的设计空间周围探索，也是很有价值的。设想下一滩雨水是怎么找到下水口的，或者说蚂蚁是怎么发现食物的。探索在本质上是分散行动，并通过一种可扩展的通信机制来协调整体行为。一个外围的游走者可能会在你旁边发现宝藏，而你可能有点过于专注而没能发现」。

现在很多创业项目在早期发布的时候常常采用邀请制，这其实是获取早期合作者用户的最佳时期，合理的选择用户并通过邮件列表、群组和线下交流活动等方式不断获取反馈，并让用户参与其中，会大大提高你的产品质量和代码质量。我参与过的早期项目中，有道云笔记·协作版算是做的不错的，可惜的是，产品版本正式发布之后，这种参与和反馈感渐渐消失了。

更多的创业产品只是把邀请用户当做普通用户看待，意义寥寥。正确的做法应该是把所有潜在的合作者用户加入你的邮件列表或特定群组，每次发布新版本时，向邮件列表发送朋友对话般的通知（而不是例行邮件），鼓励他们参与，听取他们的意见，征求他们关于设计决策的看法，当他们发来补丁和反馈时给他们以热情回应。

你会有回报的。

## 7、最好的领导就是「不要试图去领导」

林纳斯是一个懒惰的程序员，所以他很早就认识到，好的领导者，并不是大包大揽，也不是让下属去完成领导部署的任务，而是让他们做自己真正想做的工作。好的领导者不应该总是去试图领导别人，他们要及时反思，修正自己的思路和决策，听取别人的意见，并把一些决策权交给他人。

作为整个 Linux 项目的领军人物，林纳斯只是在操作系统内核的争端上进行仲裁和决策，其他时候，大部分是集思广益，多头并进。林纳斯说：

我有时会赞同他们的工作，有时会批评他们的工作，但是大多数时候我都是放任自流的。如果两个人同时维护了相同的功能，我会接受两份工作成果，评估哪一份更可行。如果两者竞争激烈，那么我会同时拒绝他们，直到其中一位开发者失去了兴趣。

如果你是一位创业公司的领军人物，要常常反思的不是「我是不是做的太少了」，而是「我是不是管的太多了」。

## 8、及早发布，快速发布，并倾听用户的声音

很多人都习惯性的认为，除非是很小的项目，早发布和频繁发布的做法有益无害。因为早期产品大都问题多多，过早发布会耗尽用户的耐心和开发者的雄心。这种看法直到互联网时代才开始有所改变。各大互联网公司为了抢占先机，开始无快不破，虽然第一代产品存在很多问题，但是他们会通过迅猛的迭代速度，快速推出第二代和第三代产品去弥补缺陷、赢得用户和占领市场。

其实这种策略 Linux 系统在上个世纪90年代就开始采用了，林纳斯在早期（1991年）发布内核的频率甚至超过了一天一次！他把用户当做了自己的合作者，他不断倾听用户的声音，以持续发布来回报用户，用自我满足感激励那些黑客和顶尖高手。有些人会提出问题，有的人会发现问题，有的人会解决问题，这一切都会淹没在 Linux 频繁发布的版本浪潮里……

当然，在那个年代，林纳斯能做到这一点，和他自己的才能与设计天赋不无关系。《大教堂和集市》一书中对林纳斯的描述是：

他更像是一个工程实施上的天才，他具备一种避免 bug 和防范开发走入死胡同的第六感，而且有一种能发现从 A 点到 B 点最省力路径的真本事，事实上，Linux 的整个设计，都透露着这种特质，并反映了林纳斯那种本质上保守而简洁的设计取向。

在移动互联网时代，及早发布、快速发布还会带来另一个附加值：如果你的 App 能够一周更新一次，那么用户永远不会忘记这些 App 和开发者，他们知道这些 App 的后面有一群鲜活的生命在不断的进行产品改进、性能调优、功能增强，通过频繁的发布，用户是能够感知到这些数据之外的东西，并给你丰厚的回报。

## 9、如果一个问题解决不了，那么要问问自己，是不是提出了正确的问题。

当你发现自己在开发中四处碰壁的时候，当你发现自己苦苦思索也难以确定下一个特征的时候，当你发现自己辗转腾挪也无法解决一个老问题的时候……停下来，喝杯咖啡吹吹风，你会发现，过了今天问题还是解决不了。

通常这时候，你不该再问自己是否找到了正确答案，而是是否提出了正确的问题，也许是问题本身需要被重新定义。

在不损失效能的前提下，不要犹豫，扔掉那些过时的特性吧。为了挽救 IE6的用户，还不如去为那些愿意使用高级浏览器（支持 HTML5）的用户提供更好的服务。

## 10、设计上的完美并不是没有东西可以加了，而是没东西可以减。

有时候，我们在软件设计的时候会尽可能让自己表现的聪明而有原创性，这让我们在前行的时候常常忽略那能够直达目的地的小径，我们被蓝色湖泊上飘荡着雾气吸引，在高山上怒放的美丽花朵之间徜徉，而忘记了真正的目标。

在应该保持软件健壮性和简单性的时候，设计者常常下意识把它弄得既华丽又复杂。应该用自动内存管理的时候使用了引用计数，能够最简实现的时候使用了各种设计模式，也许在潜意识里，很多程序员认为，使用了复杂技巧并难以读懂的代码才是好代码。

对于产品的设计和实现来说，增加功能和代码是最容易做到的，反而是代码减无可减，功能砍无可砍，最难实现。如果你的产品减少任何一个功能都会带来完整性和体验缺失的话，这款产品的功能就已经接近完美了，代码同样如此。

无论是产品设计还是编程实现，永远记住这样一个原则：KISS （keep it simple and stupid），简单即为美。

……

Linux 可以说是 IT 发展史上圣杯级别的产品，它的故事没有终点。几十年过去了，Linux 散落在历史长河中的点点滴滴，依然像耀眼的珍珠一样在时间的深水河中发出璀璨的光芒。如果你是一个开发者，多读读 Linux 相关的技术书；如果你是互联网从业者，多读读 Linux 相关的故事和传奇。如果你两者都不是，多读读 MacTalk 就好了。