# AI Daily Hub — 每日 AI 热点项目索引

> 每天发现一个 AI 热点，构建一个可运行的开源项目。一个网关、一套工具，把热点变成生产力。

## 📅 项目索引

| 日期 | 热点主题 | 项目 | 技术栈 | 规模 | 状态 |
|---|---|---|---|---|---|
| 2026-08-10 | Claude Code 跨会话消息 / YC QM 多Agent / OpenAI Multi-Agent API | [**AgentMesh（多Agent编排平台）**](https://github.com/huzjie/agentmesh) | Python 3.13 + FastAPI + React 19 + WebSocket | 222 文件 / 116 测试 | ✅ 已发布 |
| 2026-07-31 | Kimi K3 开源 / 多模型百花齐放 | [**Unified AI Gateway（统一 AI 网关）**](https://github.com/huzjie/unified-ai-gateway) | Node.js 20 + TypeScript + Fastify + React 19 + SQLite | 874 文件 / 442 测试 | ✅ 已发布 |

---

## 🏆 今日精选（2026-08-10）

### AgentMesh（企业级多Agent跨会话协作编排平台）

**热点背景**：Claude Code 推出跨会话消息传递、YC 开源 QM 多Agent harness、OpenAI 发布 Multi-Agent API——多Agent协作与跨会话通信成为 AI 工程的核心主题，企业需要一套安全可控的多Agent编排平台。

**项目定位**：一个企业级多 Agent 跨会话协作与编排平台。让多个 AI Agent 在隔离沙箱中运行，通过消息总线跨会话通信协作，统一编排调度，对标 Claude Code Cross-Session Messaging + YC QM + OpenAI Multi-Agent API。

**核心能力**：
- 🧩 **5 大编排拓扑**：Sequential / Parallel / Hierarchical / Debate / Reducer 一键切换
- 💬 **跨会话消息总线**：Agent 间 pub/sub 消息路由 + WebSocket 实时推送 + 持久化回放
- 🏗️ **隔离沙箱**：Docker 沙箱 + seccomp 配置 + CPU/内存/超时资源限制，安全执行不可信代码
- 🛡️ **安全治理**：JWT/API-Key 认证 + RBAC 权限 + 限流 + 哈希链审计日志 + 密钥管理
- 🔌 **7 家 Provider 适配器**：OpenAI / Gemini / Qwen / Zhipu / Kimi / MiniMax / Ollama
- 🧠 **分层记忆**：会话记忆 / 跨会话交接 / 向量语义检索
- 🛠️ **工具系统**：代码执行 / Web 搜索 / 文件操作 / HTTP / Shell / 数据库（只读）/ 自定义工具注册
- 📊 **可视化控制台**：React 19 + TypeScript + Tailwind（Agent / 工作流 / 消息 / 工具 / 指标仪表盘）
- 📦 **双语言 SDK**：Python + TypeScript，REST + WebSocket 全能力覆盖

**快速开始**：
```bash
git clone https://github.com/huzjie/agentmesh.git
cd agentmesh
pip install -e .
cp .env.example .env   # 填写 Provider API Key
uvicorn agentmesh.api.server:app --port 8000
cd src/agentmesh/web && npm install && npm run dev   # 控制台 http://localhost:5173
```

**质量**：222 文件 / 116 单元测试通过 / Docker 多阶段构建 + docker-compose / Kubernetes + Helm + Terraform 部署 / GitHub Actions CI / 中英双语文档。

[![GitHub](https://img.shields.io/badge/Repo-agentmesh-blue)](https://github.com/huzjie/agentmesh)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/agentmesh/blob/main/LICENSE)

---
---

## 🗂️ 全部项目

| 日期 | 项目 | 说明 |
|---|---|---|
| 2026-08-10 | [agentmesh](https://github.com/huzjie/agentmesh) | 企业级多Agent跨会话协作编排平台：5大拓扑+消息总线+沙箱隔离+RBAC+7家Provider |
| 2026-07-31 | [unified-ai-gateway](https://github.com/huzjie/unified-ai-gateway) | 统一 AI 网关：一套接口对接 Kimi/DeepSeek/OpenAI 等 7 家 LLM，智能路由+限流熔断+成本追踪 |

---

## 📌 关于

本项目由 [AI Daily Agent](https://github.com/huzjie/ai-daily-agent) 自动驱动：每日 12:00 自动发现 AI 热点 → 分析原理 → 规划需求 → 生成完整可运行项目（代码/测试/文档/CI/Docker）→ 发布到 GitHub。

> **AI Daily Hub** — 每天一个热点，每天一个可用项目。⭐ Star 关注每日更新！
