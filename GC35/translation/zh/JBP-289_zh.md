# JBP-289 - 更新和增加经常性支付给filipv的费用
````plain text
作者: filipv
日期: 2022-11-04
```

## 简介

更新并增加对filipv的经常性支付，从6000美元/FC → 6500美元/FC。

##近期工作

(WIP,不是详尽的)

### 子图

- [实施AddToBalance事件](https://github.com/jbx-protocol/juice-subgraph/commit/ed0fd01cb3c4b3fc964d815d6111b80def1487bd)到所有协议版本的Subgraph中。

- 为所有协议版本[实施资金周期](https://github.com/jbx-protocol/juice-subgraph/pull/20) `配置`和`启动`事件（审查中）。这将允许用户在项目活动反馈和其他服务中看到排队的重新配置和更新的资金周期。将所有元数据解包库移植到AssemblyScript，允许在子图上直接查看资金周期元数据。

### 前端

- [实施AddToBalance事件](https://github.com/jbx-protocol/juice-interface/pull/2176)到项目活动反馈中。

- 创建了[juice-rss](https://github.com/filipvvv/juice-rss)，一个用于Juicebox项目的RSS通知服务。一个实时实例可在[https://juice-rss.deno.dev](https://juice-rss.deno.dev)上找到。RSS是一种流行的通知服务，可以与IFTTT、Zapier和其他服务一起使用，生成电子邮件通知、Discord消息或其他集成。

### 文档

- 对[juice-docs]（https://github.com/jbx-protocol/juice-docs）进行持续的技术维护。这包括建立[新主页](https://info.juicebox.money/)，实现Algolia DocSearch，修复bug，包维护等等。

- 记录NFT的奖励。这是一项正在进行的工作，将是未来一两个星期的重点。目前的工作在[https://info.juicebox.money](https://info.juicebox.money)上进行。

- 创建指南和教程，包括。

	- [**用Juicebox启动一个自定义的以太坊（配置指南）**](https://youtu.be/kWxaFn4iwug) (~500 views).

	- [**Juicebox：在5分钟内制作一个以太坊库房和一个代币**](https://youtu.be/pJszOKMxYNE) (~300 views)

	- 配置指南见[https://info.juicebox.money/user](https://info.juicebox.money/user)

	- [Snapshot](https://info.juicebox.money/user/governance/snapshot)、[Gnosis Safe](https://info.juicebox.money/user/governance/gnosis)和[Discord](https://info.juicebox.money/user/community/discord/dao/)的指南。

### 社区结盟

- Discord服务器管理。

- Discord公告的Webhook服务。昨天首次使用。

- "社区管理 "工作。回答问题，回复咨询，等等。

- 与@Nicholas合作举办市政厅。录音、议程等。

- 维护Notion，包括提案数据库（Notion看门人）。

- 维护DAO的YouTube频道。

###记账

- [juice-accountant](https://github.com/filipvvv/juice-accountant)为[Juicebox](https://juicebox.money/)自动生成会计CSV文件。
 项目：它检索并处理代币持有者、支付、赎回和分配，然后生成CSV文件，并以你选择的货币进行法币转换。这对任何想要做账或交税的项目创建者都很有帮助。

- [juice-fees](https://github.com/filipvvv/juice-fees)为每个Juicebox项目支付的费用生成会计CSV文件，并以你选择的货币进行法币转换。

- [safe-refunds](https://github.com/filipvvv/safe-refunds)生成Gnosis保险箱已执行交易、执行人和气体费用的CSV。这是为计算Juicebox multisig的气体退款而创建的，但可以被任何使用Gnosis保险箱的项目创建者（或其他任何人）使用。

- [各种会计/簿记工作](https://github.com/filipvvv/juice-accounting)包括资产负债表和其他一些文件。

### 杂项

- 各种治理工作，包括本资助周期的修正案。治理工作在这一点上应该是相当稳定的。迄今为止，已撰写了51份提案。希望随着时间的推移，这一点也能逐渐减少。

- 多重认证工作。更新成员，排队/验证交易，以及其他操作。@twodam做了大部分的工作。

- 探讨了各种法币的选择。目前还没有完全达到效果。

- 帮助了几个项目的创建者。讨论，项目配置，营销策略，让他们与律师联系，等等。

- 解决各种Etherscan验证问题。

- 代表DAO在几个播客和活动中发言，包括。

	- [**为你的下一个Web3项目筹集资金的灵活方式|Filip from Juicebox**](https://podcasts.apple.com/sk/podcast/the-flexible-way-to-fundraise-for-your-next-web3/id1614643326?i=1000581786444)

	- [**DAO新闻报道：2022年7月20日--由Juicebox的Filip介绍**](https://podcasts.apple.com/us/podcast/dao-news-report-july-20-2022-featuring-filip-from-juicebox/id1630815761?i=1000570565500)

	- **人际网络播客（12月发布）**。

	- DAOPlanet NYC

	- 几个Twitter空间

- 在这个[法律工具](https://daolabs-docs.on.fleek.co/legal/intro/start.md)上为Juicebox项目做了大量工作。还没有完成。不过介绍部分很好，我将把它移到项目创建者文档中。在这个项目上投入的时间相当疯狂。

- 关于[DAO服务条款](https://info.juicebox.money/tos)的工作。

## 即将到来的优先事项

- 完成NFT奖励的记录工作。

- 学习Dune。

- 在前台进行项目配置和启动。

- 让法币支付为JBM工作。

- 更好的通知服务。

- 升级项目搜索（也许还有索引）。

- 继续上述其他项目。

- 开始关闭Notion。

- 修改项目创建者的文档。维基风格。

- 专注于项目创建者的工具和分发。

也可能对juicebox.money-looking的[Metamask onboarding library](https://docs.metamask.io/guide/onboarding-library.html)的上机经验感兴趣。

## 规范

将DAO的v2库对filipv的分配从6000美元/FC增加到6500美元/FC。

##风险

这些资金可能会在其他地方得到更好的利用。

## 时间表

在本提案获得批准后的第一个供资周期内，在 "快照 "中更新这一赔款。在FC#42中取消这一支付方式。
