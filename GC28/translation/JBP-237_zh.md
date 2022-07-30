
```纯文本
作者: gulan
日期: (2022-07-29)
```

## 论文

授权记账员报销multisig为执行交易而花费的汽油费。在multisig中添加gulan，以创建报销交易。

## ＃＃动机

目前还没有正式的政策来规定多人组报销汽油费。我们应该正式授权簿记员继续报销汽油费。

## ＃＃＃规范

簿记员应不时地审查道的多义词所产生的eth费用，并报销eth中的地址所产生的费用。

- 簿记员应计算出报销所需的eth总额，然后换算成美元。

- 簿记员应将所需的美元金额加到mutlsig地址上。

- 记账员或multisig的其他成员应随后从gnosis创建一个交易，向所需各方报销正确的金额。

- 然后，multisig签署并执行该交易。

将gulan作为记账员加入multisig，以便他们能够创建报销交易。Gulan不会签署交易，也不会对法定人数百分比作出贡献。gnosis的投票要求应保持不变。

## 理论依据

目前还没有正式的政策来补偿multisig成员在multisig执行的交易中的天然气费用。该流程将现有流程正式化，并将gulan添加到multisig中，作为交易创建的一个额外选项，并将确保对交易状态和记录的跟踪。

##风险

用户的首选地址可能会改变。

ETH的价格在配置和执行之间可能会发生变化，导致发送给multisig报销的资金过多或过少。像所有的multisig转账一样，这将要求multisig使用multisig钱包中未分配的资金来支付增加的费用，或者在mutisig钱包中产生未分配的资金，这些资金可以更好地用于财政或其他投资。

## 时间线

 如果通过快照，尽快