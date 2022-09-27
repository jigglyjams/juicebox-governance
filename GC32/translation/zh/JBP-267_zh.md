## 简介

给予multisig权限来设置[tokenUriResolver](https://info.juicebox.money/dev/api/contracts/jbprojects/write/settokenuriresolver/)。这个合同将给JBProjects NFTs元数据（图片+标题+描述）。

## 动机

每个JB项目都由一个NFT代表。目前，这些NFTs没有元数据。这个OpenSea屏幕截图显示了没有元数据的NFT的样子。

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d050407c-07bf-4f22-a446-1aa5cedfac48/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220927%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220927T062406Z&X-Amz-Expires=3600&X-Amz-Signature=9f40760dc95a2daaa90555e91a96662323d26f89b6e4689c74d49095a6b704d5&X-Amz-SignedHeaders=host&x-id=GetObject)

对JB项目来说，拥有NFT元数据是有益的，这样人们在查看包含Juciebox NFT的钱包和合同时就可以看到（甚至可能分享）这些NFT描述页面。这也是JB的一个品牌推广机会。

尼古拉斯正在开发一个链上svg渲染的tokenUriResolver（WIP [Github](https://github.com/nnnnicholas/juice-tokenUriResolver)），它在每个项目中默认看起来或多或少像下面的截图。如果项目拥有者愿意，他们可以用自己的uri解析器逻辑完全覆盖这种可视化（和附带的文本元数据）。美学和功能正在积极开发中，我预计tokenUriResolver将在未来几个月内多次更新。

有趣的是：这使用了@peri的Capsules字体，他在[https://cpsls.app](https://cpsls.app)创建并部署了链上字体。

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/836e4381-6d97-4ae1-88e9-f883be1d1836/F6C4D347-3D56-4431-863F-98761B5014CE.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220927%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220927T062406Z&X-Amz-Expires=3600&X-Amz-Signature=3dd5e47b6941194b9f57894fe8a01fcbcc8c73e366d4c859bd1060ea3eede8d4&X-Amz-SignedHeaders=host&x-id=GetObject)

## 规范

授予multisig设置和改变tokenUriResolver的权限。Nicholas和Jango（以及合同组的其他成员）将与multisig沟通，在他们认为必要的时候更新tokenUriResolver。

这个权限在3个月后被撤销，如果有必要，这个权限可以重新提出。

## 理论依据

tokenUriResolver是该协议的一个低风险参数。给予multisig更新它的开放性权限，对协议的安全性或可用性没有重大威胁，并给JBDAO的开发者提供了反复改进tokenUriResolver合约的机会。

## 风险

tokenUriResolver可能被用来部署具有欺骗性或不足的坏元数据。在极端糟糕的情况下，tokenUriResolver可以在不安全的NFT元数据浏览器中实现恶意的钱包互动--尽管OpenSea和其他主要市场有保护措施来消除这种威胁载体。

## 时间轴

给予multisig开放的许可，以更新tokenUriResolver，为期3个月。
