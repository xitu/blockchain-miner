> * 原文地址：[What is Ethereum? A Step-by-Step Beginners Guide](https://blockgeeks.com/guides/ethereum/)
> * 原文作者：[blockgeeks.com](https://blockgeeks.com)
> * 译文出自：[掘金翻译计划 — 区块链分舵](https://github.com/xitu/blockchain-miner)
> * 本文永久链接：[https://github.com/xitu/blockchain-miner/tree/master/article/0001/what-is-ethereum.md](https://github.com/xitu/blockchain-miner/tree/master/article/0001/what-is-ethereum.md)
> * 译者：[cdpath](https://github.com/cdpath)
> * 校对者：[davelet](https://github.com/davelet)

# 以太坊初学者手把手教程

如果你想要了解什么是以太坊，知道它的工作原理和用途，却不愿陷入技术细节，这个教程就是为你准备的。

重要说明：本教程假设读者已对区块链技术有基本的了解。如果不熟悉区块链，可以先读一下这篇[《区块链初学者手把手教程》](http://blockgeeks.com/guides/what-is-blockchain-technology-a-step-by-step-guide-than-anyone-can-understand/)。

## 什么是以太坊教程？

**超越比特币及第一代去中心化应用**

尽管区块链的概念经常和[比特币](http://blockgeeks.com/guides/what-is-bitcoin-a-step-by-step-guide/)一起出现，也有很多区块链应用已经超越了数字货币的范畴。实际上，比特币只是当今几百种区块链应用中的一种。

![以太坊初学者手把手教程](https://blockgeeks.com/wp-content/uploads/2016/10/Sally-Davies-FT-Technology-Reporter-1-150x150.png) **_「区块链之于比特币，就如同互联网之于电子邮件。区块链是一个巨大的电子系统，可以在其基础上构建应用。货币只是基于区块链的一种应用。」_** [Sally Davies, FT 科技记者](https://twitter.com/daviesally)

不久之前，构建区块链应用仍然需要复杂的编程、加密和数学领域的背景知识，以及海量的（计算）资源。不过现在形势变了。先前无从想象的应用，从电子投票和资产电子记录，到合规（regulatory compliance）和交易都在以前所未有的速度被开发和部署。以太坊通过为开发者提供工具来构建去中心化的应用，让这一切成为可能。

## 什么是初学者的以太坊教程？

简单地讲，以太坊是基于区块链技术的开放软件平台，开发者可以在此平台上开发并部署去中心化应用。([点此购买以太币](http://coinsquare.io/register?r=BLOCKGEEKS)) 

**以太坊像比特币吗？有点儿像，但不完全一样。**

以太坊和[比特币](http://blockgeeks.com/guides/what-is-bitcoin-a-step-by-step-guide/)都是分布式公共区块链网络。比特币和以太坊有一些明显的技术差异，不过最值得注意的是它们的目的和能力有本质区别。比特币只提出了一种区块链应用，即点到点电子现金系统，可以实现线上比特币支付。比特币的区块链用来追踪电子货币（比特币）的所有权，而以太坊的区块链专注于执行任何去中心化的应用的代码。

在以太坊区块链中，矿工挖的不是比特币，而是以太币，一种给网络提供燃料的[加密货币](http://blockgeeks.com/guides/what-is-cryptocurrency-everything-you-need-to-know-ultimate-guide/)。以太币不仅是可交易的加密货币，应用的开发者还可以用以太币来支付交易费和以太坊网络的服务费。

* * *

![gavin-wood-smart-contracts](https://blockgeeks.com/wp-content/uploads/2016/10/Gavin-Wood.-Smart-Contracts-1-150x150.png) 

**_「比特币是最早也是最重要的货币；是基于区块链的一种应用。然而，它并不是唯一的应用。用过去发生过的类似场景下的例子来说吧，电子邮件是互联网的一种应用，而且显然促进了互联网的发展，但互联网不仅有这一种应用。」_**
[Dr Gavin Wood, 以太坊联合创始人](http://gavwood.com/)

## 什么是智能合约？

[智能合约](http://blockgeeks.com/guides/smart-contracts-the-blockchain-technology-that-will-replace-lawyers/)只是个惯用语，用来描述可以促进金钱、内容、财产、股份或任何有价物交易的计算机代码。运行在区块链上的智能合约就类似于自主操作的计算机程序，在满足特定条件时自动执行。因为智能合约运行在区块链上，它只会严格执行代码，没有审核、停机，欺诈的威胁，也不受第三方干扰。

![什么是智能合约？初学者指南](https://blockgeeks.com/wp-content/uploads/2016/10/infographics-02-1-1.jpg) 尽管所有的区块链都可以执行代码，不过能力大都有限。以太坊不同。以太坊允许开发者创建任何需要的操作，而不仅仅提供有限的操作。这就意味着开发者可以创建数千种不同的应用，完全超出我们之前所见。

* * *

![什么是区块链技术？大家都能看懂的教程](https://blockgeeks.com/wp-content/uploads/2016/10/dtapp-150x150.png) **_「（以太坊）区块链有一些超凡的能力。其中之一是可以构建智能合约。就跟字面意思差不多，智能合约可以自执行，自行打理好实施、管理、性能和支付等事情」_** [Don Tapscott](http://dontapscott.com/)

## 以太坊虚拟机

在以太坊之前，区块链应用只能执行有限的操作。比如比特币和其他[加密货币](https://blockgeeks.com/guides/what-is-cryptocurrency/)都只能用作点到点数字货币。

不久开发者就遇到了麻烦。要解决问题，一个方法是扩展比特币和其他应用提供的函数，既复杂又浪费时间。另一个方法就是开发全新的区块链应用和平台。以太坊的创造者 Vitalik Buterin 针对这个问题提出了新的解决方法。

* * *

![什么是区块链技术？大家都能看懂的教程](https://blockgeeks.com/wp-content/uploads/2016/10/Vitalik-Buterin-150x150.png) **_「我认为（那些比特币社区的人）处理这个问题的方法错了。我认为他们关注的是个别的应用；他们尝试用一种类似瑞士军刀的协议去分别支持每一种（场景）」_** Vitalik Buterin, 以太坊创造者

以太坊的核心创新是[以太坊虚拟机](https://blockgeeks.com/guides/how-to-learn-solidity/)（EVM），它是运行在以太坊网络上的图灵完备软件。如此，只要有足够的时间和内存，任何人都可以用任何语言运行任何程序。以太坊虚拟机让创建区块链程序变得前所未有的简单和高效。不用为每个新应用都创建一个原生的区块链了，以太坊使得在一个平台上开发数千种不同应用成为可能。

## 以太坊有什么用？

以太坊帮助开发者构建并部署[去中心化的应用](https://blockgeeks.com/guides/dapps-the-decentralized-future/)。去中心化应用或者说 Dapp 为其用户提供一些特定的功能。比如，比特币是一种 Dapp，为其用户提供了点对点电子货币系统，从而实现了在线比特币支付。因为去中心化应用由运行在区块链网络上的代码构成，它不受任何个人或中心化实体的控制。

![以太坊初学者手把手教程](https://blockgeeks.com/wp-content/uploads/2016/10/infographics2-02-1.png) 任何中心化的应用都可以通过以太坊来去中心。想想存在于数百种行业中的中介服务吧。从显而易见的银行贷款，到很少有人想到产权登记、投票系统和守规等等，都是中介服务。

以太坊还可以构建去中心化匿名组织（DAO）。DAO 是完全匿名，去中心化的组织，没有任何领导人。DAO 由代码运行在以太坊网络上的一组智能合约上。其代码设计之初就是为了取代传统组织的规范和架构，去除对人和中心化控制的依赖。DAO 由任何购买了 token 的人集体拥有，token 不代表股份和所有权，它表示贡献的多少，并赋予人们投票权。

* * *

![Stephen Tual, Slock.it 创始人](https://blockgeeks.com/wp-content/uploads/2016/10/Stephen-Tual-Slock.it-Founder-1-150x150.png) **_「DAO 由一个或多个智能合约组成，由一群志趣相投的人共同投资。DAO 的运作完全透明，不受任何人的干预，包括创始人。DAO 只要能承担其生存费用就能存在于网络上，为其客户提供服务。」_** Stephen Tual, [Slock.it](https://slock.it/) 创始人, 前 Ethereum CCO.

## 以太坊去中心化平台有什么好处

因为去中心化应用运行在区块链上，它们都受益于如下特性：

* **不变性** - 第三方无法对数据做出修改。
* **防篡改** - 应用运行在共识网络上，审查不复存在。
* **安全** - 没有中心点沦陷风险，由密码学确保安全，应用免受黑客攻击和欺诈威胁。
* **零停机时间** - 应用永远在线，永不关闭。

## 去中心化应用有哪些缺点？

当然除了这些优点，去中心化应用也不是没有缺点。因为[智能合约代码](https://blockgeeks.com/guides/how-to-learn-solidity/)是人写的，其质量与作者能力相关。代码的错误和疏忽可能招致意外的攻击。如果代码中的错误被坏人利用，除了达成共识并重写低层代码之外没有有效的办法阻止攻击。而修改低层代码的做法又违背了区块链的基本原则，不变性。同样的，任何由中央方发起的行动都会严重威胁去中心化应用的本质。

![以太坊初学者手把手教程](https://blockgeeks.com/wp-content/uploads/2016/10/infographics2-01-1.png)

## 想开发以太坊应用，如何访问以太坊？

有很多方法可以接入以太坊网络，最简单的方法是用原生的 Mist 浏览器。Mist 提供了易用的用户界面和数字钱包，用户可以交易并存放以太，也可以创建、管理、部署并使用智能合约。就如同 web 浏览器让用户可以访问互联网，Mist 提供了通往去中心化区块链应用的门户。

还有一个 MetaMask 浏览器插件，可以将谷歌的 Chrome 浏览器变身为以太坊浏览器。MetaMask 让任何人都可以用 web 浏览器就可以轻松运行或开发去中心化应用。尽管最开始 MetaMask 只支持 Chrome 浏览器，它最终会支持 Firefox 以及其他浏览器平台。

尽管仍在初期阶段，Mist、MetaMask 以及其他浏览器已经准备好让更多人接触到基于区块链的应用。即使是没有技术背景的人也有可能构建区块链应用。这是区块链技术的革命性的一步，很有可能使得去中心化应用成为主流。

## 区块链/以太坊课程：填补空缺

市场紧缺区块链开发者，一些大学和私人公司为此提供了不少[区块链相关的课程](https://blockgeeks.com)以满足市场需求。

根据比特币先驱 [Jered Kenna](https://news.bitcoin.com/former-tradehill-founder-dark-pool/) 的说法，有经验的区块链专家的年收入可超过 200,000 美元。

**「有区块链经验的人才供不应求」，Kenna 解释道。「有些人一天能拿 5 个 offer。」**

## 和 Blockgeeks 一起学习区块链开发

作为区块链社区的领先者，Blockgeeks 已经组织了[自己的课程](http://courses.blockgeeks.com/)帮助大家了解区块链技术并为工作市场上的不错的工作机会做好准备。这些课程的目标是帮助学生跟上区块链技术的脚步，同时让他们培养实际技能，为职业生涯提供帮助。

## 区块链基础：实用的学习路径

区块链认证硕士课程从基本原理开始，让学生打好基础，进而学习进阶知识，教会他们将区块链技术应用到实际情况。

学习到课程的最后，学生将会创建、连接并使用部署在 AWS 上的个人区块链。他们会学会如何使用 MultiChain Streams（多链流）并创建自己的区块链应用。

**这个课程专为以下人士准备：**

* 想在工作中使用区块链技术的员工
* 想在项目中使用区块链技术的学生
* 想更了解区块链行业的投资者
* 想在新业务中拥抱区块链技术的企业家
* 想使用区块链的产品经理
* 行业领导者的顾问

![以太坊初学者手把手教程](https://blockgeeks.com/wp-content/uploads/2016/10/infographics2-03-1.png)

## 现在以太坊上有什么应用？

以太坊平台已拥有众多应用，横跨多个服务领域及产业。但是开发者身处未知领域，所以很难预知哪个应用会成功哪个又会失败。下面列出一些出色的项目：

[Weifund](http://weifund.io/) 提供了基于智能合约的众筹开放平台。它让出资得以成为由合约背书的数字资产，可以在以太坊生态系统中使用、交易或出售。

[Uport](https://uport.me/#home) 为用户提供了安全且便捷的方法来全权控制自己的身份和个人信息。不再依赖会把个人信息出卖给第三方的政府机构，用户可以控制谁有权访问自己的数据和个人信息。

[BlockApps](http://blockapps.net/) 为企业构建、管理并部署区块链应用提供帮助。从概念证明到生成系统以及与传统系统的集成，Blockapps 提供了一系列工具来构建私有、半私有或公开的行业专用的区块链应用。

[Provenance](https://www.provenance.org/) 利用以太坊让不透明的供应链变得透明。通过跟踪原材料和产品的历史来构建一个开发、可访问的信息框架，让顾客可以在购买产品时有做够的信息来帮助决策。

[Augur](https://www.augur.net/) 是开源的预测市场平台，任何人都可以做出预测，而预测正确会得到奖励。通过交易虚拟股份，对真实世界的未来事件，比如谁会赢得下一场美国大选，进行预测。如果用户购买了预测正确的股份，会得到金钱奖励。

了解其他正在开发的以太坊应用，请点击[这里](http://dapps.ethercasts.com/)。

* * *

![caleb-chen: 什么是以太坊](https://blockgeeks.com/wp-content/uploads/2016/11/Caleb-Chen-150x150.png) **「以太坊是一个惊人的公共试验，展示了公共区块链上的智能合约的价值。这是突破式创新的结果亦是突破式创新的来源，自互联网早期以来鲜见。」 – **Caleb Chen [London Trust Media](http://londontrustmedia.com/)

## The DAO 攻击威胁了一切

还记得如何用以太坊构建去中心化匿名组织吗？2016 年发生了一起恶性事件。一个开发了名为 The DAO 的去中心化匿名组织项目的初创公司遭到黑客攻击。

The DAO 项目由初创公司 Slack.it 背后的团队打造。他们的目标是创建无人风投公司，投资者可以通过智能合约进行决策。The DAO 通过出售 Token 集资，最终从数千名出资人手中募集到了约 1.5 亿美元。

募资结束后不久，The DAO 被未知攻击者攻击，一次性被盗走价值约 5000 万美元的以太币。尽管被攻击的原因是 The DAO 自身的软件错误，与以太坊平台无关，以太坊的开发者和创始人仍然不得不为其擦屁股。

## 即将到来的以太坊分叉 （fork）

众多争论过后，[以太坊社区](http://blockgeeks.com/omg-ethereum-hard-forked/)投票决定通过硬分叉或者说修改代码，收回被盗的资金。硬分叉将被盗资金移入一个新的智能合约，资金的原所有者可以取回被盗的 token。事情就此变得复杂。这个决定充满争议，引发了激烈的辩论。

这里稍作解释。以太坊基于区块链技术，所有的交易都应该是不可逆且不可修改的。通过执行硬分叉并重写区块链运行的规则，以太坊树立了危险的先例，违反了区块链的本质。如果每次涉及一大笔钱或者有足够多的人受到负面影响的时候就修改区块链的话，区块链就丧失了其核心价值 ── 安全、匿名、防篡改且不可变。

尽管也有一些不那么激进的软分叉方案，以太坊社区及其创始人仍身处险境。如果他们不取回被盗的资金，人们会失去对以太坊的信心。另一方面，取回被盗资金所需的操作又违背了去中心化的核心原则并树立了危险的先例。

## 分叉的后果：以太坊被分裂

最后，以太坊社区大多数人投票选择硬分叉，取回了被盗的 The DAO 资金。但是不是所有人赞同这一决定。这导致了分裂，也就是有两个平行的区块链同时存在。对于那些哪怕有黑客攻击也强烈反对修改区块链的人来说，有[经典以太坊](https://blockgeeks.com/guides/what-is-ethereum-classic/)。而同意修改一小部分区块链代码并取回被盗资金的大多数则选择以太坊。

这两个区块链有相同的特性，而且在硬分叉之前的所有区块都相同。也就是说在硬分叉之前以太坊网络上的一切在[经典以太坊](https://blockgeeks.com/guides/what-is-ethereum-classic/)上都是有效的。而自硬分叉或修改代码之后，两个区块链各自独立运行。

## 超乎想象的以太坊的未来

尽管受到 The DAO 攻击的影响，以太坊仍在不断发展，有着光明的未来。通过提供友好的平台，让人们可以驾驭区块链技术的力量，以太坊正加速实现世界经济的去中心化。去中心化应用有可能深远影响数百个行业，包括金融、房地产、学术、保险、医疗和公共部门等等。

* * *

![https://consensys.net/team/](https://blockgeeks.com/wp-content/uploads/2016/10/Joseph-Lubin-1-150x150.png) _「如果你认为互联网影响了你的生活，以太坊也会对通信甚至整个信息产业产生同样广泛的影响。它将改变我们生活的方方面面。

_构建公共以太坊生态环境：随着未来两年公共以太坊的可扩展性和可配置的隐私/机密性的增长，消费者将会利用其区块链身份和访问点（uPort）接触到各种有趣的早期产品。_

_包括众筹平台（Weifund），团队管理工具（Boardroom），音乐/电影/艺术内容管理和使用平台（ujo），智慧市场（Gnosis）以及游戏（Virtue  Poker）」_

Joseph Lubin, [Consensys](https://consensys.net/team/) CEO

## 最重量级的公司会在私有区块链上展开业务

* **私有区块链：** 两年内，大公司都会在私有企业区块链上展开业务。每个公司的员工、顾客、供应商和服务提供商都可以通过高强度加密的交易（transation）来安全地访问私有区块链。
* **合作区块链：** 两年内，大多数公司开始自下而上构建合作区块链，与其生态系统中的少数对手方就少数用例展开合作，以共享真实数据（source-of-truth）基础设施，供应链或价值链。
* **公共区块链的商业用途：** 一些公司会根据自身场景使用公共区块链。这些场景用到的区块链组成部分与其购买或构建的基于以太坊的私有实现相同。

以太坊平台也助力于改变我们使用互联网的方式。去中心化应用正在推动从信息互联网（迅速看到，交换并交流信息）到价值互联网（直接交换价值，无需中间方）的根本改变。

> 随着行业对区块链平台的研究的不断深入，以太坊正在成为事实上的领导者。例如，几天前，摩根大通开源了 Quorum 平台，该平台由 Jeff Wilcke 及其团队利用以太坊 Go 语言客户端打造。其他几家主要银行也在使用以太坊，而微软将 Beltchley 平台作为其区块链基础组件。不管是公开还是私下的，行业持续为以太坊做出贡献，与我们以及其他人一道帮助尚处学步阶段的代码库走向成熟。请持续关注相关新闻。
> 
> 区块链的发展需要地球村的通力合作。实时网络和投身开源社区的开发者做出了重要的贡献。他们持续改进并加强以太坊平台，帮助以太坊更快响应行业对其主张的价值的需求。这些投入的时间和资源充分表明开发者对以太坊及其商业价值的信心，以及对以太坊能力的肯定。– Joseph Lubin, [Consensys](https://consensys.net/team/) CEO

尽管为时尚早，而且毫无疑问会有许多困难需要克服，以太坊看起来的确是一个转型（transformational）平台。还有众多激动人心的应用有待开发，我们只能无比期待以太坊无法想象的未来。

> 如果发现译文存在错误或其他需要改进的地方，欢迎到 [掘金翻译计划 — 区块链分舵](https://github.com/xitu/blockchain-miner) 对译文进行修改并 PR，也可获得相应奖励积分。文章开头的 **本文永久链接** 即为本文在 GitHub 上的 MarkDown 链接。


---

> [掘金翻译计划](https://github.com/xitu/gold-miner) 是一个翻译优质互联网技术文章的社区，文章来源为 [掘金](https://juejin.im) 上的英文分享文章。内容覆盖 [Android](https://github.com/xitu/gold-miner#android)、[iOS](https://github.com/xitu/gold-miner#ios)、[前端](https://github.com/xitu/gold-miner#前端)、[后端](https://github.com/xitu/gold-miner#后端)、[区块链](https://github.com/xitu/gold-miner#区块链)、[产品](https://github.com/xitu/gold-miner#产品)、[设计](https://github.com/xitu/gold-miner#设计)、[人工智能](https://github.com/xitu/gold-miner#人工智能)等领域，想要查看更多优质译文请持续关注 [掘金翻译计划](https://github.com/xitu/gold-miner)、[官方微博](http://weibo.com/juejinfanyi)、[知乎专栏](https://zhuanlan.zhihu.com/juejinfanyi)。
