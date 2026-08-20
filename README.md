# EscrowDesk

> **一句话：** 代客部署/铸币这单生意，把微信口头单变成 BSC 上的托管验收：客户锁服务费，开发者交合约与材料，条件满足或确认后放款。

BNB Hack · **DeSoc**（验收说明可走 AI）  
仓库：https://github.com/b123jery/bnb-hack-online

## 问题

代客部署/铸币多在微信里成交，**钱和活对不上**：客户怕付了没交付，开发者怕做了不结款。

## 方案

EscrowDesk 把交付放到 BSC 上：

1. 客户锁定服务费，写明验收条件  
2. 开发者提交合约地址、验证链接、说明书哈希  
3. 条件满足或客户确认后放款  

## 硬规则（比赛版）

| 情形 | 结果 |
| --- | --- |
| 开发者未在期限内交付 | 自动退款给客户 |
| 已交付后 72 小时客户不操作 | 视为验收并放款 |
| 客户在窗口内拒绝 | 进入双方各押一笔的争议，由指定仲裁地址裁定 |

## 当前状态

**设计中，尚未部署。**

## 仓库结构

```
.
├── README.md          # 项目说明（本文件）
├── docs/              # 设计与提交材料
├── contracts/         # 托管 / 验收合约
├── apps/              # 前端 / API
└── .env.example
```

## 社区

- 黑客松：[BNB Hack: Online Edition](https://www.bnbchain.org/en/hackathons/bnb-ai-hack)
- Discord：https://discord.com/invite/bnbchain

## License

MIT
