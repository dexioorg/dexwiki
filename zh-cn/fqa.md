# 使用什么 sdk

dexchain 高度兼容 ethereum，可以使用 ethereum 的 sdk，例如 web3js， web3j 等。

# 使用什么编译器

可以使用网页端[remix](https://remix.ethereum.org)、或者命令行的 [solidity](https://solidity.readthedocs.io/) 编译器进行编译。

# 是否支持EVM？

完全支持以太坊EVM，对以太坊开发者完全友好。

# 地址生成规则是否一致？
完全一致。

# 有类似swap的Dex合约提供换币吗？

目前官方Dex还没有，鼓励社区开发者提供。

# 是否有跨链桥接（bridge）资产到Dexchain？

目前还没有官方的去中心化桥，鼓励社区开发者提供。
对于开发者资产，我们提供了资产承兑方案，帮组开发者快速资产上链。

见[跨链](./chainbridge.md)

# 如何获取测试币？

官方测试币水龙头地址，可以申请测试网DEX。

https://faucet.testnet.dex.io/

# 合约部署有什么要注意的吗？

RPC接口兼容以太坊，可直接使用web3.js，对以太坊开发者完全友好。

# 区块确认时间是怎么样的？

6秒一个区块，10个区块确认。
