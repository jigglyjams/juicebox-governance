## 论文

撤销[JBP-186: 启动财务管理](https://snapshot.org/#/jbdao.eth/proposal/0xfce85632456d2cb91cd8361c0f79707de7a4ef4608912ab0d01c9d8abb5619d5)的未完成部分，并重新分配已经分配的ETH。

## 动机

JBP-186的许多部分还未执行，没有明确的执行路径。生态系统的状况已经发生了很大的变化，这意味着原来的计划可能不再适用了。

##规范

- Revoke [JBP-186: Launch Treasury Management](https://snapshot.org/#/jbdao.eth/proposal/0xfce85632456d2cb91cd8361c0f79707de7a4ef4608912ab0d01c9d8abb5619d5).

Multisig to:

- 用400wETH交换Lido stETH。

- 将400wETH换成火箭池rETH。

- 用422.33wETH换取Maker DAI

本规范应利用已经在multisig-not treasury ETH中的wETH。

## 理论依据

- stETH和rETH是相对分散的收益率资产，具有高流动性和数量锁定。

- DAI是一个相对分散的稳定币，具有高流动性和数量锁定。

##风险

Juicebox DAO将继承stETH、rETH、DAI的固有风险；以及它们的社区、市场波动、它们的智能合约和其中的任何漏洞。Juicebox DAO也可能错过其当前投资组合（几乎完全是ETH）的上升空间。

## 时间线

交换的时间表和策略应在DAO的多签名人的决定下进行。在Ethereum Shanghai升级或2023年1月1日的较早时间，撤销本提案的任何未完成部分。
