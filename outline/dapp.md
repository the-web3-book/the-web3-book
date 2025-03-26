# 第三册 链上开发篇《智能合约应用开发实战》

## 一.前言
随着区块链技术的不断发展，Web3 生态系统正逐步改变互联网的底层逻辑，推动去中心化应用（DApp）、智能合约、去中心化金融（DeFi）、非同质化代币（NFT）、可编程资产以及跨链互操作性等领域的创新。无论是 Ethereum 生态、Solana 生态、Sui 生态，还是其他公链技术，各种新型智能合约编程语言、开发工具、基础设施与协议正在快速演进，为开发者带来了前所未有的机会与挑战。

本书致力于为 Web3 开发者提供一套完整的 智能合约开发与区块链应用实践指南，涵盖 Solidity、Rust、Move 等主流智能合约开发语言，结合 Ethereum、Solana、Sui 及 Cosmos Wasm 生态进行深入解析，并辅以丰富的实战项目，帮助读者从基础语法入门，到掌握跨链桥、DeFi、LSD、Fraud Proof、zk Verifier 等前沿应用的开发技能。

## 二.本书特点
1 多链支持，生态全面
以 Ethereum (EVM) 为核心，详细讲解 Solidity 编程、合约升级、DeFi、NFT、跨链等应用。
介绍 Solana (SVM) 生态的 Rust 智能合约开发，包括 Solana Program Library（SPL）标准、JSON-RPC 交互、去中心化应用开发等。
深入 Sui (MoveVM) 生态，剖析 Move 智能合约机制、Sui Coin、NFT 发行、闪电贷等场景。
涉及 Cosmos Wasm 合约 及其他区块链基础设施开发。

2 从基础到进阶，全链路学习
适合初学者：从 Solidity、Rust、Move 语言的基本语法、智能合约编写、常见设计模式入手，构建扎实的基础。
适合 进阶开发者：深入 ABI 编解码、EVM 内存布局、OpStack、Arbitrum Fraud Proof、zkVerifier 解析等，提升智能合约安全性与性能优化能力。
适合 实战开发者：涵盖 DeFi、NFT、RWA、LSD、跨链桥等多个完整实战项目，助力 Web3 产品落地。
3 强实践导向，完整项目开发
通过 Step-by-Step 的方式，带领读者构建自己的 NFT 平台、跨链桥、Meme 币发行平台、再质押协议、Fraud Proof 验证器等。
结合 OpenZeppelin（OZ） 代码库、Foundry、Hardhat、TheGraph、Golang 监听合约事件等工具，构建生产级 Web3 DApp。

3 适合读者
Web3 开发者：希望学习或提升 Solidity、Rust、Move 编程能力，并掌握智能合约安全、性能优化、项目开发方法。
区块链产品经理：希望深入理解 Web3 产品底层逻辑、代币经济学及区块链生态系统，形成正确的产品思维。
安全研究员 & 区块链架构师：希望掌握智能合约漏洞分析、跨链桥安全机制、Fraud Proof 与 zk Verifier 技术原理。
投资者 & 创业者：希望了解 Web3 生态的技术发展趋势，并为项目开发提供技术支持。

4 本书共 17 章
从基础到进阶，涵盖 Ethereum、Solana、Sui 生态 的智能合约开发与实战：
第 1-2 章：Solidity 基础与进阶编程，包括智能合约开发、ABI 编解码、OZ 代码库、合约升级、内联汇编等。
第 3 章：Solidity 小实战，如发行代币、NFT 平台开发、TheGraph 事件监听、Golang 监听合约事件等。
第 4-5 章：Rust 基础与进阶编程，涵盖 Rust 语言特性、内存管理、网络编程、并发编程等。
第 6 章：Rust 小实战，如 gRPC 服务、Solana JSON-RPC 开发、MPC gg20 托管钱包等。
第 7-9 章：Move 语言开发，包括 Move 基础、进阶、Sui 生态实战，如 NFT 发行、Uniswap V1/V2 开发等。
第 10-16 章：Web3 生态应用实战，涵盖 Meme 代币发行、NFT & RWA、DeFi、LSD/LST/LSP、跨链桥、签名验证。
第 17 章：Fraud Proof 和 zk Verifier 开发，解析 OpStack、Arbitrum Fraud Proof、Polygon zkEVM、Scroll zkEVM，并进行实战演练。

三. 本书大纲

第 1 章: Solidity 基础编程
1.1 智能合约简介
1.2 合约文件结构
1.3 合约的定义
1.4 数据类型
1.5 循环分支控制
1.6 函数与函数选择器
1.7 事件
1.8 继承
1.9 抽象合约与接口
1.10 合约的 lib 库
1.11 异常处理
1.12 变量作用域和数据存储
1.13 Solidity 内存布局
1.14 本章小结

第 2 章: Solidity 进阶编程
2.1 call, delegatecall, staticcall 和 multicall 基本使用
2.2 跨合约调用方式
2.3 常见的address(this)，tx.origin 和 msg.sender 语句解释
2.4 create 和 create2 底层原理与实现机制
2.5 合约自毁
2.6 Solidity 内联汇编
2.7 合约的升级方式
2.8 OZ 代码库讲解
2.9 ABI 编解码和生成 bindings
2.10 本章小结

第 3 章: Solidity 小实战
3.1  Ethereum 介绍
3.2 以太坊的交易类型
3.3 深入理解 EVM 字节码
3.4 智能合约开发工具
深入理解 hardhat 的使用
深入理解 foundry 的使用
常用的 RPC 节点服务商
3.5 发行自己的第一个代币 3.6 使用智能合约编写 Merkle Tree 3.7 链上链下结合的去中心化随机数 3.8 代币锁和时间锁 3.9 Hash 数字游戏 3.10 开发自己的 NFT 平台
3.11 基于 TheGraph 开发合约事件监听器
3.12 Golang 监听合约事件项目实战

