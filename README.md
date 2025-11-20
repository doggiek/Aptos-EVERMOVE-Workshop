# Aptos EVERMOVE Workshop · Hangzhou 2025

# 背景
## 活动详情

🔗：[Aptos EVERMOVE 杭州站 Mini Hackson](https://mp.weixin.qq.com/s/jEB_PfDk1M3kQK-dPxk4KA)
- 名称：Aptos EVERMOVE 杭州站 Mini Hackson
- 时间：2025.11.15
- 概况：Aptos生态 + Move语言

## 仓库概览

本仓库聚合了 Mini Hackson 的三个示例项目，全部以 Git submodule 的形式管理，便于独立开发、版本追踪与复用。克隆仓库后请执行：

```bash
git submodule update --init --recursive
```

即可拉取所有子模块代码。

### 子模块列表

1. `helloworld`：Aptos HelloWorld 模块示例。
2. `NFT`：基于 Aptos Token Objects 的 NFT 示例。
3. `cutemarket`：Move + SDK 应用（需要提交），原始 Aptos 线下活动代码库：`git@github.com:tu95/Aptos_Hangzhou_2025_cuteMarket.git`，本代码库为修改后的版本。

> 所有子模块目录均位于仓库根目录下，便于在本地统一编译、部署与演示。


# 活动介绍（原始）

## 加入我们

项目提交仓库：https://github.com/ALCOVE-LAB/Aptos-EVERMOVE-Hackathon-Kunshan-2025

### alcove

alcove 致力于支持富有才华的开发者使用 Move 语言构建下一代 Web3 应用。在 alcove，我们相信一步创新，一步成就。Make Your Move。

- 推特：https://x.com/alcove_pro

### Movemaker

Movemaker 是由 Aptos 基金会授权，经 Ankaa 和 BlockBooster 联合发起的官方社区组织，专注于推动 Aptos 华语区生态的建设与发展。作为 Aptos 在华语区的官方代表，Movemaker 获得了来自 Aptos 基金会百万美元级的资金和资源支持，致力于连接开发者、用户、资本与生态合作伙伴，打造多元、开放、繁荣的 Aptos 生态系统。

- 官网：https://movemaker.xyz
- 推特：https://x.com/MovemakerCN

### Aptos

Aptos 是采用 Move 语言的 Layer 1 区块链，致力于提供可扩展性、可靠性、安全性与可用性。Move 语言专为安全智能合约而设计，其最大的优势正是安全性。

- 推特：https://x.com/Aptos

## 挑战任务

我们将原有的单一提交流程拆解为三个循序渐进的挑战，帮助你从基础到应用全面理解 Aptos 生态。前两个挑战以练习为主，无需向官方仓库提交成果；第三个挑战将产生正式提交。

1. **Hello Aptos Move（无需提交）**  
   使用 Aptos Move 在 testnet 上部署一个基础的 HelloWorld 模块，并通过 Aptos CLI 进行读写交互。请确保能够展示状态数据的读取与更新。
   
   **代码: ** https://github.com/ALCOVE-LAB/Aptos-EVERMOVE-Workshop-HangZhou-2025-HelloWorld

2. **NFT 标准实践（无需提交）**  
   基于 Aptos NFT 标准发布一个 NFT 系列，完成 // TODO 的几个填空，编译成功后在尝试 mint 一个 NFT 。该挑战主要帮助你熟悉标准资产发行流程。
   
   **代码：** https://github.com/ALCOVE-LAB/Aptos-EVERMOVE-Workshop-HangZhou-2025-NFT
3. **Move + SDK 应用（需要提交）**  
   使用 Aptos Move 搭配 Aptos TS SDK 或 Go SDK 构建一个可交互的应用（示例：To-do List、公开留言板、NFT 展示墙等）。该挑战需要同时准备 Move 合约、链上交互逻辑与最小可用的前端/接口。

## 提交方式（仅针对挑战 3）

1. Fork 官方仓库：https://github.com/ALCOVE-LAB/Aptos-EVERMOVE-Hackathon-Kunshan-2025  
2. 克隆你的 Fork：`git clone https://github.com/YOUR_USERNAME/Aptos-EVERMOVE-Hackathon-Kunshan-2025.git`  
3. 在仓库根目录创建 `ID-Name` 文件夹，将挑战 3 的所有交付内容（代码、README、演示资料、demo 链接等）放入该文件夹中，勿修改其他目录。  
4. 提交并推送：`git add .` → `git commit -m "项目名称 结果提交"` → `git push`  
5. 创建 Pull Request，命名为 “项目名称”，并在说明中提供：  
   - GitHub 仓库链接（必填）  
   - 其他支持材料（可选，如演示视频/截图/PPT）  

## 开发与部署提示

- 所有合约须部署在 Aptos Testnet（ https://aptos.dev ）, 可在官网领取测试币或在社群提交地址申请测试币，用于部署与调用。  
- 推荐通过 Aptos CLI 管理账户、发布模块与执行交易。  
- 需要使用 Aptos Move 编写至少一个智能合约；如集成前端，请确保能够调用合约的主要接口。  
- 如果你在开发过程中使用 AI 辅助，请提示模型关键词 “Aptos Move”，确保输出与生态保持高度相关。  
- 项目需在本次活动期间开发、可运行，并避免任何恶意或违规内容。  

## Demo 展示

如果你完成了可运行的 demo，欢迎在线下 Demo 展示环节进行分享。展示时建议准备：  

- 合约与前端的实时交互演示 
- 架构与技术栈说明 (可选）)
- 亮点与未来规划（可选）  

期待在 Hangzhou 2025 与大家一起探索 Move 语言的无限可能！
