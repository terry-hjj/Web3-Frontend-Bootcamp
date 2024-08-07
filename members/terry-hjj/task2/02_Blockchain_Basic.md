# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [ ] 一个私钥对应一个地址
- [x] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [ ] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [x] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
区块链的网络是由许多的节点联通而组成的一个分布式网络, 并无处于中心位置的权威节点, 所有节点都是平等的.  
它们通过这个分布式网络传播和同步区块信息, 并遵守该网络上所预设的共识机制, 以保证所有节点对以区块连接而成的这个链数据集合达成一致.
```

## [简答题] 智能合约是什么，有何作用？

```
智能合约是一段程序,被其发布者部署到区块链上,提供给使用者调用.  
程序接到调用后会按照其预先写好的逻辑自动智能地运行, 还可以保存有用的数据到链上, 最终使其达成各种类型的交易.
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM是一个可以执行字节码的虚拟环境, 它运行于每个节点上, 并执行符合其规范的智能合约字节码(大多是从solidity源码编译后得到), 它完成对区块信息进行验证或者打包的过程.  
因其规范严格确定, 所以每个节点上的EVM执行或验证同样的交易或者智能合约的函数调用时,总能得到完全相同的结果, 这保证了整个区块链的一致性.
```

## [分析题] 你对去中心化的理解

```
通过将数据以去中心化的方式存储, 减少了中心权威对数据进行不当处置的可能性, 且链上数据都是通过事先确定的共识机制产生的,而不是权威中心的单方面规定, 对所有用户都是公平的.  
此外, 每一节点均保存了数据, 即使某一两个节点出现故障或者发生篡改, 仍不能影响到整个网络, 使得整个区块链的健壮性大大提高.
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链上的信息是分布式存储在每一个节点, 传统数据库则存放在中心机构的一台或几台服务器上, 一旦这家机构或这几台服务器出问题, 则会影响到整个网络, 而区块链则不会出现这种情况.  
但是, 区块链的数据存储和交易执行则比传统数据库要低效一些. 因为其必须考虑在所有节点上保持一致的执行过程和相同的数据, 因此需要共识机制,加密算法等等来加以约束.  
所以, 可以考虑将可以公开的关键和重要信息保存到链上, 而将不宜公开的辅助的和次要的信息保存到传统数据库中, 以此来达到双方面的平衡.
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.