第 4 章: Rust 基础编程
4.1 Rust介绍
4.2 环境搭建
4.3 Hello, World 和 Hello, Cargo
4.4 编写⼀个一元夺宝的游戏
4.5 Rust 数据类型
4.6 程序控制流
4.7 函数与函数调⽤
4.8 程序的基本执⾏流程
4.9 Rust 的内存管理
4.10 Rust 指针类型
4.11 本章小结

第 5 章: Rust 进阶编程
5.1 Rust 所有权
5.2 引⽤与借⽤
5.3 结构体与结构体的使用
5.4 定义与使⽤枚举
5.5 match 控制流运算符
5.6 Option 枚举及其常⽤⽅法
5.7 Vector 动态数组
5.8 String 字符串
5.9 Map 与 HashMap
5.10 泛型数据类型
5.11 特征与约束
5.12 Rust 的生命周期
5.13 Rust 错误处理
5.14 项目管理
5.15 文档与测试
5.16 智能指针
5.17 闭包与迭代器
5.18 Rust 网络编程
5.19 Rust 并发编程
5.20 Rust 宏函数
5.21 本章小结

第 6 章: Rust 小实战
6.1 Rust Orm 编程实战
6.2 几个Web 框架介绍
🥳poem
🥳hyper
🥳actix-web
6.3 基于 Web 框架的项目目实战
6.4 实现 grpc server 和 client
6.5 使用 Rust 开发 solana json-rpc 实战
6.6 MPC gg20 代码逻辑讲解
6.7 基于 MPC gg20 开发 Solana 托管钱包项目
6.8 Soalan 项目介绍
6.9  Soalan 发行自己的第一个代币
6.10 Solana 上 NFT 项目开发实战
6.11 Solana 去中心化随机数开发实战
6.12 Solana 合约事件监听开发实战
6.13 本章小结

第 7 章: Move 基础编程
7.1 Move 和智能合约简介
7.2 Move 基本数据类型
7.3 Move ⽅法
7.4 Move 条件控制
7.5 Move 模块
7.6 事件和错误处理
7.7 结构体
7.8 Object 介绍
7.9 Object 所有权

第 8 章: Move 进阶编程
8.1 Abilities
8.2 泛型
8.3 设计模式
8.4 闪电贷实例开发
8.5 framework介绍和Move std
8.6 Sui Coin/FT 标准
8.7 NFT 标准
8.8 Math
8.9 随机数与时间戳
8.10 集合
8.11 Sui 上常用的 Move Lib 库

第 9 章: Move 小实战
9.1 ⽐⼤⼩游戏
9.2 Sui 的 coin 协议详解
9.3 Move 发行自己的第一个代币
9.4  Move 发行自己的 NFT 平台
9.5 从 0 开始开发一个 Uniswap V1 项目
9.6 从 0 开始开发一个 Uniswap v2 项目
9.7 Move 合约事件监听开发实战
9.8 本章小结

第 10 章: Meme 代币发行平台实战(Ethereum, Solana 和 Sui 生态)
10.1 SVM 生态 Meme 币发行平台开发实战
10.2 MoveVM 生态 Meme 币发行平台开发实战
10.3 EVM 生态 Meme 币发行平台开发实战
10.4 本章小结

第 11 章: NFT 和 RWA 项目开发实战(Ethereum, Solana 和 Sui 生态)
11.1 SVM 生态 RWA 平台开发实战
11.2 MoveVM 生态 RWA 平台开发实战
11.3 EVM 生态 RWA 平台开发实战
11.4 本章小结

第 12 章: Defi 项目开发实战(Ethereum, Solana 和 Sui 生态)
12.1 SVM 生态质押借贷平台开发实战
12.2 SVM 生态Dex 平台开发实战
12.3 MoveVM 生态质押借贷平台开发实战
12.4 MoveVM 生态 Dex 平台开发实战
12.5 EVM 生态质押借贷平台开发实战
12.6 EVM 生态 Dex 平台开发实战
12.7 本章小结

第 13 章:  LSD/LST/LSP 项目开发实战(Ethereum 生态)
13.1 SVM 生态 LSD 平台开发实战
13.2 MoveVM 生态 LSD 平台开发实战
13.3 EVM 生态 LSD 平台开发实战
13.4 本章小结

第 14 章: 再质押模型开发实战(Ethereum, Solana 和 Sui 生态)
14.1 SVM 生态再质押模型开发实战
14.2 MoveVM 生态再质押模型开发实战
14.3 EVM 生态再质押模型开发实战
14.4 本章小结

第 15 章: 跨链桥开发实战 (Ethereum, Solana 和 Sui 生态)
15.1 SVM 生态跨链桥开发实战
15.2 MoveVM 生态跨链桥开发实战
15.3 EVM 生态再质跨链桥开发实战
15.4 EVM  L2 官方桥源码解读
15.5 本章小结

第 16 章: 签名与验证签名开发实战 (Ethereum, Solana, Sui 和 Cosmos wasm 合约)
16.1 SVM 生态签名与验证签名开发实战
16.2 MoveVM 生态签名与验证签名开发实战
16.3 EVM 生态再质签名与验证签名开发实战
16.4 本章小结

第 17 章: fraud proof 和 zk verifier 开发实战(Ethereum 和 Solana生态)
17.1 EVM 生态 OP Rollup fraud proof 源码解读
🥳OpStack
🥳Arbitrum
17.2 EVM 生态 zk verifier 源码解读
🥳Polygon ZkEvm
🥳Scroll ZkEVM
17.3 SVM 生态 fraud proof/zk verifier开发实战
17.4 本章小结
