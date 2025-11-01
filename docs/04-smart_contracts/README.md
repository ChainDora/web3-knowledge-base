# 第4部分：智能合约与开发实践


## 子章节目录

- [4.0 EIP/ERC 标准体系总览](./4.0_EIP_ERC_标准体系.md)  
  EIP 的提案流程、ERC 是什么、哪些标准是“基础设施级别的”（ERC-20、ERC-721A、ERC-3643 等）。

- [4.1 EVM 架构与 Opcode](./4.1_EVM_架构与Opcodes.md)  
  EVM 是什么样的虚拟机？Stack / Memory / Storage、Gas 消耗、合约调用流程。

- [4.2 Solidity 语言与常用标准实现](./4.2_Solidity语法与标准合约.md)  
  Solidity 的核心语法（状态变量、函数、事件、修饰器、继承）；ERC-20 / ERC-721A / ERC-3643（RWA合规标准）的基本实现思路；Vyper vs Solidity。

- [4.3 开发工具链与部署实践](./4.3_开发工具链_Remix_Hardhat_Foundry.md)  
  Remix / Hardhat / Foundry 的对比，如何编译、测试、部署；如何配置 RPC、私钥、网络。

- [4.4 合约升级、代理模式与权限控制](./4.4_合约升级_代理模式_权限.md)  
  UUPS、透明代理、可升级合约的风险；为什么要加时间锁、多签、延迟升级；谁有权改合约？

- [4.5 测试与集成](./4.5_测试框架_wagmi_前端集成.md)  
  Hardhat / Foundry 测试；如何在前端用 ethers.js / wagmi 调用合约；本地/测试网/主网的差异。

- [4.6 非 EVM 生态的合约开发](./4.6_非EVM合约_Solana_Sui_Move_Rust.md)  
  Solana 的并行账户模型、Sui / Move 的资源语义、Rust 合约的风格；为什么有些人说“Solana 开发像写高性能后端”。

- [4.7 核心DeFi协议源码导读](./4.7_DeFi协议源码导读_Uniswap_闪电贷.md)  
  Uniswap V2/V3 核心逻辑、恒定乘积做市、集中流动性、闪电贷的可组合性；预言机是如何嵌进来维持价格安全的。

- [4.8 安全审计与常见漏洞](./4.8_安全审计与常见漏洞.md)  
  重入、整数溢出、签名重放、预言机操纵、闪电贷攻击；静态分析工具（如 Slither）；怎么看审计报告，不被忽悠。


