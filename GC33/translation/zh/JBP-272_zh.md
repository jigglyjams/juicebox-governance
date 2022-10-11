## 简介

向[NFT Rewards Audit Fund](https://juicebox.money/@auditfund) Juicebox项目发送价值73.8千美元的ETH，该项目正在为NFT Rewards合同的Code4rena审计筹集资金，将花费7.2千美元，加上2.5%的JB费用，总计7.38千美元。

在筹款截止日期前（大约10月17日），资助300万JBX的分配，在审计基金的捐助者之间进行分配。  

这个提议也将作为Juicebox和Code4rena的试点整合，他们询问如何使用Juicebox协议，允许任何人为C4A智能合约审计筹款。

## 动机

NFT Rewards合约很复杂，与Juicebox协议的各种承受力深度融合，允许分级NFT奖励、NFT是溢出的债权，以及NFT治理代币，可以直接控制链上治理的Juicebox项目。虽然NFT奖励只依附于特定的JBP融资周期，但如果合约没有错误和漏洞，那就最好了。

最近几周，C4A联系了尼古拉斯，询问他们如何使用JBP为以太坊上的任何协议或智能合约无权限地创建筹款池。他们的目标是让任何人都能向审计池捐款，这些钱可以用于C4A的代码竞赛。他们观察到，许多DAO想要互相审计以提高技术依赖性的警惕性。智能合约的个人利益相关者、用户和观察者也可能想投其所好，资助审计，而不需要单独支持审计的全部费用。

这个建议是一个试点项目的一部分，通过在主网上的测量实验来推进这种整合伙伴关系。NFT Rewards审计基金](https://juicebox.money/@auditfund)是一个JB项目，为支付NFT Rewards合同审计筹集资金。它正在接受公众的捐赠。目标是筹集7.38万美元，然后将资金作为DAI发放给C4A，启动NFT Rewards审计竞赛。如果JBDAO支持本提案，那么它将把73.8K美元放回国库而不产生任何新的代币（`addToBalance()`）。如果这个提议通过，最初筹款的捐赠者将能够赎回他们的代币，以获得原始捐赠的退款--由JBDAO提供，他们将拿起账单。

为了在10月18日启动比赛，C4A需要在10月17日前收到资金。为了激励NFT奖励审核基金的支持者在这个截止日期之前，如果这个提议被批准，JBDAO将向在10月17日16:00 UTC之前支付项目的捐助者分发300万JBX（JBDAO目前JBX头寸的1.4%）。100万JBX将平均分配给在">0.1到<1eth"，">1eth到<10eth"，">10eth "每个层级内捐赠的钱包。这激励了较大的捐赠者，他们将与较少的同级别的成员分享JBX奖励。

这个实验使我们能够定位和解决在推出JBP x C4A整合伙伴关系中的路障。这些都在[Discord](https://discord.com/channels/775859454780244028/1024114191419834468)中被积极记录和讨论。这个项目将同时让NFT Rewards接受C4A的审计，这是协议制定者最近的首选审计方案，并有助于一个真正的实验，推动合作关系的讨论，发现并创造解决问题的方法。例如，DrGorilla正在[编写一个分配器](https://github.com/jbx-protocol/juice-extensions-collection/blob/4f54fdcb47a8e8c152c4970af0c2fcf07dff10b5/contracts/Allocator/example/swapAllocator/SwapAllocator.sol)，这将允许任何JB项目以DAI进行支付，因为C4A要求竞赛以稳定币进行资助。注意：这个特殊的功能可能会也可能不会在NFT奖励审核中及时发货。

##规范

从JBDAO v1向0x6052faf32b26edbbcfadb5527654e458fe7c0e35（v2/256项目支付方，不铸造代币）支付73.8k美元。

从multisig发送300万JBX到safe.auditfund.eth。尼古拉斯，Jango和JB多义词将协调使代币根据上述捐赠层级提供给符合条件的地址。

## 理论依据

这是一个项目支付者地址，将资金指向@auditfund（v2项目256），而不铸造任何新的代币。这将使v1版JBDAO国库能够支付v2版的@auditfund。

## 风险

256项目可能被错误配置，赎回可能在某种程度上不按计划进行。合作关系的谈判也可能消失。

## 时间轴

添加到JBDAO v1和v2的当前周期赔付中。
