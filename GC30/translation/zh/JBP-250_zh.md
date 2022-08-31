
```纯文本
作者: jigglyjams
日期: 2022-08-26
```

## 论文

添加gnance.eth（0x50e70c43a5DD812e2309eAcea61348041011b4BA）作为Juicebox gnosis-safe（0xAF28bcB48C40dBC86f52D459A6562F658fc94B1e）的委托。这将允许nance自动排队交易到多重签名。gnance.eth不会持有执行交易的能力。

## 动机

我们想让多签名人的事情变得更简单。每个融资周期twoodam必须手动输入任何新的支付和储备率分配到项目重新配置。这可能是一项繁琐的工作，将其自动化将释放出重要贡献者的额外时间。

##规范

没有一个官方的应用程序可以将代表添加到保险箱中（gnosis只提供了一个API端点）。但是有一个开源项目实现了一个，[https://gnosis-delegator-soptq.vercel.app/](https://gnosis-delegator-soptq.vercel.app/)，其源代码是[https://github.com/Soptq/gnosis-safe-delegate-dapp](https://github.com/Soptq/gnosis-safe-delegate-dapp)。

**主要注意：该应用目前只支持MetaMask**。

如果获得批准，多签名者之一需要遵循以下步骤。

- 转到[https://gnosis-delegator-soptq.vercel.app/](https://gnosis-delegator-soptq.vercel.app/)

- 连接MetaMask钱包

- 加载Gnosis保险箱

- 添加0x50e70c43a5DD812e2309eAcea61348041011b4BA，标签'nance'

- 签署交易

- 完成了!

(如果有不清楚的地方，jigglyjams可以为上述内容制作一个视频)

## 理由

见动机。

关于多重签名代表的更多信息请见这里。[https://safe-docs.dev.gnosisdev.com/safe/docs/tutorial_tx_service_set_delegate/](https://safe-docs.dev.gnosisdev.com/safe/docs/tutorial_tx_service_set_delegate/)

## 风险

签名者可能没有MetaMask，使得这个提议有点难以实现。如果是这样的话，jigglyjams将向项目提交一份PR，以增加更多的钱包支持。

## 时间轴

在FC#31开始前实施，以便Nance能够自动提交FC#31的交易。
