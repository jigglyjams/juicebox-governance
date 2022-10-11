## 简介

什么是想法？

延长对jigglyjams的经常性支付，每个周期5000美元，共4个周期（共20,000美元）。

## 激励

_这能解决什么问题？为什么是现在？

治理自动化对于Juicebox的长期成功至关重要。nance项目在juicebox DAO的治理自动化方面取得了重大进展，但仍有更多工作要做。就在过去几周，twodam和jigglyjams一直在大力合作，为juicebox的治理建立一个独立的工具（见alpha [https://juicetool.xyz/nance/juicebox](https://juicetool.xyz/nance/juicebox)）。这有助于向提案提交者澄清哪些字段是提交提案所必需的，并有助于自动进行支付提案的配置。

DAO的高报酬成员做低层次的繁琐工作的时间仍然太多。nance已经成功地进行了V2和V3库房的自动重新配置，为多义词成员节省了大量的时间和头痛的问题。V1金库的配置仍然非常繁琐，必须自动化，以防止出现意外的昂贵错误。

##规范

_究竟将如何执行？要具体，不要留下任何模糊的地方。

将jigglyjam的V2 juicebox项目（id: 188）加入juicebox dao的V2库的资金分配中，金额为5000美元的ETH。

## 理论依据

_为什么这个规范是合适的？

自从jigglyjam提出第一个经常性支付建议（JBP-221）以来，已经完成了以下事情。

- 在投票阶段使用deepl API对提案进行自动翻译，并存储在GitHub中（见[https://github.com/jigglyjams/juicebox-governance/tree/main/GC32/translation/zh](https://github.com/jigglyjams/juicebox-governance/tree/main/GC32/translation/zh)

- 在GitHub中备份提案和投票结果(见[https://github.com/jigglyjams/juicebox-governance/blob/main/DATABASE.md](https://github.com/jigglyjams/juicebox-governance/blob/main/DATABASE.md))

- 在概念数据库中增加支持支付路径信息的列

- 为JB库V2和V3的赔款重新配置自动进行Gnosis交易排队（这为多签名者节省了很多时间！）。

- 许多错误的修正和对概念→不和谐→快照信息流的整体收紧

- **gnance.eth已经向快照提交了86个建议**，还有很多建议提交给了discord

- jigglyjams通过对juice-sdk的贡献来协助peeldao（见[https://github.com/jbx-protocol/juice-sdk-v3/pull/1](https://github.com/jbx-protocol/juice-sdk-v3/pull/1)）。

- jigglyjams协助了multisig的伟大牧民工作。

随着jigglyjam的经常性支付的继续，将完成以下任务。

- 自动配置V1库房 - _jigglyjams将与twodam合作，使之成为DAO和multisig成员的绝佳体验_。

- 自动同步所有JB的juicebox库房

- 迁离notion - jigglyjams计划将juicebox慢慢迁离notion作为提案存储系统。一个原型仍然需要建立，但jigglyjams计划使用dolt（sql数据库的git）来版本和存储治理数据库。最初，juicetool将同时向notion和新的治理存储系统提交提案，当新系统完全运行，并且dao对其能力感到满意时，我们将关闭与notion的连接。

- 让其他juicebox项目更容易获得nance--nance为juicebox dao提供的便利将吸引其他daos进入该平台。通过twodam和juicetool完成上述任务（从notion迁移），将成为扩展到其他juicebox项目的主要催化剂。

- 关于通过Nance的提案数量的统计数字

## 风险

什么会出错？

jigglyjams可能无法完成这项工作。补救措施：_jigglyjams在过去的5个月里一直积极参与，非常享受这项工作，并成为JB的一部分。

## 时间轴

_本提案究竟应在何时生效？这个提案到底应该什么时候结束？

本提案应在GC#33的重新配置中生效，并保持到GC#36。
