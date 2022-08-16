
```纯文本
作者: twodam.eth
日期: 2022-08-07
```

## 论文

_什么是想法？_

更新twodam.eth的经常性支付，并将支付转移到v2库房项目。

## ＃＃激励

为什么是现在？这能解决什么问题？

Juicebox V2已经在主网上运行，它提供了更多的功能和可能性。有必要<u>更新沙丘仪表板</u>以与新功能同步，例如。NFT奖励，财政扩展。

在目前准备重新配置的过程中，我需要几个小时/FC来审查和提交重新配置。有必要<u>编写工具和改进流程</u>，这样我们就可以有更多的自动系统，减少对某些人（目前是jango或我）的依赖来完成这项工作。如果我们更进一步，我们也可以将记账自动化，使之成为一个工具，并提供给juicebox协议的项目。

Juicebox没有新功能的官方公告渠道，虽然我们有定期的全体会议和个人会在推特上介绍功能，但仍有一些人想知道特定功能的状态或类似 "正在发生什么 "的问题。为什么不做[跟踪所有功能的页面](https://juicetool.xyz/progress)，如果可能的话，甚至做一个每周的通讯？(aggregating [0xSTVG’s weekly recap](https://twitter.com/0xSTVG/status/1553734201685422080?s=20&t=e1c06889Cro0EnzP00plgQ), [Zhape’s town-hall summary](https://twitter.com/zhape1112/status/1556085798176337920?s=20&t=gIkYqWPVd4lk6LsBZqRm_Q), [Matthew’s governance recap and podcast](https://twitter.com/0xmatthewb/status/1554495858581839874?s=20&t=e1c06889Cro0EnzP00plgQ) etc.)

##规范

_究竟如何执行？请具体说明，不要留下任何歧义。

从<u>**v2国库**</u>向[TwodamLab](https://www.juicebox.money/@twodam)项目(id: 115)支付5000美元的ETH，每个FC，共6FC(即：与前一个FC的行动相同)

## 理论依据

为什么这个规范是解决这个论题的最佳方式？

### 我将要做的事情

自动化和/或优化程序，例如：重新配置、记账和多签名交易验证。

实施和汇总juicebox的数据洞察力，例如。DAO健康分析，正在开发的项目/功能和资助项目的状态等。

将dune dashboards与v2数据完全整合，对那些因数据量不断增加而导致的超时进行优化查询。

部分可交付项目。

- <u>Juicebox通讯</u>，从成员（Jango、Aeolian、0xSTVG、Zhape、Matthew）那里汇总信息，每周/每两周分组，作为一站式的通讯，人们可以订阅（RSS Feed）。

- <u>Juicebox v2 Project dashboard</u> on dune, including treasury, community token, NFT rewards and extensions.

- <u>优化准备和提交新的重新配置的过程</u>，从导入记账CSV和生成重新配置的交易数据开始，如果可行的话，与nance整合，使其完全自动化。

- <u>优化dune上的token余额跟踪器</u>（由于查询的执行时间过长而超时）。

- <u>维护JuiceTool上的文档和工具</u>，包括更新功能进度、资助项目和时间表等。

- <u>在JuiceTool上完全实现DAO健康指标</u>（查看演示[这里](https://juicetool.xyz/metric))

### 我所做的事情

数据显示

- [Juicebox Protocol Overview](https://dune.com/twodam/Juicebox-Protocol-Overview), 更新为跟踪V2数据，实施了趋势项目（与jbm上的项目相同）。

- [Juicebox Portfolio](https://dune.com/twodam/Juicebox-Portfolio)，已更新以跟踪V2数据。

- [Juicebox Gas & Fun Facts](https://dune.com/twodam/Juicebox-Gas-and-Fun-Facts)，概述了普通行动的气体成本和一些有趣的事实。

- [Juicebox Logbook](https://dune.com/twodam/Juicebox-Logbook)，juicebox协议上所有活动的日志。

- [JBX机制](https://dune.com/twodam/JBX-Mechanism)，实现了JBX兑换分析（谁在兑换JBX？团队成员、项目负责人、用户或交易商）。

- [[文章]研究/比较类似的协议](/5d7075f7a9c44094abad463e121dcf14)，包括Juicebox, Mirror, Superfluid, Parcel, Coordinape.

工具

- [JuiceTool](https://juicetool.xyz/)，围绕Juicebox生态系统策划文档和工具。目前已实施文档和[snapshot plus](https://juicetool.xyz/snapshot/jbdao.eth)。

翻译

- 翻译和撰写zhape提案的摘要。([FC#22](https://discord.com/channels/775859454780244028/916924794358882384/972417988189884426), [FC#23](https://discord.com/channels/775859454780244028/916924794358882384/977449718579888148), [FC#24](https://discord.com/channels/775859454780244028/916924794358882384/982516926695763978))

- 启动信息网站的中文选项。([https://discord.com/channels/775859454780244028/993597487304691793/993857428460412988](https://discord.com/channels/775859454780244028/993597487304691793/993857428460412988))

簿记/多义词

- 每个周期与古兰一起审查记账文件。(e.g [https://discord.com/channels/775859454780244028/915334655144787998/1004359134596055050](https://discord.com/channels/775859454780244028/915334655144787998/1004359134596055050))

- 为多义词排队交易，在专用通道上保持背景和讨论。(e.g [https://discord.com/channels/775859454780244028/991382812718551060/994082245805621368](https://discord.com/channels/775859454780244028/991382812718551060/994082245805621368))

- 跟进已通过的、尚未完全执行/实施的提案。(e.g [https://discord.com/channels/775859454780244028/982051720089706508/988342376688922646](https://discord.com/channels/775859454780244028/982051720089706508/988342376688922646))

## 风险

什么可能出错？

特沃达姆没有做好他的工作。

缓解措施：Twodam已经贡献了~9个月，他从一开始到现在都履行了自己的承诺。

## 时间线

_本建议究竟何时生效？这个提案到底应该什么时候结束？

通过重新配置FC#29生效，在FC#35结束
