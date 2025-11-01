 # 第3部分：模块化区块链、扩容、互操作与基础设施


## 子章节目录

- [3.1 模块化 vs 单体：执行 / 共识 / 数据可用性分离](./3.1_模块化架构与L1瓶颈.md)  
  单体链（执行+共识+DA 一体） vs 模块化（分层）；为什么要把执行层、共识层、数据可用性层拆开；结合 BTC / ETH 的演进来说明现实动机。

- [3.2 Layer 2 扩容与 Rollup](./3.2_Layer2_Rollup_Optimistic_ZK.md)  
  Optimistic Rollup vs ZK Rollup 的基本原理、挑战期 vs 有效性证明；Arbitrum、Optimism、zkSync、StarkNet 的差异；EIP-4844 / Blob 交易如何降低 L2 成本。

- [3.3 多链系统：平行链、子网、Zone](./3.3_多链架构_Polkadot_Avalanche_Cosmos.md)  
  Polkadot Parachain、Avalanche Subnet、Cosmos Zone 的安全共享模式，各自的信任假设是什么。

- [3.4 跨链互操作与跨链桥风险](./3.4_跨链与互操作性_LayerZero_IBC.md)  
  LayerZero 的全链通信思路、Cosmos IBC 模型、消息传递 vs 资产托管型桥、为什么跨链桥成了最大风险点之一。

- [3.5 节点、客户端与 P2P 网络](./3.5_节点客户端_P2P网络.md)  
  全节点 vs 轻节点；Geth / Prysm 等不同客户端的重要性；gossip 协议如何广播交易；节点服务商如何变成一门生意（RPC 服务等）。

- [3.6 去中心化预言机](./3.6_预言机与外部数据.md)  
  为什么智能合约需要“现实世界的价格和事实”；Chainlink 的机制、VRF（可验证随机数）；Pyth/Band 等不同喂价模式；预言机攻击与历史案例。

- [3.7 基础设施服务：RPC / 索引 / WalletConnect](./3.7_RPC_TheGraph_WalletConnect.md)  
  为什么 dApp 不直接跑自己的节点；Infura / Alchemy 这类 RPC 提供什么；The Graph 如何索引链上数据；WalletConnect 如何让钱包和应用说话。



