
```纯文本
作者。尼古拉斯
日期: 2022-09-09
```

## 简介

向@Jango支付22.5千美元的报销费用，用于他对Juicebox协议v3的Code4rena缓解审查安全审计。

## 动机

Jango支付了22.5千美元DAI，以预订Code4rena的安全审计。这是一个缓解审查，其中C4A监护人将审查Juicebox V3代码，该代码修补了[JBP-206 Sponsor Code4rena Audit](https://juicetool.xyz/snapshot/jbdao.eth/proposal/0x3bc54466f651d559b9e4ff45d1576085ec057fcb5bf6b85afacc5806b9c5a6f4)中发现的漏洞。

重要的是，JBDAO在V3的变化部署到主网之前，要资助对其进行安全审计。本着权宜之计，Jango先垫付了这笔钱。如果通过，这个提案将补偿他的费用。

比赛计划于2022年9月13日星期二开始。

以太坊Tx。  [https://etherscan.io/tx/0x2145844f4bc4b2b4fef8eba0b1c94af5e93ba8c2a9919733b55af24a33070cfd](https://etherscan.io/tx/0x2145844f4bc4b2b4fef8eba0b1c94af5e93ba8c2a9919733b55af24a33070cfd)

Discord confirmation from C4A: [https://discord.com/channels/775859454780244028/1012540289774268416/1017898679325184100](https://discord.com/channels/775859454780244028/1012540289774268416/1017898679325184100)

## ＃＃规范

- 在Juciebox V1项目的dao.jbx.eth上增加22.5千美元的报酬。

- 一旦分发，multisig应该将价值22.5美元的eth交换给DAI。

- 然后，多义体应将DAI转移到jango.eth中。

## 理论依据

本规范正确地报销了Jango的费用。

##风险

不正确的配置。审计不发生。这不是一个大的风险，因为比赛的开始日期是在这个提案的投票结束之前。

## 时间线

GC#31
