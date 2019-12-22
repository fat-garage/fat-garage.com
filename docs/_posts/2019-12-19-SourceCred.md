---
title: SourceCred：让你的贡献在组织中能看得见
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2019/2019121901.png
---
### 导读

DAO组织是什么？想解决什么问题？

DAO组织较核心但被忽视的问题-怎样评估成员的贡献并给予相应的激励？

SourceCred在这方面尝试和创新方向：
1）基于交互算法形成的贡献图谱 
2）根据事先的算法规则，每一次贡献都可以获得信誉（Cred），信誉兑换token

### 正文

现在组织人类活动的经典模式是集中的，自上而下的机构，比如公司。有一个人控制着公司的资本，他们付钱让员工做符合公司目标的事情，这是非常有效的，不容置疑公司创造了巨大的生产力。但这个过程中，由于集权所带来个人价值的埋没，以及无法预测的个体的脆弱性也凸显出来。简单说，就是你为公司贡献了很多，但到头来奖励和声誉永远只属于掌权者；莫名其妙的被解雇也是常见的事。此外，企业只擅长优化利润和资本回报率，但这种动力很难评价好坏，对于公司来说可以短时间内成就估值上亿的独角兽，对于个人你可以说我是那独角兽的员工但Sadly我并没有股票。

于是新的组织方式出现了，比如DAOs。

![图片](/assets/2019/2019121902.png)

### DAO组织想解决什么问题？
几个点个人感觉比较性感：
1. 让参与者可以从组织的壮大中，根据自己的贡献程度获得相应的收益

2. 参与者的贡献的衡量不是由一个人或者一个中心化的决策方给出的。而是基于类似于peer review或交互算法

3. 项目支持者和贡献者能看到资金如何得到了适当的分配

DAO组织权限自由，每个人都可以参与，不像公司那样有腐败的中央集权。我们可以看到开源项目是这种模式最成功/最广泛的应用。超级去中心化，人们出于共同的兴趣或热情走到一起，创造出伟大的东西。**DAOs提供的最令人兴奋的可能性之一是能够更公平地补偿人们所创造的价值。但如何衡量价值呢？这种价值以何种形式得到回报？这可能是最困难的挑战。**

DAO经常使用某种形式的“活动度量”来度量价值，例如执行一个角色所花费的时间($/hr)、产生的单位工作量(比如一串代码)或性能度量(例如代码被引用的次数)，这些都是有据可循的明面上的东西，比较容易量化。但那些受到“扁平化效应”的影响，不易被量化的工作，像UI设计，度量标准也必须做相应的更改。

在DAO中，参与者可以选择匿名，并且完全可以从事超越传统雇佣角色的活动。成员可以自由地在不同的领域、不同的技能水平上增加价值，并以新的创造性方式进行合作；如果不是这样，那么与传统公司就没什么两样。因此，DAOs必须以一种不过度依赖传统角色或任务定义的方式来评估贡献。

### SourceCred的基于信誉的贡献评估
最近看到一个叫做SourceCred的项目，目标是创建一个去中心化的协议来评估人们的贡献的价值。与传统的公司模式相比，这种模式的集中度要低得多：不是由CEO来决定每个人的薪酬，而是每个人都参与了信誉的流动。信誉的分配不是完全靠算法，人的干预(在我理解是调整贡献权重等）在SourceCred中起到一个引导的作用，主观性以一种有原则和透明的方式被应用，与数据和复杂的算法相结合，因此。这个结果比数据或判断单独产生的结果更好。

![图片](/assets/2019/2019121903.png)

每个成员的贡献和关系网络构成了一个贡献图。SourceCred将PageRank算法应用于此图，生成一个分数，每个贡献称为cred。它的基本思想是：如果一个贡献与其他贡献相联系，那么它就能获得信誉。贡献者与他们帮助过的贡献者相联系，他们也可以获得相关信誉。

项目的社区和维护者在这个过程中有很大的主动权，可以重新配置源的权重和参数（上面提到的人的干预）。例如，他们可以为一些非常重要的贡献分配额外的权重，或者减少那些看起来垃圾的贡献的权重，这些指标都是可以自定义的。

SC在前两个月前将这套算法整合进了自己的论坛Discourse中，论坛中的贡献者每发一篇文章，一个回复、点赞、引用等等都会根据预先设定好的算法获得对应的信誉。

![图片](/assets/2019/2019121904.png)

在有了信誉分之后，成员们就可以拿去兑换相应的token了，简单说，逻辑如下：

社区成员做出贡献-->根据算法获得对应声誉（Cred）-->对应兑换token（Grain）-->变现

*Grain是SourceCred的社区token，随着SourceCred协议的成熟，届时信誉将与Grain 结合起来，每一个为一个基于信条的项目做出贡献的人都会得到关于他们的贡献有多有价值（对应多少token）的明确反馈，并且会得到项目本身长期利益的回报。

### 结尾
SourceCred提出了一种的基于信誉的对成员贡献评估的思考（没有着重讨论任务的分配），目前这种试验也在他们自己的社区中进行，比自上而下的二元参与的公司结构，DAO组织确实可以有更多设计的空间。最近我也尝试加入了一些DAO组织的实践，发现了一些有趣的现象，比如，

首先，当你作出一些贡献之后，最终是由“一个人”用一个excel表格告诉你，你可以获得什么样的奖励，这多少有点奇怪。

另一个现象是DAO组织并不能清晰的定义目标和对应的任务奖励，这或许不是问题，但是当成员加入了相应的项目后，会有相应对自己贡献的一些期待。只是列出的角色和职责我觉得这是「公司」就可以做的事情。

第三，token对于贡献者的意义。Sourcecred培养了一批真正对社区有着很强认知的成员（从他们的大量讨论中就可以看出）。前期的持有者一定不能认为拿到的token只是一种业余时间赚外快的消遣，token现在能做什么，将来能做什么，对于组织来说意味着什么是创始成员们需要考虑和达成一定共识的。

西方的思想偏向于首先去定义一些框架性的规则、做大量“哲学性”的讨论，开发出相应的工具，然后把他们用于实践中。而大多数国内的实践是先讲一个故事，把你带入到相应的情境中，再去开发相应的工具。没有孰好孰坏，土壤不同罢了。

Sourcecred的论坛有很多关于DAO的讨论，而且他们本身也在实践这种分布式协作方式去开发、宣传这个产品（每周线上社区例会、协作播客、研究等等）。上个月我在上面问了一大堆问题，没想到收到了很多回复（[Some questions as a new comer](https://discourse.sourcecred.io/t/some-questions-as-a-new-comer/337/3)）。然后就顺理成章的邀请创始人dc入驻了胖车库🤩。

![图片](/assets/2019/2019121905.png)

参考资料：

[SourceCred and DAOs: A Sketch](https://discourse.sourcecred.io/t/sourcecred-and-daos-a-sketch/161/6)

[DAO Reputation System Challenges](https://discourse.sourcecred.io/t/dao-reputation-system-challenges/165)

编译：Jessie