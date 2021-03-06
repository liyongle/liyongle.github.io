---
layout: post
title: 【社区运营思考系列1】软件开源，动了谁的蛋糕？
excerpt: "开源软件社区运营话题很大，我的认识也很浅薄，边学边做边总结思考"
categories: [Open Source Community]
tags: [Open Source, Culture, Mindset]
modified: 2019-12-14
comments: true
---

## 背景

2019年，中美贸易战愈演愈烈，我也不知道到底为啥两个家伙就干起来了，不懂也不想动。脑子中经常浮现出我们农村人常说的”狗咬狗两嘴毛“，然后感觉自己好像能想到这句话本身就是罪恶的，于是乎强忍着不想，继续搬砖。

在这样的背景下，中国的科技领域开始意识到自己真的就是一暴发户，比如，在IT领域”缺芯少魂“的事实终于被大家接受了，于是乎，感觉一夜之间冒出了许多芯片、许多操作系统、许多数据库。

而这其中，用开源方式运作的更是数不胜举。大概是大家都希望别人能够来和自己一起构建生态，注意，关键词是”来“。

那么，开源手段对各方到底有什么影响呢？本文试图简单探讨一下。

## 对开发者，春天来了

对软件开发者来讲，从闭源开发方式转换为开源开发方式，几乎是只有收益没有弊端。具体来讲：

- 自己的劳动成果真的属于自己了。

从法律上来讲，在公司内开发，版权属于公司所有，不属于个人。相当年，不少人曾经因为试图将自己的代码转移到公司外而受到处罚，甚至锒铛入狱。而在开源模式下，代码公开可获得，自己的劳动成果可以让自己随时、随地地使用，只要符合开源协议。

- 自己的价值可以被更加公平地衡量

相对于闭源模式，开源模式工作场景下，价值创造的方式几乎不变，价值评价可以被更多人看到，价值分配也是如此。

所在公司、部门、主管，对自己进行价值评价时，或多或少地都会受到公司管理水平和价值观的影响。而在开源模式下，则价值可以被更多人看到。如果你是金子，则更容易发光发亮。

- 自己更有动力经营自己的项目

自己写的代码，只有在被更多人使用时价值才更大。闭源模式下，代码只可能被所在公司某个或者某些产品使用，并服务于所在公司的客户。而在开源模式下，优秀的代码可以被更多人使用，作者自己如果有追求，则会自然地更加用心地经营自己的项目。

经营项目包括但不限于

1. 对用户反馈及时响应

2. 对用户关心的新特性、新需求及时开发

3. 照顾热心参与到自己项目的开发中的朋友，进而让自己的产品功能更好、质量更高

如果说有”弊端“，那就是让东郭先生更加难以生存。

## 对于部门经理

在闭源场景下，虽然不同的公司程度不完全相同，但多数情况下，部门经理的权利有很多，可以决定任务分配，可以决定绩效评价结果，可以影响升职加薪，等等。

而在开源模式下，对部门经理的挑战会更大。他需要：

- 充分了解每个员工的能力和产出，并给出更加公平地评价

有这样一个说法，**如果部门经理需要根据代码量、commit数量等指标来评价员工，那只能说明这个部门经理是无能的**。

我个人非常认可这种说法，因为软件开发是脑力劳动，同样的功能，A可以用100行代码完成，B可以用1000行，孰优孰劣，需要从功能、性能、可维护性等多角度评价，如果只看代码量，那真的是无能。

所以，开源模式下，对部门经理是挑战更是鞭策。努力吧！

## 对公司来讲，利弊都有

### 先说”弊“

公司把代码开源出去，从上面两点看，增加了公司的管理难度。比如一个因为公司人力资源水平或者部门经理管理水平低下而略受委屈，在开源场景下，因为封闭结构变成了耗散结构，他很可能被其他有同样需求的公司挖走。这姑且算弊吧。

另外，开源还是闭源，对一个公司的战略能力也提出了更高的要求。开源社区的价值和公司的商业价值如何平衡，如何让开源促进商业，需要论证清楚。

### 再说”利“

如果一个软件项目或者产品的开源战略是合理的，那么在执行好的情况下，这个公司有如下可能的方面受益。

- 打破竞争对手的垄断

- 节约开发成本

- 更早得到客户的反馈

- 赢得客户信任(没有机会放所谓的后门了)

- 更容易构建技术生态

## 对用户来讲，采购难度可能增大了

在闭源时代，用户的选择或者采购行为，更多地靠供应商的推销，以及必要的测试等，运作承受的采购体系可以把风险控制到比较低的水平。

在开源时代，一个供应商拿着一个依赖开源软件做起来的产品来销售时，你不得不考虑更多问题：

- 这个产品用了多少开源软件，这个厂家对哪些可以兜底？

- 这个厂家会不会管理产品中用到的开源软件？

微软对开源软件有这样一个说法，非常精准。开源软件就像免费的宠物，如果你只养一只免费的宠物，你会很轻松，也会很愉快；如果你有成千上万只免费的宠物，虽然是免费的，但你如果照顾不好任何一只，那就可能出大问题。可能没有人喜欢成千上万只宠物。

这个说法对应的就是，如果一个产品使用了成千上万款开源软件（非常常见），那么就意味着有成千上万款软件会有bug、安全漏洞风险，而几乎没有哪家供应商敢说自己可以对着成千上万款软件都可以维护得很好。

## 小结

开源，是开发者的春天。如果每个开发者都在开源社区通过技术能力展示自己的价值，那么他所从事的项目也很有可能成功，进而项目（产品）成功的可能性也增加了。用户、厂家、开发者，总体来讲是多赢的。

## 预告

这个系列主要是自己思考的点滴记录，目的是提高自己，欢迎大家给出反馈。

下一篇我想从成本和收益的角度来分析一下。


## 强烈推荐下面的文章

1. [给孩子看的西方政治学](https://mp.weixin.qq.com/s/cuShGU1k1tGv87iMKceUPA)
