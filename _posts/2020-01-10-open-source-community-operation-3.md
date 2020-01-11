---
layout: post
title: 【社区运营思考系列3】看起来反商业逻辑的开源，为什么生命力这样持久？
excerpt: "开源是情怀、是政治、还是商业？"
categories: [management]
modified: 2020-01-10
comments: true
---

### 为什么写这一篇？

快下班时，有个多年不见的同事通过IM问我了几个问题：

1. 为什么会有开发者投入到开源项目中贡献，难道情怀可以当饭吃？

2. 现在的商业公司为什么会投入做开源？

这两个问题问得很好，我当时很忙，但还是跟他通了电话，解释了一通，他反馈说我的解释能够将故事讲圆了，满意。不知道是不是假客套。最后一个小插曲，说完正题之后再表。


### 先感谢

这些问题在我从事这个领域的过程中也有不同的理解，但自我感觉通透，还是从事[openEuler](openeuler.org)开源运营之后。

感谢SM Zhang、Junping Du等几位朋友，我印象中他们的一些观点或者故事对我很有启发。

### 1. 开源软件从玩具到可规模赚钱

潜台词：”雷锋“有，但极少，不给钱大多数浑身冰凉发挥不了预热。

开源软件的起源，的确是几个有情怀的人做出来的，包括Linus Torvals、Richard Stallman (*我不善于记忆，随便诌几个名字*)等一批人，把代码开放出来，让软件基本可用，比如Linux，但离规模商用还差很远，那时候更像一个玩具熊。

开源软件可以商业变现，要归功于（或者归咎于）IBM。

我记得很清楚，在十来年前刚工作的时候，每发布一个软件版本，我们需要提供三个包，分半是：

- Solaris，泡在SUN的小型机上
- AIX，跑在IBM的小型机上
- HP-UX，跑在HP的小型机上

一份源代码，编译出3个包，可见有多么不方便。

也就是说，当时的服务器市场主要由SUN、IBM和HP瓜分了，上面的操作系统是各自基于Unix做的版本，互相不完全兼容。

大约在2000年的时候，三国之一的IBM为了瓜分更大的地盘，走了一个险招，从Unix转型Linux操作系统。对客户来讲可以说方便了客户，不用再编译三个包了，对自己来说，如果Linux支持IBM支持得最好，那么IBM有机会拿下HP和SUN。

实际情况是，那时候Linux很弱小，满足度很低，现在Red Hat的龙头产品[RHEL当时还没有发布第一个版本](https://en.wikipedia.org/wiki/Red_Hat_Enterprise_Linux#RHEL_2.1)。所以IBM帮助这些Linux玩家，在服务器市场带着这些小兄弟玩儿，逐步催熟了Linux。

这一招的确把仅配套Unix操作系统的对手打败了，当然了对手失败自己是否得利，是另外一回事儿。

总之，因为这段历史，玩儿开源软件的确可以赚钱了，全球开源软件玩儿最好的Red Hat已经突破了30亿美元的年收入水平。

### 2. 商业公司为什么热衷于对开源软件进行投入

首先，要追求利润最大化，垄断是最佳的；而要实现垄断，开源肯定不是好选择，因为开源就意味着对手也可以拿到同样的代码。

那么，追求利润最大化的商业公司，为什么会热衷于投资开源软件？

Linux的商业成功，的确带动了一批试图通过开源软件实现商业成功的公司。也是因为这样，开源软件越来越多。而随着技术的发展，社会需求也越来越复杂，背后的软件也越来越复杂，在这个过程中，每个软件产品都或多或少地用到了开源软件。要用好软件，就需要懂这款软件，这决定了需要在开源软件上有一定的投入。

更重要的是，商业模式在发生着巨大变化。

通过软件赚钱有几种可能的模式：

- 靠硬件变现，软件免费，为了让硬件可用
- 靠软件License赚钱，也就是一个软件包多少钱
- 靠服务赚钱，比如软件免费赠送，但维护需要收费
- 靠云服务赚钱

真正可怕的是最后一种，云服务的商业模式。可以说，云服务这种商业模式是一个巨大变化，因为客户可以像使用水电一样使用IT服务，这种模式的诞生，对仍然使用传统商业模式的软件开发商造成了沉重打击。

而云服务背后的软件是开源，还是闭源，相对来讲已经无关紧要。云服务比拼的是服务的丰富性、易用性以及低成本（包含风火水电服务器软件开发维护等）。

所以，商业公司之所以大力投入开源，是因为在新商业模式下，开源闭源已经不是竞争力的关键了，干脆，一起玩还能降低些微的开发成本。

### 3. 开发者为什么愿意投入开源社区贡献呢？

通过前面两个的分析，可以知道，现在的开源社区已经是商业公司掌控的开源社区了，无论是Linux Foundation，还是Apache Foundation，大部分开源项目后面都是商业公司在投入。

所以，开发者投入开源社区，是因为商业公司需要，而不是开发者都是活雷锋。

然后，可能有人会问，开源社区的开发者貌似更有开发热情，为什么？

按照惯例，问为什么之前先问是不是。我的感觉是是，原因详见[软件开源，动了谁的蛋糕？](/_posts/2019-12-15-open-source-community-operation-1.md)。

我认为，软件源代码（自己的脑力劳动成果）可以跟着自己走、以及开源软件的广泛应用（此处不留爷，自有留爷处），是开发者必须有热情的内在原因。


### 延伸：难道就没有点儿情怀在里面，难道无论公司还是个人都是为了$$？

我自己的体会，当然不是。

愉快地工作，是不比金钱收入重要性低的一个指标。

相对来讲，我与开源社区的人合作，相对于和公司内的一些人合作，要愉快得多得多。主要有如下感受：

1. 交流效率高。真正公开的交流，而且是实名的，会让每个人讲话需要三思，开源社区几乎没有键盘侠的存在。所以大家会自觉地把一件事情经过深度思考再详细写出来，看起来慢，实则快。而我在公司内最大的感受是，即时消息满天飞、电话满天飞，但经常遇到要求都提不清楚，动不动需要“拉通”。
2. 被尊重的感觉。也是因为全部是公开的交流，每个人都不会随便暴露自己恶的一面，偶尔遇到奇葩，也有机会深呼吸，毕竟大部分交流是文本交流。哪怕是假客套，保持一直假客套，也就成了真尊重了。
3. 协作的感觉，很棒。
4. 包容性好。人太杂了，会让你意识到原来世界有如此的多样性，也就理解了。
5. 所谓的长期规划少。应该有规划，毫无疑问，但每个层面都搞规划，就不得不产生讲故事高手了，因为规划意味着预测，预测不就得讲故事？极少数人规划就行了，大部分人致力于把每一件是做好，快速迭代，好事儿自然也就发生了。


### Call back

文章开头儿说了，有个小插曲。

我跟他讲完电话，因为多年不见，我就顺口问了一句，你现在在忙什么呢，怎么关心起开源了。他回答说“我来了个电话，回头再聊吧”，就挂了电话，之后在IM上也没有留个言说个谢谢。

这家公司有不少人都这样，我摇头苦笑，去食堂吃饭了。