<div align="center">

# solopreneur-skills

「把创业决策从感觉，变成可复用能力」

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Skill Set](https://img.shields.io/badge/Type-Solopreneur%20Skills-7B3FE4)
![Status](https://img.shields.io/badge/Status-Building-3B82F6)
![Compatible](https://img.shields.io/badge/Claude%20Code-Compatible-84cc16)

面向一人公司与个人项目的技能集合。  
从「要不要做」到「怎么做更稳」，用结构化对话与模块化框架提升决策质量。

[效果示例](#效果示例) · [安装](#安装) · [已收录-skill](#已收录-skill) · [工作方式](#工作方式) · [仓库结构](#仓库结构)

**Other Languages / 其他语言：**  
[English](./README.en.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md)

</div>

---

## 为什么是这个仓库

很多创业决策失败，不是因为不努力，而是因为在错误的问题上投入太深。  
`solopreneur-skills` 的目标是把这些关键判断，沉淀成可以长期复用的 skill：

- 机会到底值不值得做
- 解法是否可行、可落地
- 你是否是这件事的合适执行者
- 下一步最低成本该验证什么

---

## 效果示例

**用户**  
❯ 我有两个方向：做 AI 简历工具，或者做内容选题 SaaS，怎么选？

**solopreneur-skills（mpf-fit）**  
❯ 先不急着二选一。先回答两件事：  
1）哪个方向你有真实一线问题样本？  
2）如果 6 个月没有收入，你更愿意长期做哪一个？  

你先回答这两点，我再带你做第一轮 Market × Product × Founder 对比。

---

**用户**  
❯ 我已经决定做了，怎么提高成功率？

**solopreneur-skills（mpf-fit）**  
❯ 好，切到 C 模式（提升胜率）。  
先只看一个维度：可触达性。  
你最可能拿到前 20 个目标用户的渠道，是哪个具体社区或场景？

---

## 已收录 Skill

### mpf-fit

Market-Product-Founder Fit 对话决策技能，适用于：

- 赛道分析
- 机会评估
- 一人公司/副业方向选择
- 已决定要做后的策略优化
- 报告生成（快速版 / 完整版 / 建议版）

入口文件：`mpf-fit/SKILL.md`  
详细说明：`mpf-fit/README.md`

---

## 安装

本仓库为本地技能集合，建议在 Cursor / Claude Code 中直接使用。

示例触发语句：

```text
帮我评估这个项目值不值得做
我有三个副业方向，先帮我选
我已经决定做了，给我一个一周验证计划
出一份完整分析报告
```

---

## 工作方式

每个 skill 都遵循同一套工程化思路：

1. **主控层（Core）**：控制节奏、路由维度、决定是否出报告  
2. **模块层（Modules）**：按维度拆分能力，便于复用与扩展  
3. **模板层（Assets）**：报告模板独立维护，便于迭代表达  
4. **参考层（References）**：案例与方法论沉淀，支持持续增强

---

## 仓库结构

```text
solopreneur-skills/
├── README.md
└── mpf-fit/
    ├── SKILL.md
    ├── README.md
    ├── modules/
    ├── assets/
    └── references/
```

---

## 路线图

- 增加机会类型分类器（SaaS / 内容 IP / 工具 / 平台 / 咨询）
- 增加内部评分引擎（仅用于追问深度与报告时机）
- 扩展案例库（成功/失败样本与验证路径）
- 新增更多 solopreneur 场景技能（定位、定价、分发、复盘）

---

## Other Languages

当前主文档为中文。多语言文档预留如下（欢迎 PR）：

- English: `README.en.md`
- 日本語: `README.ja.md`
- 한국어: `README.ko.md`
- Español: `README.es.md`

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=kongusen/solopreneur-skills&type=Date)](https://www.star-history.com/#kongusen/solopreneur-skills&Date)

> 占位说明：仓库刚创建，Star 曲线会随时间自动更新。

---

## License

MIT
