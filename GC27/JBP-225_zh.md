
 
```纯文本
作者。Tankbottoms.eth
日期：2022-07-15

```

## 论文

偿还智能合约和Banny（以及app.bannyverse.xyz）存储到主网的费用，估计费用为14,000美元。

## 动机

NFT的VeBanny资产可以完全存储在链上。这些资产的展示需要在Ethereum的生命周期内保存下来。要做到这一点，意味着要将Banny字符资产部署到智能合约存储。现在以太坊的成本特别低，因此部署和消耗气体的时间应该是现在左右。

##规范

关于代币中呈现的Banny字符的例子，见[https://black-lab-1027.on.fleek.co/?banny=20&lock=5](https://black-lab-1027.on.fleek.co/?banny=20&lock=5)
对于所有核心Banny资产的预览，这些资产在veToken中都有体现[https://black-lab-1027.on.fleek.co/secret.html](https://black-lab-1027.on.fleek.co/secret.html)，点击任何一个角色演示如何使该角色的所有配件可用于创建一个新的Banny角色，该角色打算被提供给铸币[https://app.bannyverse.xyz/](https://app.bannyverse.xyz/) - 为了使这些资产可用，我们需要将它们部署到Ethereum主网区块链上。

我们采取了一切努力使这项开支最小化，包括使用压缩方案，以及使用以太坊智能合约存储的存储文件系统，而不是由[BannyCommonUtils.sol contract.](https://github.com/tankbottoms/vebanny-bannyverse-on-chain)自动管理的普通合约存储。

虽然存储资产的成本很高，但让veToken持有者和app.bannyverse.xyz的用户永远可以访问这些资产的好处可以说是不可估量的。

能够部署Banny字符的地址控制着能够向存储合同添加更多的内容。我们可能想增加政策，以便一些人可以这样做，当然要注意的是，要产生气体成本。

这些合同已经由#合同组内部审查，但将再次通过适当的审查、文件和渠道。

## ＃＃理由

见规范。

##风险

智能合约的部署失败，一切都会丢失。
对Banny角色资产的使用为零。
Wagmi Studios声称Banny角色资产的版权受到侵犯，在成千上万的veTokens被铸造后，诉讼随之而来。

## 时间线

视情况而定。
