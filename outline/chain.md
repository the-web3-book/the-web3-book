# 作者信息

| 用户名 | 用户 ID | 头像 | 横幅 | The Web3 承诺 | 已购买人数 |
|--------|---------|------|------|------|--------|
| The Web3 | 0xtheweb3 | ![avatar](https://pbs.twimg.com/profile_images/1781583634979262466/j59yosRR_normal.jpg) | ![banner](https://pbs.twimg.com/profile_banners/1751058789783289856/1713538465) | 2025 年之前不对外开放 | 100 |

# 第四册 公链篇:《公链底层原理与源码解析》

本书以区块链技术的底层原理与公链生态系统为核心，全面解析各大主流公链的架构设计、核心机制以及源码实现，帮助读者深入理解区块链系统的技术细节和演进路径。

在第一章 “公链基础知识” 中，本书首先介绍区块链的基本概念、核心密码学算法、数据结构、共识机制、通信机制以及公链和联盟链的常见技术解决方案，为后续章节的深入解析奠定基础。

第二至第七章围绕主流公链 Bitcoin、Ethereum、Cosmos、Solana、Sui 和 HyperLedger Fabric 展开深入剖析。涵盖 Bitcoin 的 UTXO 模型、Taproot 技术、闪电网络及 BRC20 生态，Ethereum 的 EVM 机制、PoS 共识、信标链架构及 Layer2 扩展方案，Cosmos 的 IBC 跨链通信及模块化架构，Solana 和 Sui 的高性能区块链设计，以及 Fabric 作为联盟链的架构与共识机制。这些章节不仅包含公链的核心技术解析，还辅以关键源码解读，帮助读者掌握公链的实际实现。

第八章和第九章聚焦于区块链的 模块化演进与 Layer2 方案，分析 OpStack、ZkEVM、Arbitrum Nitro、Orbit 等 Layer2 解决方案的底层实现，同时深入解读各大 Layer2 官方桥接协议。

第十章 “数据可用层（DA）” 探讨 Celestia、EigenDA 以及 EIP-4844 方案，并提供 DA 相关的开发实战。

第十一章 “链抽象解决方案” 介绍 Rollup Services、Fraud Proof、ZK Prover & Verifier 以及 L2 桥接的抽象模型，并深入剖析 DappLink 在链抽象领域的技术实现。

本书适合对区块链底层技术感兴趣的开发者、研究人员及 Web3 从业者，旨在提供一套系统化的技术指南，助力读者掌握区块链公链架构的核心要点，并具备阅读和分析区块链源码的能力。

### 第 1 章：公链基础知识
  - #### 1.1 区块链的基本概念
  - #### 1.2 区块链的核心密码学算法
  - #### 1.3 区块链的基本数据结构
  - #### 1.4 区块链的共识机制
  - #### 1.5 区块链的通信机制
  - #### 1.6 区块链的组织形式
  - #### 1.7 公链常见的技术解决方案
  - #### 1.8 联盟链常见的技术解决方案
  - #### 1.9 技术创新公链项目生态
  - #### 1.10 本章小结

### 第 2 章：Bitcoin 原理及源码解读
  - #### 2.1 Bitcoin 基本信息
  - #### 2.2 Bitcoin 数据组织结构源码解读
    - 链的组织结构
    - 区块组织形式
  - #### 2.2 Bitcoin 共识协议与源码解读
  - #### 2.3 Bitcoin 挖矿与挖矿难度
  - #### 2.4 Bitcoin UTXO 模型与源码解读
  - #### 2.5 Bitcoin 交易结构
  - #### 2.6 Bitcoin 脚本编程
  - #### 2.7 Bitcoin Taproot 底层实现机制与源码解析
  - #### 2.8 Bitcoin 的匿名性和地址分析策略
  - #### 2.9 闪电网络，RGB 与 RGB++ 协议
  - #### 2.10 BRC20 协议
  - #### 2.11 Bitcoin 生态项目分析
  - #### 2.12 本章小结

### 第 3 章：Ethereum 原理及源码解读
  - #### 3.1 以太坊简介
  - #### 3.2 以太坊的数据组织形式底层实现与源码解析
    - 🛞交易树
    - 🛞收据树
    - 🛞状态树
  - #### 3.3 以太坊的历史版本
  - #### 3.4 以太坊的共识算法细节实现与源码解析
    - 🛞POW
    - 🛞POS
  - #### 3.5 以太坊 EVM 底层实现与源码解析
  - #### 3.6 以太坊信标链底层实现与源码解析
  - #### 3.7 以太坊执行层和共识层之间的通信方式
  - #### 3.8 以太坊交易执行流程源码解析
  - #### 3.9 以太坊 json-rpc 接口部分源码解析
  - #### 3.10 不同类型的以太坊节点详解解说
  - #### 3.11 以太坊光速链展望
  - #### 3.12 以太坊的生态系统项目分析
  - #### 3.13 本章小结

### 第 4 章：Cosmos 原理及源码解读
  - #### 4.1 Cosmos 的基本概念讲解
  - #### 4.2 cometBFT 详细讲解
  - #### 4.3 基于 cometBFT 写一个能够落块的简版区块系统
  - #### 4.4 Cosmos SDK 详细讲解
  - #### 4.5 分析 Cosmos 模块的实现
  - #### 4.6 在 Cosmos SDK 开发一个板块
  - #### 4.7 Cosmos 跨链间通信
  - #### 4.8 Cosmos 链间安全
  - #### 4.9 Cosmos Wasm 合约开发实战
  - #### 4.10 基于 Cosmos 开发一条应用链
  - #### 4.11 BTC 赛道知名项目 Babylon
    - Babylon--->链代码分析
    - BtcStaker 源码解读
    - Vigilante: Btc 节点监控 monitor, reporter, sumitter 等板块的功能
    - Babylon Rust 合约代码讲解与Wasm 合约的部署
  - #### 4.12 本章小结

### 第 5 章：Solana 原理及源码解读
  - #### 5.1 深入剖析 Solana 底层实现机制
  - #### 5.2 Solana 项目源码解读
  - #### 5.3 如何基于 Solana 开发自己的 Layer2
  - #### 5.4 在 Solana 上开发一个 DA(数据可用层) 项目
  - #### 5.5 本章小结

### 第 6 章：Sui 原理及源码解读
  - #### 6.1 深入剖析 Sui 底层实现机制
  - #### 6.2 Sui 项目源码解读
  - #### 6.3 如何基于 Sui 开发自己的 Layer2
  - #### 6.4 在 Sui 上开发一个 DA(数据可用层) 项目
  - #### 6.5 本章小结

### 第 7 章：HyperLedger Fabric 源码解读
  - #### 7.1 联盟链简介
  - #### 7.2 知名联盟链项目介绍
  - #### 7.3 HyperLedger Fabric 版本发展过程介绍
  - #### 7.4 HyperLedger Fabric 0.6 版本 PBFT 共识算法与源码解读
  - #### 7.5 HyperLedger Fabric kafka + zookeeper 共识底层实现与源码解读
  - #### 7.6 PKI 公钥基础设施与 HyperLedger Fabric CA 模块的源码解读
  - #### 7.7 HyperLedger Fabric 账本与 ChainCode 底层实现与源码解读
  - #### 7.8 HyperLedger Fabric 通信过程与源码解读
  - #### 7.9 本章小结

### 第 8 章：模块化区块链演变过程
  - #### 8.1 模块化区块历史渊源
  - #### 8.2 Cosmos 生态的模块化区块链设想
  - #### 8.3 模块化区块链在 Ethereum 生态实施过程
  - #### 8.4 几个顶级的模块化区块链项目简介
  - #### 8.5 本章小结

### 第 9 章：Layer2 底层实现机制以及代表项目源码解读
  - #### 9.1 什么是 Layer2
  - #### 9.2 Layer2 相关概念介绍
  - #### 9.3 OpStack 项目源码解读
    - 🛞OVM
    - 🛞OpStack
    - 🛞OpStack SuperChain 构想与未来
  - #### 9.4 ZkEvm 板块 Polygon ZkEvm
    - 零知识算法的普及
    - 🛞Polygon zkEvm 的 zkevm-node 源码解读
    - 🛞Polygon zkEvm 的 zkevm-prover 源码讲解
    - 🛞Polygon zkEvm 的 zkevm-prover 的 zk snark 和 stark 怎么构建分析
  - #### 9.5 Arbitrum Nitro 和 Orbit 项目源码解读
    - 🛞Arbitrum Nitro 的项目架构分析
    - 🛞Arbitrum Nitro 源码解读
    - 🛞深入理解 Arbi Gas Oracle 的细节实现
    - 🛞基于 Orbit 构建 Layer3 应用链实战
    - 🛞Orbit 构想与未来
  - #### 9.6  知名 Layer2 的官方桥源码解读
    - 🛞ZkSync Era 官方桥源码解读
    - 🛞Linea 官方桥源码解读
    - 🛞Scroll 官方桥源码解读
    - 🛞StarkNet 官方桥源码解读
  - #### 9.7 基于 Babylon 开发一个通用型 Layer2 FP
    - 🛞Rust 合约代码编写
    - 🛞Fp 实现
    - 🛞去中心化 Relayer 实现
  - #### 9.8 本章小结

### 第 10 章：数据可用层底层原理以及代表项目源码解读
  - #### 10.1 数据可用层基本概念
  - #### 10.2 数据可用层知名项目介绍
  - #### 10.3  EigenDA 项目源码解读
  - #### 10.4 Celestia 项目源码解读
  - #### 10.5 EIP4844 底层实现与源码解读
  - #### 10.6 OpStack Rollup Celestia 和 EigenDA 开发实战
  - #### 10.7 本章小结

### 第 11 章：链抽象解决方案
  - #### 11.1 链抽象解决方案简介
  - #### 11.2 RollUp Services 抽象
  - #### 11.3 Fraud Proof 抽象
  - #### 11.4 Zk Prover 和 Zk Verifer 抽象
  - #### 11.5 L2 和桥快速验证网络抽象
  - #### 11.6 DappLink 链抽象解决方案底层实现与源码解析
  - #### 11.7 本章小结

[查看推文](https://x.com/0xtheweb3/status/1885864350134796538)
