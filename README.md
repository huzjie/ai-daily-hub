# AI Daily Hub — 每日 AI 热点项目索引

> 每天发现一个 AI 热点，构建一个可运行的开源项目。一个网关、一套工具，把热点变成生产力。

## 📅 项目索引

| 日期 | 热点主题 | 项目 | 技术栈 | 规模 | 状态 |
|---|---|---|---|---|---|
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-10 | Claude Code 跨会话消息 / YC QM 多Agent / OpenAI Multi-Agent API | [**AgentMesh（多Agent编排平台）**](https://github.com/huzjie/agentmesh) | Python 3.13 + FastAPI + React 19 + WebSocket | 222 文件 / 116 测试 | ✅ 已发布 |
| 2026-07-31 | Kimi K3 开源 / 多模型百花齐放 | [**Unified AI Gateway（统一 AI 网关）**](https://github.com/huzjie/unified-ai-gateway) | Node.js 20 + TypeScript + Fastify + React 19 + SQLite | 874 文件 / 442 测试 | ✅ 已发布 |

---

## 🏆 今日精选（2026-08-11）

### AegisAgent（AI Agent 运行时安全网关与特权治理平台）

**热点背景**：2026-08 云安全联盟（CSA）披露 **CoreBreak** 漏洞族——AWS Bedrock AgentCore（CVE-2026-18830, CVSS 8.6）、Google ADK（CVE-2026-18236, CVSS 9.3）、Vercel @ai-sdk/harness（CVE-2026-64650/64651）可在**模型根本没运行**的情况下被触发工具调用；Claude Code / Gemini CLI 被一个 GitHub issue 就能在 CI 上执行代码并逐字符泄露 API Key（CVE-2026-12537, CVSS 10.0）。AI Agent 的运行时安全防线集体失守。

**项目定位**：一套可落地、可生产部署的 **AI Agent 运行时安全网关**。核心命题是"每一次工具调用都必须能被密码学地绑定回一次真实发生过的模型补全"，直击 CoreBreak 漏洞根因。

**核心能力**：
- 🔐 **Provenance 溯源引擎**：HMAC 签名 attestation token 绑定每次 tool call 到真实 completion，判定 UNSIGNED / FORGED / ORPHANED / MISMATCHED / REPLAYED / EXPIRED，逐条对应 CVE
- 📜 **策略引擎**：YAML 策略 DSL（matchers + conditions + effects）+ 8 个内置策略包 + 规则覆盖分析 + what-if 模拟器 + 热重载
- 🛡️ **多检测器检测层**：120+ 条签名规则（prompt 注入 / 凭据扫描 / 外泄链 / 工具投毒 / schema 漂移 / 行为异常 / 出网管控）
- 📦 **沙箱隔离**：Subprocess / Docker / Firejail 驱动 + seccomp + rlimit + 文件系统 jail + 出网白名单 + canary token + 12 项边界自测探针
- 👥 **人工审批**：多级 N-of-M 会签 + TOTP/硬件密钥 step-up + 逐级升级 + break-glass 紧急通道（防伪造审批）
- 🔌 **MCP 安全代理**：工具描述净化 + schema 钉扎 + shadow MCP 发现 + AI-BOM + 凭据隔离
- 🌐 **LLM 网关**：9 家供应商适配器（OpenAI/Anthropic/Gemini/Bedrock/Qwen/DeepSeek/Kimi/Ollama）+ 中间件 + 本地反向代理
- 🔗 **不可篡改审计**：HMAC 哈希链 + SQLite 持久化 + JSONL/CSV 导出 + Prometheus 指标
- 🖥️ **可观测**：CLI（9 子命令）+ REST API + 单文件深色 Web 控制台

**快速开始**：
```bash
git clone https://github.com/huzjie/aegisagent.git
cd aegisagent
pip install -e .
aegis init        # 生成配置
aegis doctor      # 环境诊断
aegis serve       # 启动 API + Web 控制台 http://127.0.0.1:8080
aegis check --json '{"tool":"shell.exec","arguments":{"command":"rm -rf /"}}'
```

**质量**：248 文件 / stdlib-only 内核（零第三方依赖）/ 9 框架集成（LangChain/LlamaIndex/AutoGen/CrewAI 等）/ Docker 多阶段构建 + docker-compose / GitHub Actions CI + CodeQL / 中英双语文档 + 威胁模型文档。

[![GitHub](https://img.shields.io/badge/Repo-aegisagent-blue)](https://github.com/huzjie/aegisagent)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/aegisagent/blob/main/LICENSE)

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
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-10 | [agentmesh](https://github.com/huzjie/agentmesh) | 企业级多Agent跨会话协作编排平台：5大拓扑+消息总线+沙箱隔离+RBAC+7家Provider |
| 2026-07-31 | [unified-ai-gateway](https://github.com/huzjie/unified-ai-gateway) | 统一 AI 网关：一套接口对接 Kimi/DeepSeek/OpenAI 等 7 家 LLM，智能路由+限流熔断+成本追踪 |

---

## 📌 关于

本项目由 [AI Daily Agent](https://github.com/huzjie/ai-daily-agent) 自动驱动：每日 12:00 自动发现 AI 热点 → 分析原理 → 规划需求 → 生成完整可运行项目（代码/测试/文档/CI/Docker）→ 发布到 GitHub。

> **AI Daily Hub** — 每天一个热点，每天一个可用项目。⭐ Star 关注每日更新！
