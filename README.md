# AI Daily Hub — 每日 AI 热点项目索引

> 每天发现一个 AI 热点，构建一个可运行的开源项目。一个网关、一套工具，把热点变成生产力。

## 📅 项目索引

| 日期 | 热点主题 | 项目 | 技术栈 | 规模 | 状态 |
|---|---|---|---|---|---|
| 2026-07-31 | Kimi K3 开源 / 多模型百花齐放 | [**Unified AI Gateway（统一 AI 网关）**](https://github.com/huzjie/unified-ai-gateway) | Node.js 20 + TypeScript + Fastify + React 19 + SQLite | 874 文件 / 442 测试 | ✅ 已发布 |

---

## 🏆 今日精选（2026-07-31）

### Unified AI Gateway（统一 AI 网关）

**热点背景**：月之暗面发布 Kimi K3（2.8 万亿参数全球最大开源模型）上线两天被挤爆；DeepSeek V4、MiniMax、Inkling-Small 等模型百花齐放——多模型时代，开发者需要一个统一网关。

**项目定位**：一个可自托管的统一 LLM API 网关，用一套 **OpenAI 兼容接口**对接多家大模型提供商，提供智能路由、负载均衡、限流熔断、成本追踪与用量分析。

**核心能力**：
- 🔌 **OpenAI 兼容 API**：`POST /v1/chat/completions` + SSE 流式
- 🧩 **7 类 Provider 适配器**：OpenAI / Kimi(Moonshot) / DeepSeek / MiniMax / Anthropic / Ollama / Mock
- 🧭 **智能路由**：优先级 / 故障转移 / 成本优先 / 随机（带权重）
- 🛡️ **限流熔断**：token-bucket / fixed-window / sliding-window / 并发限制 + 熔断状态机 + 半开探测
- 💰 **成本追踪**：配置文件声明单价 × token 用量，多维度聚合统计
- 🔑 **多租户 Key 管理**：SHA-256 哈希存储、模型白名单、每 Key 限流
- 📊 **管理控制台**：React 19 + MUI + Tailwind（仪表盘 / Key / Provider / 路由 / 日志 / 审计）
- 🛠️ **CLI 管理**：key / provider / route / stats / log 全生命周期管理

**快速开始**：
```bash
git clone https://github.com/huzjie/unified-ai-gateway.git
cd unified-ai-gateway
pnpm install
cp .env.example .env   # 填写 Provider API Key
npm run dev            # 网关 http://localhost:8787
npm run dev:web        # 控制台 http://localhost:5173
```

**质量**：875 文件 / 442 个单元测试 100% 通过 / Docker 多阶段构建 / GitHub Actions CI+CD / 完整中文文档。

[![GitHub](https://img.shields.io/badge/Repo-unified--ai--gateway-blue)](https://github.com/huzjie/unified-ai-gateway)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/unified-ai-gateway/blob/main/LICENSE)

---

## 🗂️ 全部项目

| 日期 | 项目 | 说明 |
|---|---|---|
| 2026-07-31 | [unified-ai-gateway](https://github.com/huzjie/unified-ai-gateway) | 统一 AI 网关：一套接口对接 Kimi/DeepSeek/OpenAI 等 7 家 LLM，智能路由+限流熔断+成本追踪 |

---

## 📌 关于

本项目由 [AI Daily Agent](https://github.com/huzjie/ai-daily-agent) 自动驱动：每日 12:00 自动发现 AI 热点 → 分析原理 → 规划需求 → 生成完整可运行项目（代码/测试/文档/CI/Docker）→ 发布到 GitHub。

> **AI Daily Hub** — 每天一个热点，每天一个可用项目。⭐ Star 关注每日更新！
