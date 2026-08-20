# 验合约卡

> **一句话：** 在 BNB Chain 上，用一张「验合约卡」一眼看清合约是否已验证、来源是否可信、有没有明显风险。

BNB Hack: Online Edition 参赛项目 · 赛道倾向 **AI / DeSoc（安全与信任）**  
仓库：https://github.com/b123jery/bnb-hack-online

## 为什么做

普通用户面对合约地址时，很难判断：有没有开源验证？是不是仿盘？权限是否危险？  
验合约卡把「验源 + 关键摘要 + 风险提示」压成一张可分享的卡片，降低上链交互前的信任成本。

## 计划能力（MVP）

1. 输入 BSC / opBNB 合约地址 → 生成验合约卡  
2. 展示：验证状态、编译器、创建者线索、基础风险标签  
3. （可选）AI 一句话解读：这份合约「适合普通人怎么理解」

## 仓库结构

```
.
├── README.md          # 项目一句话 + 说明（本文件）
├── docs/              # 设计与提交材料
├── contracts/         # 智能合约
├── apps/              # 前端 / API / Agent
└── .env.example
```

## 快速开始

```bash
npm install
npm run dev
```

## 社区与黑客松

- 黑客松主页：[BNB Hack: Online Edition](https://www.bnbchain.org/en/hackathons/bnb-ai-hack)
- **BNB Chain Discord（请加入）：** https://discord.com/invite/bnbchain  
  进服后找黑客松 / builder 支持频道，发项目一句话方便找队友与答疑。

## 提交清单

- [x] 公开仓库写清「验合约卡」一句话
- [ ] Demo / 在线预览
- [ ] 技术架构说明（见 `docs/OVERVIEW.md`）
- [ ] 合约地址（testnet / mainnet）
- [ ] 发推 tag @BNBChain #BNBHack（按官方提交要求）

## License

MIT
