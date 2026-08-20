# 验合约卡 — 概述

## 一句话介绍

在 BNB Chain 上，用一张「验合约卡」一眼看清合约是否已验证、来源是否可信、有没有明显风险。

## 问题与目标

- 痛点：用户只看到一串合约地址，无法快速判断验证状态与风险。
- 目标用户：准备交互 DApp / 代币合约的普通用户与 builder。
- 为什么选 BNB Chain：BSC 生态合约多、仿盘与未验证合约常见，验真需求强。

## 核心功能

1. 合约地址 → 验合约卡（验证状态、元数据、风险标签）
2. 可分享卡片链接 / 图片
3. AI 辅助一句话解读（可选）

## 技术栈（待定）

| 层 | 选型 |
| --- | --- |
| 合约 | Solidity（如需链上存证 / 徽章） |
| 链 | BSC / opBNB |
| 前端 | 待定 |
| 数据 | BscScan / 节点 RPC |
| AI | 可选：摘要解读 |

## 社区

- Discord：https://discord.com/invite/bnbchain
- Hackathon：https://www.bnbchain.org/en/hackathons/bnb-ai-hack

## 路线图

- [x] 公开仓库 + 一句话定位
- [ ] MVP：地址查询 + 卡片页
- [ ] Testnet / 演示
- [ ] 黑客松正式提交
