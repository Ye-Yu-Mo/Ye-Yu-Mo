# 嗨，我是 Jasmine (Ye-Yu-Mo)

> **AI Infra · 量化投资 · Rust 系统编程**
>
> 做能落地的工程，不做概念自慰。Talk is cheap, show me the code.

## 🔭 正在做什么

- **[AI-SRE-Agent](https://github.com/Ye-Yu-Mo/AI-SRE-Agent)** — 让 AI 安全地运维真实 Linux 服务器，typed action + plan/apply，可审计可回滚
- **[FundVal-Live](https://github.com/Ye-Yu-Mo/FundVal-Live)** — 盘中基金实时估值，⭐ 497，持续迭代中

## 📫 联系

- Email: xulei.ahu@qq.com
- Blog: [ye-yu-mo.github.io](https://ye-yu-mo.github.io/)

## 📊 GitHub 数据

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=Ye-Yu-Mo&show_icons=true&count_private=true&hide_border=true&theme=default)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Ye-Yu-Mo&layout=compact&hide_border=true&langs_count=6&theme=default&exclude_repo=LearnRep,Ye-Yu-Mo.github.io,JasmineNote)

</div>

## ⭐ 核心项目

### [FundVal-Live](https://github.com/Ye-Yu-Mo/FundVal-Live) — 盘中基金实时估值
`Python` · ⭐ 497

盘中实时计算基金估值与净值，让持仓收益不用等收盘。配套两个数据 API：

- **[yjb-api](https://github.com/Ye-Yu-Mo/yjb-api)** (⭐8) — 养基宝 API
- **[xbyj-api](https://github.com/Ye-Yu-Mo/xbyj-api)** — 小倍养基 API

> 从数据采集到实时估值的完整基金量化链路。

### [AI-SRE-Agent](https://github.com/Ye-Yu-Mo/AI-SRE-Agent) — AI 安全运维 Agent
`Go + TypeScript + MCP`

让 AI 安全地部署和维护真实 Linux 服务器，核心是**不给 AI root shell**：

- **Typed Action** — AI 只能调用预定义动作，不能执行任意命令
- **Plan/Apply 分离** — 有副作用的操作先生成计划，风险分级后再执行
- **可审计可回滚** — 每次写操作记录 before/after，部署失败一键回滚
- **MCP 集成** — 17 个 MCP tools，Claude Code 直接调用

### [trade](https://github.com/Ye-Yu-Mo/trade) — 多智能体量化交易
`Rust + DeepSeek + Tokio` · ⭐ 9

纯 Rust 异步事件驱动交易引擎，集成 DeepSeek 多智能体做市场分析与决策，支持回测与币安实盘。

## 🛠 技术栈

**核心语言**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**领域与框架**

![MCP](https://img.shields.io/badge/MCP-Protocol-green?style=flat)
![DeepSeek](https://img.shields.io/badge/AI_Agents-DeepSeek-blue?style=flat)
![Tokio](https://img.shields.io/badge/Tokio-Async-FF6B35?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Binance](https://img.shields.io/badge/Binance-API-F0B90B?style=flat&logo=binance&logoColor=black)

## 📚 早期作品

打基础阶段的 C++ 系统编程练习，仍可参考：

- **[LogSystem](https://github.com/Ye-Yu-Mo/LogSystem)** — 异步双缓冲高性能日志系统
- **[Message-Queues](https://github.com/Ye-Yu-Mo/Message-Queues)** — AMQP 核心协议栈消息队列
- **[XuChat-server](https://github.com/Ye-Yu-Mo/XuChat-server)** — C++ 即时通讯服务端

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Ye-Yu-Mo)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:xulei.ahu@qq.com)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=flat&logo=blogger&logoColor=white)](https://ye-yu-mo.github.io/)

**Talk is cheap. Show me the code.**

</div>
