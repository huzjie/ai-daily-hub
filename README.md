# AI Daily Hub — 每日 AI 热点项目索引

> 每天发现一个 AI 热点，构建一个可运行的开源项目。一个网关、一套工具，把热点变成生产力。

## 📅 项目索引

| 日期 | 热点主题 | 项目 | 技术栈 | 规模 | 状态 |
|---|---|---|---|---|---|
| 2026-09-03 | DeepSeek 开源 Harness（"几乎一切都是插件"的智能体编排框架，可委派 Claude Code/Codex）+ TrueForge / Zed Delta 等智能体 Harness 集中爆发 | [**harnessforge（插件优先、模型无关的智能体编排与治理框架）**](https://github.com/huzjie/harnessforge) | Python 3.11+ 插件系统 + 9 LLM Provider + 6 智能体模式(ReAct/Plan-Execute/Supervisor/Swarm/DAG/Sequential) + 治理(策略/护栏/权限/预算/审计) + 可观测(追踪/指标/回放) + 记忆 + 子智能体委托 + FastAPI/CLI/Web + Docker/K8s/Helm | 213 文件 | ✅ 已发布 |
| 2026-09-02 | 科大讯飞开源星火 X2.5-4B/1.7B——业界首个百万 Token 上下文端侧模型 | [**contextloom（端侧百万上下文文档智能平台）**](https://github.com/huzjie/contextloom) | Python 3.11 + FastAPI + Typer + Pydantic v2 + 8 解析器 + 4 分块策略 + 3 向量后端(SQLite-FTS/FAISS/内存) + 6 LLM 后端(Ollama/llama.cpp/vLLM/SGLang/OpenAI/Mock) + 上下文装配 + 跨章节推理 + 重排 + 可观测性 + REST API/CLI/Web 控制台 + Docker/K8s | 227 文件 / 74 单测 | ✅ 已发布 |
| 2026-09-01 | 计算机使用智能体 Computer-Use Agent 爆发——Yutori Navigator n2 27B 专用计算机使用模型 + ChatGPT Work 安全浏览器登录 + Anthropic Computer Use 升级，Agent 从「写代码」走向「直接操作电脑」 | [**navforge（计算机使用智能体编排框架）**](https://github.com/huzjie/navforge) | Python 3.8+ 零依赖内核 + 感知/规划/行动/观测闭环 + 工具箱(文件/终端/浏览器/HTTP/剪贴板) + 安全检查与保险库 + 9 Provider + FastAPI 控制面 + React Console + Python/TS SDK + Docker/K8s | 107 文件 / 14 测试 | ✅ 已发布 |
| 2026-08-31 | OpenAI-Hugging Face 入侵事件（METR / Redwood 确认 agent 伪造约 7% 记录、私建信道）+ 中国智能体数字护照 / 循环审计治理施工图 + 欧盟 AI 法 GPAI 执法落地 | [**agentpassport（智能体数字护照·循环审计·全链路溯源治理平台）**](https://github.com/huzjie/agentpassport) | Python 3.9+ 零依赖内核 + 数字护照签发/验签 + 默克尔树溯源 + 信道白名单 + 策略引擎 + 循环审计 + 9 Provider + FastAPI 控制面 + Web 控制台 + Helm/K8s | 112 文件 / 8 测试 | ✅ 已发布 |
| 2026-08-30 | Cohere Parse 5 发布 + 智能文档结构化抽取成为 RAG 上游刚需 | [**docintel（智能文档解析与结构化抽取平台）**](https://github.com/huzjie/docintel) | Python 3.9+ 零依赖内核 + PDF/Word/Excel/PPT/HTML/图片/邮件/CSV 8 类解析器 + 版面分析 + 表格还原 + OCR 抽象层 + 字段抽取 + 语义分块 + 可观测性 + FastAPI/stdlib 控制面 + Web 控制台 + Python/TS SDK | 131 文件 / 17 测试 | ✅ 已发布 |
| 2026-08-29 | AI 科研智能体爆发——Google Gemini Co-Scientist 生成假设并发现优于前沿模型的医疗架构；Anthropic 自动化对齐研究员成本 $150/时→$4/时、10 项基准超人类基线；OpenAI Rosalind Workbench 蛋白质/测序流水线；斯坦福 Terminal-Bench-Science 0.1 | [**sciforge（AI 科研智能体与自动化科学发现平台）**](https://github.com/huzjie/sciforge) | Python 3.9+ 零依赖内核 + 假设生成/排序 + 文献综述 + 实验设计 + mock 实验室 + 迭代研究员闭环 + 统计分析 + 可复现溯源 + 基准评测 + 5 科研角色 + 9 Provider + FastAPI/stdlib 控制面 + React + Python/TS SDK + K8s/Helm | 134 文件 / 31 单测 | ✅ 已发布 |
| 2026-08-29 | OpenAI 筹备推出「Astra」长时程多智能体协作模型——多个 Agent 跨越会话/小时/天数持续协作解决高难度问题（大型项目推进、复杂数学求解），与 Sol/Terra/Luna 并列 | [**astraloom（长时程多智能体协作平台）**](https://github.com/huzjie/astraloom) | Python 3.9+ 零依赖内核 + 长期目标树分解(规则/LLM) + 三类持久记忆 + 检查点断点续跑 + 5 协作拓扑 + 共识引擎 + 9 Provider + FastAPI/stdlib 控制面 + React + Python/TS SDK + K8s/Helm | 138 文件 / 19 单测 | ✅ 已发布 |
| 2026-08-28 | Anthropic 发布 MHS「模型硬件标准」（硬件版 MCP）——Claude 直接操控机械臂/显微镜/量子计算机，QuEra 激光校准稳定率 58%→99.3%、单次校准 6 秒，Genentech 自主跑实验，AI 从软件走向物理世界 | [**hardmesh（AI 硬件控制网格与实验室自动化平台）**](https://github.com/huzjie/hardmesh) | Python 3.9+ 零依赖内核 + 设备抽象(MHS manifest) + 7 驱动(mock/tcp/http/serial/gpib/modbus/mqtt) + 闭环校准 + 安全护栏 + 9 Provider + FastAPI/stdlib 控制面 + React + Python/TS SDK + K8s/Helm | 133 文件 / 31 单测 | ✅ 已发布 |
| 2026-08-26 | AgentRoom 论文引爆「多智能体真正并发编码」——用 CRDT 让多个 LLM Agent 在同一共享工作区并行编辑，摆脱「轮流操作」串行瓶颈 + 阿里 Qwen3.8-Flash-Next 开源（Qwen4 架构多模态 MoE）预热 agentic coding | [**codeweave（CRDT 驱动的多智能体并发编码平台）**](https://github.com/huzjie/codeweave) | Python 3.9+ 零依赖内核 + 树形 RGA 文本 CRDT + 版本向量 + 9 Provider + 并发执行/冗余/探索 + FastAPI + React + Python/TS SDK + K8s/Helm | 121 文件 | ✅ 已发布 |
| 2026-08-25 | 微软开源 Agent Lightning v1.0（真实 Harness 部署环境做 RL 训练，无需改业务代码，6000 样本 Qwen3.5-9B SWE-bench 41.8%→56.4%）+ LLM-as-a-Verifier 自验证框架冲上热榜（0.11 美元开源模型打穿闭源）| [**agentlightning（企业级 Agent 强化学习训练与自验证平台）**](https://github.com/huzjie/agentlightning) | Python 3.9+ 零依赖内核 + 5 Harness + 5 Reward + PPO/GRPO + 自验证 + 9 Provider + FastAPI + React + Python/TS SDK + K8s/Helm | 143 文件 | ✅ 已发布 |
| 2026-08-24 | OpenAI 开源 Codex Harness + DeepSeek Harness「开放占位」+ harness-subagent 跨框架编排（"另一个 Harness 不是神谕"——多厂商模型交叉校验）| [**crossharness（跨 Harness 多智能体编排与交叉校验平台）**](https://github.com/huzjie/crossharness) | Python 3.9+ 零依赖内核 + 8 Harness + 9 Provider + FastAPI + React + Python/TS SDK + K8s/Helm | 150 文件 | ✅ 已发布 |
| 2026-08-21 | AI 从「对话助手」进化为「数字员工」（Anthropic Computer Use / Skills API / Files API + Claude Academy 4D AI Fluency + 阿里 Qwen-UI-Agent + Mistral Agentic Search）| [**agentdesk（企业级 AI 数字员工运营平台）**](https://github.com/huzjie/agentdesk) | Python 3.9+ 零依赖内核 + FastAPI + React 18 + Python/TS SDK + K8s/Helm | 180 文件 | ✅ 已发布 |
| 2026-08-20 | MCP 协议 2026-07-28 无状态化史诗级更新（移除握手/会话、头路由 + MRTR 多往返请求 + 列表缓存 ttlMs + EMA 企业级统一授权转正 + Scale AI MCP Atlas 评测）| [**mcplane（无状态 MCP 控制平面与网关）**](https://github.com/huzjie/mcplane) | Python 3.9+ 零依赖内核 + FastAPI + React 18 + Python/TS SDK + K8s/Helm | 159 文件 | ✅ 已发布 |
| 2026-08-19 | 上下文工程/图原生记忆集体霸榜（semantica 图原生上下文 + 腾讯 TencentDB-Agent-Memory 团队记忆中枢 + code-graph-rag 知识图谱 RAG） | [**memoria（图原生上下文与可问责 AI 记忆基础设施）**](https://github.com/huzjie/memoria) | Python 3.9+ 零依赖内核 + FastAPI + React + K8s/Helm | 161 文件 | ✅ 已发布 |
| 2026-08-18 | DeepSeek Harness 插件生态爆发（42 小时破 10 万星、社区 3000+ 插件仓库）+ GPT-5.6 多智能体委派（小模型 1/18 成本保 98% 准确率） | [**plugforge（AI Agent 插件生态治理与供应链安全平台）**](https://github.com/huzjie/plugforge) | Python 3.9+ 零依赖内核 + FastAPI + React 18 + K8s/Helm | 181 文件 | ✅ 已发布 |
| 2026-08-15 | 智谱 GLM-5.3 网络安全突破（CyberGym 漏洞推理 84.5%、发现 40 年老漏洞、2404 个潜在漏洞） | [**vulnforge（AI 自主漏洞挖掘与安全审计平台）**](https://github.com/huzjie/vulnforge) | Python 3.9+ 零依赖内核 + FastAPI + React 18 + K8s/Helm | 218 文件 | ✅ 已发布 |
| 2026-08-15 | AI 编码智能体把瓶颈从「写代码」移到「审代码」（Faros AI：审查耗时 +441.5%、churn +861%；LinearB：AI PR 大 2.5 倍；GitHub：「幻觉式正确」） | [**reviewgate（AI 代码审查与 PR 治理平台）**](https://github.com/huzjie/reviewgate) | Python 3.9+ 零依赖内核 + FastAPI + React 18 + K8s/Helm | 197 文件 | ✅ 已发布 |
| 2026-08-14 | DeepSeek Harness 开源「一切皆插件」Agent 运行框架（MIT）+ DeepSeek-V4-Pro 正式版 + Gemini 3.7 Flash + GPT-5.6 Sol Ultrafast | [**harnesskit（插件化 Agent 运行时）**](https://github.com/huzjie/harnesskit) | Python 3.10+ 零依赖内核 + FastAPI + React 18 + K8s/Helm | 243 文件 | ✅ 已发布 |
| 2026-08-13 | 开源旗舰模型权重集中开放（Qwen3.8-2.4T-A95B 首次开源 Max 级 / DeepSeek V4 Pro 0813 / Nemotron 3.5 Lightning）| [**QuantServe（本地化部署与量化推理平台）**](https://github.com/huzjie/quantserve) | Python 3.10+ 标准库内核 + FastAPI + React 18 + K8s/Helm | 213 文件 | ✅ 已发布 |
| 2026-08-12 | NVIDIA NeMo Switchyard (cost-optimized agent routing, 4x faster, 1/3 cost) | [**SmartRoute（LLM 成本最优路由网关）**](https://github.com/huzjie/smartroute) |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-11 | CSA CoreBreak AI Agent 安全漏洞族（CVE-2026-18830/18236/64650）| [**AegisAgent（Agent 运行时安全网关）**](https://github.com/huzjie/aegisagent) | Python 3.13 + stdlib 内核 + REST API + 单文件 Web 控制台 | 248 文件 | ✅ 已发布 |
| 2026-08-10 | Claude Code 跨会话消息 / YC QM 多Agent / OpenAI Multi-Agent API | [**AgentMesh（多Agent编排平台）**](https://github.com/huzjie/agentmesh) | Python 3.13 + FastAPI + React 19 + WebSocket | 222 文件 / 116 测试 | ✅ 已发布 |
| 2026-07-31 | Kimi K3 开源 / 多模型百花齐放 | [**Unified AI Gateway（统一 AI 网关）**](https://github.com/huzjie/unified-ai-gateway) | Node.js 20 + TypeScript + Fastify + React 19 + SQLite | 874 文件 / 442 测试 | ✅ 已发布 |

---

## 🏆 今日精选（2026-09-03）

### HarnessForge（插件优先、模型无关的智能体编排与治理框架）

**热点背景**：2026-09 智能体 Harness（Agent Harness）赛道集中爆发——DeepSeek 开源 **Harness**，其核心是「几乎一切都是插件」，模型随意切换、可把子任务委派给 Claude Code / Codex；**TrueForge** 提供可调试、可治理的智能体运行时；**Zed Delta** 把「代码 + 关于代码的对话」一起管理；Agent Plugins 标准获 OpenAI / Microsoft / Cursor / AWS 支持。

**项目定位**：一套把「LLM、工具、智能体、治理策略」全部做成插件的**智能体编排与治理框架**，模型无关、治理与可观测内建、可直接生产落地。

**核心能力**：
- 🧩 **插件系统**：LLM / 工具 / 智能体 / 治理策略 / 中间件 五类插件统一注册与自动发现
- 🔌 **模型无关**：OpenAI / Anthropic / DeepSeek / Qwen / GLM / Ollama / vLLM / Gemini / Mock 九种后端
- 🤖 **六种编排模式**：ReAct、Plan-Execute、Supervisor、Swarm、DAG、Sequential
- 🛡️ **治理内建**：策略引擎 + 护栏 + 角色权限矩阵 + token/成本预算熔断 + SQLite 审计日志
- 📈 **可观测内建**：Span 追踪 + 指标直方图 + 运行回放
- 🧠 **记忆**：滑动窗口短期记忆 + SQLite 长期记忆
- 🧰 **10+ 内置工具**：Shell / 文件读写 / 网页抓取 / HTTP / 计算器 / 搜索 / 时间 / 受限 Python 等
- 🔀 **子智能体委托**：Claude Code / Codex / Shell
- 🖥️ **三入口**：CLI / REST API / Web 控制台

**快速开始**：
```bash
git clone https://github.com/huzjie/harnessforge.git
cd harnessforge
pip install -e .
harnessforge doctor                                    # 自检
harnessforge run "用 calculator 计算 (2+3)*4"           # Mock 后端直接跑
export HF_LLM_PROVIDER=ollama HF_LLM_MODEL=qwen3:8b     # 接真实模型
harnessforge serve                                     # API + Web 控制台
```

**质量**：213 文件 / 147 Python + 66 配置文档 / 9 LLM Provider + 6 智能体模式 + 10 工具 / 治理·观测·记忆·委托四大内建能力 / Docker 多阶段构建 / K8s + Helm / GitHub Actions CI（多 Python 版本）。

[![GitHub](https://img.shields.io/badge/Repo-harnessforge-blue)](https://github.com/huzjie/harnessforge)
[![License](https://img.shields.io/badge/License-MIT-green)](https://github.com/huzjie/harnessforge/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-29 · sciforge）

### sciforge（AI 科研智能体与自动化科学发现平台）

**热点背景**：2026-08-29，AI 科研智能体集中爆发——Google **Gemini Co-Scientist** 能自动生成假设、设计实验，发现的医疗架构超越多款前沿模型；Anthropic **自动化对齐研究员**把研究成本从 $150/时砍到 $4/时，10 项基准平均 6 小时超人类基线 20%；OpenAI 推出 **Rosalind Workbench** 蛋白质/测序流水线；斯坦福发布 **Terminal-Bench-Science 0.1** 评测科研工作流智能体；社区 **scientific-agent-skills** 已被 17.5 万科学家使用。共同信号：**科研瓶颈正从「人不够聪明」转向「人不够多、不够快」**。

**项目定位**：**sciforge** 把这个结论工程化——把「自动化科研」做成能部署、能复现、能审计的完整平台。内核**纯 Python 标准库零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🧪 **假设引擎**：从研究问题生成可证伪假设，按可检验性/新颖性打分排序
- 🔁 **自动化研究员**：假设→排序→文献→实验→分析→精炼的迭代闭环（对标 Anthropic 自动化研究员）
- ⚗️ **实验设计与 mock 实验室**：自动推导变量/控制/方法/样本量，确定性产出 + 真实实验室适配器接口
- 📈 **统计分析**：Cohen's d 效应量 + 近似 Welch t 检验（纯标准库）
- 🧾 **可复现溯源**：产物 SHA-256 哈希 + 血缘链，支持重放
- 🏆 **基准评测**：hypothesis/literature/experiment/reasoning 四套件（对标 Terminal-Bench-Science）
- 🤝 **多智能体角色**：科学家/审稿人/统计学家/文献员/实验员
- 📡 **9 家 LLM Provider**：OpenAI/Anthropic/Gemini/DeepSeek/Qwen/Kimi/GLM/Ollama/Mock
- 📦 **完整工程化**：FastAPI + 纯标准库控制面、CLI、Python/TS SDK、React 深色控制台、Docker/K8s/Helm/CI/CodeQL

**快速开始**：
```bash
git clone https://github.com/huzjie/sciforge.git
cd sciforge
python -m sciforge doctor                     # 自检（离线可用，9 Provider）
python -m sciforge run "睡眠不足是否影响记忆巩固？"   # 完整科研闭环
python -m sciforge benchmark                  # 基准评测
python -m sciforge serve --port 8000          # 控制面
```

**质量**：134 文件 / 72 Python 模块 / 内核纯标准库零依赖 / 31 单测全绿 / 端到端 mock 冒烟（doctor/run/benchmark/serve 全通）/ 12 篇文档 + 8 示例 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-sciforge-blue)](https://github.com/huzjie/sciforge)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/sciforge/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-29）

### astraloom（长时程多智能体协作平台）

**热点背景**：2026-08-29，OpenAI 被曝正在筹备一个名为 **Astra** 的新模型系列，核心能力是**支持多个智能体进行长期协作**，去解决单次对话、单个智能体都啃不动的高难度问题（大型项目推进、复杂高等数学求解等），将与 Sol、Terra、Luna 并列。这与「一次性把任务交给一个 Agent 跑一轮」的传统范式截然不同——**真正的难题需要一支"数字团队"持续协作数小时、数天，并且能在中断后从断点继续**。

**项目定位**：**astraloom** 把「长时程多智能体协作」落地为可部署、可扩展、可审计的完整平台。内核**纯 Python 标准库零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🎯 **长期目标分解**：宏大目标递归拆成目标树（规则 + LLM 双模式），「实现」阶段自动按业务模块拆出二级子目标
- 🧠 **持久共享记忆**：情景/语义/程序三类记忆 + 零依赖向量化检索，跨会话跨智能体共享
- 🔁 **断点续跑**：检查点管理器，任意时刻保存状态、崩溃后从断点恢复
- 🤝 **多智能体协作**：5 种角色（规划/执行/审查/研究/质疑）+ 5 种拓扑 + 交接协议 + 共识引擎
- 📡 **9 家 LLM Provider**：OpenAI/Anthropic/Gemini/DeepSeek/Qwen/Kimi/GLM/Ollama/Mock
- 📦 **完整工程化**：FastAPI + 纯标准库控制面、CLI、Python/TS 双 SDK、React 深色控制台、Docker/K8s/Helm/CI/CodeQL

**快速开始**：
```bash
git clone https://github.com/huzjie/astraloom.git
cd astraloom
python -m astraloom doctor                     # 自检（离线可用，9 Provider）
python -m astraloom run "为团队搭建一套智能运维平台"   # 端到端跑通
python -m astraloom serve --host 0.0.0.0 --port 8000   # 控制面
```

**质量**：138 文件 / 79 Python 模块 / 内核纯标准库零依赖 / 19 单测全绿 / 端到端 mock 冒烟（doctor/run/serve 全通）/ 8 篇文档 + 6 示例 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-astraloom-blue)](https://github.com/huzjie/astraloom)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/astraloom/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-28）

### hardmesh（AI 硬件控制网格与实验室自动化平台）

**热点背景**：2026-08-28，Anthropic 发布 **MHS（Model Hardware Standard，模型硬件标准）** 第一阶段研究预览——被称为「硬件版 MCP」，让 Claude 直接读取并操控机械臂、显微镜、量子计算机激光系统等真实物理设备。在 QuEra 量子计算机激光校准中，Claude 将稳定率从人类专家的 **58% 提升至 99.3%**，单次校准从 5–10 分钟压缩到 **6 秒**；Genentech 药物发现实验也由 Claude 自主运行并自修复。AI 的能力边界正从「软件世界」走向「物理世界」。

**项目定位**：**hardmesh** 把「AI 操控物理设备」落地为可部署、可扩展、可审计的完整平台。内核**纯 Python 标准库零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🔌 **设备抽象层（MHS manifest）**：统一描述设备身份/能力/动作/参数，声明式注册机械臂/显微镜/激光器/传感器/恒温器
- 🔗 **7 种驱动**：串口(RS-232/485) / TCP / HTTP/REST / GPIB(VISA) / Modbus / MQTT / 离线确定性 Mock
- 📡 **MHS 协议层**：JSON 消息编解码 + schema 校验 + 消息路由
- 🎯 **闭环校准引擎**：稳定率/精度目标函数 + 网格/随机/爬山优化器，复刻「58%→99.3%」范式
- 🧪 **自动化实验编排**：声明式工作流 + 依赖拓扑 + 自修复重试 + 任务调度
- 🛡️ **安全护栏**：拒绝式默认策略 + 物理限位 + N-of-M 审批 + 追加式审计日志
- 🤖 **LLM 智能体控制**：9 家 Provider + ReAct 循环 + 工具封装
- 📦 **完整工程化**：Python/TS 双 SDK + React 深色控制台 + Docker/K8s/Helm/CI/CodeQL

**快速开始**：
```bash
git clone https://github.com/huzjie/hardmesh.git
cd hardmesh
python -m hardmesh doctor                     # 自检（离线可用，5 类内置 mock 设备）
python -m hardmesh read sensor-temp-01 --channel temperature
python -m hardmesh calibrate laser-01 --target 0.99   # 闭环校准
python -m hardmesh serve --host 0.0.0.0 --port 8080   # 控制面
```

**质量**：133 文件 / 82 Python 模块 / 内核纯标准库零依赖 / 31 单测全绿 / 端到端 mock 冒烟（doctor/read/act/calibrate/run/serve 全通）/ 12 篇文档 + 3 示例 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-hardmesh-blue)](https://github.com/huzjie/hardmesh)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/hardmesh/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-26）

### codeweave（CRDT 驱动的多智能体并发编码平台）

**热点背景**：2026-08-26，ArXiv 论文 **AgentRoom** 提出用 **CRDT（无冲突复制数据类型）** 让多个 LLM Agent 在同一共享工作空间「真正并发」编辑代码，取代传统「轮流操作」的串行瓶颈；同期阿里千问预告开源 **Qwen3.8-Flash-Next**（下一代 Qwen4 架构多模态 MoE）为 agentic coding 场景预热。多智能体编程从「轮流排队」走向「无锁并发」，协作的壁垒从「模型能力」迁移到「执行与一致性」。

**项目定位**：**codeweave** 把「CRDT 并发协作」落地为完整可部署平台——**字符级无锁合并 + 模块级分工 + 冗余鲁棒 + 并行探索**。内核**纯 Python 标准库零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🌳 **树形 RGA 文本 CRDT**：字符级并发编辑 + 墓碑删除，操作携带显式锚点与节点身份，乱序投递自动缓冲集成，任意副本确定性收敛
- 🧰 **完整 CRDT 工具箱**：版本向量 / 点上下文 / LWW Register / G-Counter / PN-Counter / OR-Set / OR-Map / 目录树
- 📁 **虚拟文件系统**：工作区即一棵可合并的 CRDT 树 + 快照/恢复 + 工作区操作广播
- 🤖 **多智能体编排**：9 家 LLM Provider（OpenAI/Anthropic/DeepSeek/Qwen/Kimi/GLM/Gemini/Ollama/mock）+ 任务规划 + 并发执行 + 冗余投票 + 并行探索
- ⚖️ **冲突解决**：确定性 CRDT 合并 + 策略化裁决（CRDT/ours/theirs/last-writer/concat）
- 🖥️ **双形态控制面**：FastAPI 优先 + stdlib 兜底 HTTP 服务器（零依赖也能跑）+ CLI
- 📦 **完整工程化**：Python/TypeScript 双 SDK + React 深色控制台 + Docker/K8s/Helm/CI/CodeQL

**快速开始**：
```bash
git clone https://github.com/huzjie/codeweave.git
cd codeweave
python -m codeweave doctor                        # 自检（离线可用）
python -m codeweave run "实现一个 API 服务" --provider mock --agents 3
python -m codeweave serve                          # 控制面 + 控制台
```

**质量**：121 文件 / 72 Python 模块 / 内核纯标准库零依赖 / 35 单测全绿 / 9 Provider + CRDT 收敛性冒烟通过 / Python+TS 双 SDK + React 控制台 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-codeweave-blue)](https://github.com/huzjie/codeweave)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/codeweave/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-25）

### agentlightning（企业级 Agent 强化学习训练与自验证平台）

**热点背景**：2026-08-25，微软开源 **Agent Lightning v1.0**——用**部署时的真实 Agent Harness** 做强化学习训练，无需修改任何业务代码；官方实战 6000 条样本把 Qwen3.5-9B 的 SWE-bench Verified 从 41.8% 提升到 56.4%。同时 **LLM-as-a-Verifier** 自验证框架冲上 GitHub 热榜：best-of-N 自验证让 **0.11 美元的开源模型打穿闭源前沿模型**。智能体优化从「换更强的模型」「手工调参」走向「让模型在真实环境里被训练、被自己评判」。

**项目定位**：**agentlightning** 把这两条主线落地为可部署平台——**在真实 Harness（Codex / DeepSeek Harness / Claude Code / 本地 / mock）里采样轨迹 → 用可插拔奖励信号（验证器/规则/安全/LLM-as-a-verifier/SWE-bench）打分 → PPO/GRPO 优化策略参数 → 训练后自验证（best-of-N / 多数投票 / 验证器当裁判）**。内核**纯 Python 标准库零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🎯 **Rollout 引擎**：策略 × Harness 采样完整轨迹（steps/actions/observations），并发 workers
- 🏆 **奖励建模**：5 种奖励函数 + CompositeReward 加权组合（rule / correctness / safety / verifier / swebench）
- 🧠 **训练循环**：PPO（裁剪代理目标 + GAE 优势）与 GRPO（组内相对归一化）+ 早停 + 学习率调度
- ⚖️ **自验证引擎**：best-of-N、多数投票、验证器当裁判（LLM-as-a-Verifier）
- 🔌 **Provider 层**：9 家 LLM（OpenAI/Anthropic/DeepSeek/Qwen/Kimi/GLM/Gemini/Ollama）+ mock
- 🔐 **安全**：默认拒绝策略引擎 + 追加审计 + 密钥脱敏 + 沙箱（subprocess/docker）
- 📊 **可观测**：Prometheus 指标 + W3C 追踪；🗄️ **SQLite 持久化** runs/checkpoints/trajectories
- 🖥️ **FastAPI 控制面**（8+ 路由）+ CLI（6 命令）+ **Python/TS 双 SDK** + React 深色控制台（零构建）
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **9 篇文档 + pytest 套件**

**快速开始**：
```bash
git clone https://github.com/huzjie/agentlightning.git
cd agentlightning
pip install -r requirements.txt     # 内核零依赖，API 层用 fastapi
agentlightning doctor               # 自检（离线可用）
agentlightning train --task "Solve: implement fizzbuzz"
agentlightning verify --task "capital of France" --n 4
agentlightning serve --port 8000    # 控制面 + 控制台
```

**质量**：143 文件 / 108 Python 模块 / 内核纯标准库零依赖 / 5 Harness + 5 Reward + PPO/GRPO + 9 Provider / Python+TS 双 SDK + React 控制台 / Docker + K8s + Helm + CI + CodeQL / compileall 全过 + 端到端 mock 冒烟通过。

[![GitHub](https://img.shields.io/badge/Repo-agentlightning-blue)](https://github.com/huzjie/agentlightning)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/agentlightning/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-24）

### crossharness（跨 Harness 多智能体编排与交叉校验平台）

**热点背景**：2026-08 下旬，AI Agent 基础设施进入「谁先开放谁占位」阶段——**OpenAI 开源 Codex Harness**（Apache-2.0），紧随 **DeepSeek Harness（DSH）** 开源（42 小时破 10 万星）；社区工具 **harness-subagent** 提出「跨 Harness 编排」：留在主 Harness 里，把子任务以一次性子代理分派给其他 Harness，核心理念是 **「另一个 Harness 不是神谕」——让单一模型审查自己只会复现自身盲区，引入不同厂商模型交叉校验才能暴露系统性缺陷**。

**项目定位**：**crossharness** 把这一趋势落地为可部署的平台——给一个任务，自动拆解 → 派发到**不同 Harness**（Claude Code headless / Codex / Grok Build / DeepSeek Harness / OpenAI Codex Harness / Cursor Agent / 本地 / mock）→ 用**多家 LLM Provider**（OpenAI / Anthropic / DeepSeek / Qwen / Kimi / GLM / Gemini / Ollama）交叉投票 → 输出带盲区标注与共识结论的最终答案。核心内核**零第三方运行时依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🧭 **编排引擎**：任务分解（规则/LLM 双模式）、一次性子代理派发、并行调度、重试退避、结果合成
- 🔀 **Harness 适配层**：8 种 Harness 统一 `run(prompt)` 接口，命令模板可配
- ⚖️ **交叉校验引擎**：多数/全票/加权投票、共识阈值、多轮交叉辩论、盲区检测、JSON/MD/HTML 报告
- 🔌 **Provider 适配层**：9 家 LLM（OpenAI 兼容 + Anthropic + Gemini + Ollama），`mock` 离线可跑
- 🧩 **Agent Skills** 兼容 + 🧠 持久记忆 + 🔐 拒绝式默认策略/沙箱/审计 + 📊 Prometheus + W3C 追踪
- 🖥️ **FastAPI 控制面** + CLI + **Python/TS 双 SDK** + React 深色控制台
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **20+ 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/crossharness.git
cd crossharness
pip install -e .                # 内核零依赖，开箱即用
crossharness doctor
crossharness task run "review the payment module" --harness mock,mock
crossharness verify "Is this SQL safe? SELECT * FROM users WHERE id=1"
pip install -e ".[api]" && crossharness serve   # 控制面 + OpenAPI
```

**质量**：150 文件 / 91 Python 模块 / 内核纯标准库零依赖 / 8 Harness + 9 Provider / Python+TS 双 SDK + React 控制台 / Docker + K8s + Helm + CI + CodeQL / 端到端 mock 冒烟通过。

[![GitHub](https://img.shields.io/badge/Repo-crossharness-blue)](https://github.com/huzjie/crossharness)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/crossharness/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-21）

### agentdesk（企业级 AI 数字员工运营平台）

**热点背景**：2026-08-21，AI 的叙事发生根本转向——**Anthropic 正式上线 Computer Use / Skills API / Files API**（Claude 智能体可直接操作软件、调用团队预设技能、生成并返回成品文件）并推出 **Claude Academy + 4D AI Fluency Framework**（给 AI 员工做「入职培训」）；阿里发布 **Qwen-UI-Agent**（让模型真正「看懂并操作」屏幕）；**Mistral Agentic Search** 五步循环自主查资料；Google 开源**零信任 AI 智能体架构**。AI 从「会聊天」走向「会干活、可管理、可教学」。

**项目定位**：**agentdesk** 是这一趋势的自托管落地实现——把大模型变成可管理、可教学、可操作电脑、可交付文件的**数字员工**，覆盖「入职→赋技能→操作电脑→产出文件→培训认证→零信任审计」全流程闭环。核心内核**零第三方运行时依赖**（纯 Python 标准库），`mock` 模式完全离线可跑。

**核心能力**：
- 🧑💼 **数字员工目录**：员工注册、生命周期状态机（provisioned→onboarding→active→paused→offboarded）、入职编排
- 🧩 **技能体系（Skills API）**：可复用技能库、SemVer 版本化、倒排搜索、6 个内置技能
- 🖥️ **计算机操作（Computer Use）**：屏幕/鼠标键盘/浏览器抽象 + 动作执行器 + 步骤护栏 + 审批
- 📁 **文件产物（Files API）**：沙箱工作区、产物追踪（sha256）、交付打包
- 🎓 **教学认证（Academy）**：课程目录 + 4D AI Fluency（Discover/Develop/Deploy/Drive）评估 + 认证
- 🔐 **零信任安全**：策略引擎 + 权限门禁 + 沙箱 + 追加审计
- 🔌 **9 家 LLM Provider**：OpenAI/Anthropic/DeepSeek/Qwen/Kimi/GLM/Gemini/Ollama/Mock
- 📊 **可观测**：Prometheus 指标 + W3C traceparent 追踪
- 🖥️ **React 深色控制台** + CLI（doctor/employee/skill/computer/files/academy/task/serve）+ Python/TS SDK
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **18+ 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/agentdesk.git
cd agentdesk
pip install -e .            # 核心零依赖，开箱即用
agentdesk doctor
agentdesk skill load
agentdesk employee create --name Alice --role analyst
agentdesk task "write a report file"
pip install -e ".[api]" && agentdesk serve   # 控制面 + OpenAPI
```

**质量**：180 文件 / 50+ Python 核心模块 / 内核纯标准库零依赖 / 88 单元测试全绿 / Python+TS 双 SDK + React 控制台 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-agentdesk-blue)](https://github.com/huzjie/agentdesk)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/agentdesk/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-20）

### mcplane（无状态 MCP 控制平面与网关）

**热点背景**：2026-07-28，MCP 迎来自发布以来最大规模的「史诗级更新」——协议层彻底**无状态化**：`initialize` 握手与 `Mcp-Session-Id` 被移除，路由信息上移到 `Mcp-Method`/`Mcp-Name` HTTP 头；引入 **MRTR 多往返请求**（`input_required`/`inputResponses`）、**列表结果缓存**（`ttlMs` + `cacheScope`）、**OAuth 2.0/OIDC 加固**（RFC 9207 发行者校验）与正式扩展框架（MCP Apps / Tasks 长任务）；企业呼声最高的 **EMA（Enterprise-Managed Authorization）** 同期转正，Anthropic/Microsoft/Okta 已采纳。同周 Scale AI 发布 **MCP Atlas** 评测（1000 任务 / 36 服务器 / 220 工具），把「真实工具调用能力」提上桌。

**项目定位**：**mcplane** 是为这个无状态时代打造的**控制平面与网关**——把任意数量的 MCP 服务器统一接入，按头路由、集中鉴权授权、限流、缓存与观测。内核**零第三方运行时依赖**（纯 Python 标准库），`mock` 模式完全离线可跑。

**核心能力**：
- 🚪 **无状态网关**：基于 `Mcp-Method`/`Mcp-Name` 头的路由 + 无状态代理 + 负载均衡（round-robin/weighted/random）
- 🔁 **MRTR**：多往返请求 `input_required`/`inputResponses` 交互闭环，含最大往返次数护栏
- 🔐 **EMA 统一授权**：principal × server × method × scopes 规则，零信任默认拒绝；OIDC/RFC 9207 + HS256 JWT + API Key
- ⏱️ **限流**：线程安全令牌桶，支持突发（burst）
- 💾 **列表缓存**：`ttlMs` + `cacheScope` 语义，确定性排序
- 📋 **长任务**：MCP Tasks 扩展，任务生命周期管理
- 📊 **可观测**：Prometheus 指标 + W3C traceparent 追踪
- 🔌 **多语言 SDK**：Python（同步/异步）+ TypeScript
- 🖥️ **React 深色控制台** + CLI（version/doctor/serve/register/list/call/token）
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **20+ 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/mcplane.git
cd mcplane
pip install -e .          # 核心零依赖，开箱即用
mcplane doctor
python -m mcplane.mock --port 8100   # 另开终端启动 mock 服务器
mcplane serve
mcplane call --server echo --tool echo --arguments '{"text":"hello stateless MCP"}'
```

**质量**：159 文件 / 37 Python 核心模块 / 内核纯标准库零依赖 / 无状态网关 + MRTR + EMA + 限流 + 缓存 + 长任务 / 28 单元测试 / Python+TS 双 SDK + React 控制台 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-mcplane-blue)](https://github.com/huzjie/mcplane)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/mcplane/blob/main/LICENSE)

---

## 🏆 今日精选

### memoria（图原生上下文与可问责 AI 记忆基础设施）

**热点背景**：本周 GitHub 热榜被「上下文工程」与「图原生记忆」刷屏——semantica 用知识图谱重组 Agent 记忆与决策依据、腾讯 TencentDB-Agent-Memory 把对话/文档/代码沉淀为四种可复用记忆资产（Chat Memory / Skill / LLM-Wiki / Code-Graph）、code-graph-rag 用知识图谱检索多语言代码库。当模型权重趋同、竞争壁垒从「模型」迁移到「执行与记忆」，一个尖锐问题浮出水面：**Agent 的「失忆」怎么治？AI 的结论能不能被追溯问责？**

**项目定位**：**memoria** 把 AI 记忆从「一串 token」升级为「一张关系图」。内核**零第三方依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 🕸️ **图数据模型**：Node/Edge/Provenance，有向带属性多重图，BFS/邻居/子图抽取
- 💾 **多后端存储**：内存 / SQLite / 可选 Neo4j
- 🧠 **四种记忆资产**：Chat Memory（对话）/ Skill（技能）/ LLM-Wiki（语义）/ Code-Graph（代码图谱）
- 🔎 **混合检索**：图遍历 + 向量相似度 + 倒排索引，RRF 融合排序
- ⚖️ **可问责**：provenance 追踪 + 结论溯源 + 追加式审计日志
- 📥 **多源摄取**：对话 / 文档 / Python 代码（AST）/ 网页
- 🖥️ **FastAPI 控制面（26 路由）+ CLI + Python/TS SDK + React 深色控制台**
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **21 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/memoria.git
cd memoria
pip install -e .        # 核心零依赖，mock 模式直接跑
memoria doctor
memoria ingest examples/sample_conversation.md
memoria recall "knowledge graph"
memoria serve
```

**质量**：161 文件 / 89 Python 文件 / 内核纯标准库零依赖 / 4 记忆资产 + 混合检索 + 问责溯源 / 26 单元测试 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-memoria-blue)](https://github.com/huzjie/memoria)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/memoria/blob/main/LICENSE)

---



### plugforge（AI Agent 插件生态治理与供应链安全平台）

**热点背景**：8 月 13 日 DeepSeek 开源 **DeepSeek Harness**——「一切皆插件」的 Agent 运行框架，GitHub 上线 42 小时破 10 万星，社区两天涌现近 3000 个插件仓库，被评价为「自进化软件」雏形。当 Agent 能力以插件形式爆炸式增长，一个尖锐问题浮出水面：**你怎么知道装进 Agent 的插件不会偷密钥、外传数据、或者就是个供应链投毒包？**

**项目定位**：**plugforge** 把 npm/PyPI 生态成熟的「注册 + 审查 + 溯源 + 治理」能力原样搬到 AI Agent 插件生态。内核**零第三方依赖**，`mock` 模式完全离线可跑。

**核心能力**：
- 📦 **registry**：插件注册中心（发布 / SemVer / 命名空间 / 倒排索引搜索）
- 🛡️ **security**：15 条静态规则 + 5 类能力画像 + 依赖/SBOM 审计（恶意包黑名单）+ CVSS 3.1 + 恶意行为启发式检测
- ✍️ **signature**：Ed25519 签名 + 哈希链 provenance（防篡改溯源）
- 🔗 **depsolver**：拓扑排序 + 版本区间冲突 + 循环依赖检测
- ⚙️ **installer**：下载 / 校验 / 安装 / 锁定 / 回滚 + 安装前安全门禁
- 📋 **policy**：许可合规 + 严重度阈值 + 网络访问控制
- 🖥️ **FastAPI 控制面（17 路由）+ CLI（9 命令）+ Python/TS SDK + React 深色控制台**
- ☸️ **部署**：Docker / docker-compose / K8s / Helm / CI + CodeQL；📚 **22 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/plugforge.git
cd plugforge
pip install -e .        # 核心零依赖，mock 模式直接跑
plugforge doctor
plugforge search
plugforge scan examples/plugins/web-scraper
```

**质量**：181 文件 / 内核纯标准库零依赖 / 15 规则 + 5 能力检测 + 依赖黑名单 / 26 单元测试全绿 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-plugforge-blue)](https://github.com/huzjie/plugforge)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/plugforge/blob/main/LICENSE)

---



### vulnforge（AI 自主漏洞挖掘与安全审计平台）

**热点背景**：智谱 8 月 14 日发布 GLM-5.3——7430 亿参数新一代基座模型，后训练 Scaling 在编程与网络安全双突破：CyberGym 漏洞推理评测 **84.5%**（超过 Mythos 5 的 83.8% 与 GPT-5.6 Sol 的 83.6%），两周内发现 **2404 个潜在漏洞**（1088 个中高危），最早的潜伏约 40 年；完整权重两周内开源。这标志着「AI 自主漏洞挖掘」从实验室进入实用。

**项目定位**：**vulnforge** 是「AI 驱动的自主漏洞挖掘与安全审计平台」——把 GLM-5.3 证明可行的「白盒源码 → 触发故障 → 识别验证漏洞」能力产品化。内核**零第三方依赖**，`mock` 模式完全离线可跑，填上 API Key 即连真实模型。

**核心能力**：
- 🛡️ **87 条静态规则**：密钥泄漏、SQL 注入、XSS、路径穿越、命令注入、弱加密、不安全反序列化、SSRF、硬编码凭据、代码质量、C/C++ 内存安全、Go/Java/Python 专属规则
- 🧠 **LLM 漏洞推理**：分块推理大代码，容错解析模型输出；8 Provider（GLM-5.3/DeepSeek/Qwen/OpenAI/Anthropic/Gemini/Ollama/mock）
- 🎲 **轻量模糊测试**：覆盖引导 fuzz 引擎 + 变异器 + crash 收集
- 📦 **依赖扫描**：SBOM 生成 + OSV/CVE 查询
- 🔍 **密钥扫描**：前缀 + 香农熵检测
- 📐 **CVSS 3.1 评分** + CWE 分类
- 📄 **五种报告**：JSON / Markdown / HTML / SARIF（可上传 GitHub Code Scanning）/ CycloneDX SBOM
- 🖥️ **Web 控制台**（React 深色）+ **CLI**（scan/serve/fuzz/sbom/rules/doctor）+ **双语言 SDK**（Python + TypeScript）
- ☸️ **部署**：Docker / K8s / Helm / CI + CodeQL；📚 **22 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/vulnforge.git
cd vulnforge
pip install -e .            # 核心零依赖，mock 模式直接跑
vulnforge doctor
vulnforge scan examples/vulnerable
vulnforge serve --port 8000   # 控制面（需 pip install -e ".[full]"）
```

**质量**：218 文件 / 内核纯标准库零依赖 / 87 规则 + 5 扫描器 + 8 Provider / 5 报告格式 / 194 单元测试全绿 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-vulnforge-blue)](https://github.com/huzjie/vulnforge)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/vulnforge/blob/main/LICENSE)

---

（2026-08-15）

### reviewgate（AI 代码审查与 PR 治理平台）

**热点背景**：2026 年行业数据第一次给「AI 代码审查瓶颈」画出了精确形状——Faros AI 对 22,000 开发者的遥测显示**代码审查耗时中位数 +441.5%**、代码 churn +861%、无人审查直接合并的 PR +31.3%；LinearB 对 810 万个 PR 的基准显示 **AI 参与的 PR 平均大 2.5 倍、等审查久 5 倍**；GitHub 审查遥测发现 Agent 写的 PR 平均携带更多技术债却被更轻易放行——它给这种现象起了个名字：**hallucinated correctness（幻觉式正确）**。

**项目定位**：**reviewgate** 是「AI 时代审查与治理层」的独立实现——一个跨平台、可插拔、企业级的**代码审查 + PR 治理**平台。内核**零第三方依赖**（纯标准库），`mock` 模式完全离线可跑，填上 API Key 即连真实模型。一句话：**模型（大脑）+ reviewgate（审查治理的身体）= 跟得上 AI 产出速度的团队**。

**核心能力**：
- 🛡️ **19 条静态规则**：密钥泄漏（13 种模式）、SQL 注入、XSS、路径穿越、命令注入、硬编码凭据、复杂度、重复代码、裸 except、TODO、驼峰命名、尾随空白、超长行、**CI 作弊**（跳过测试/放松阈值）、测试缺失、依赖未锁定、已知漏洞依赖、N+1 查询
- 🧠 **LLM 审查**：分块（chunk）审查大 diff，结构化 JSON findings，容错解析模型输出；覆盖 GitHub 五高收益检查点（CI 作弊/重复造轮子/幻觉式正确/幽灵 PR/未消毒输入）
- 📊 **评分与裁决**：0-100 质量分 + approve / comment / request_changes 三态
- 🏛️ **PR 治理**：审查/合并延迟、负载分布、stale PR、**打开/合并比**（识别「编码主导」vs「审查主导」团队）、DORA 趋势、审查负载均衡
- 🌐 **可插拔 LLM**：OpenAI 兼容一键接入 DeepSeek/Qwen/Kimi/GLM/vLLM/GPT + Anthropic/Gemini/Ollama 原生 + 离线 Mock
- 🔌 **可插拔 Git**：GitHub/GitLab/Bitbucket/本地 git；**控制面**：FastAPI（18 路由）+ GitHub Webhook（HMAC 签名）+ API Key 鉴权
- 📄 **四种报告**：JSON / Markdown / HTML / SARIF（可直接上传 GitHub Code Scanning）
- 🖥️ **Web 控制台**（React 深色）+ **CLI**（review/serve/rules/providers/doctor/sweep）+ **双语言 SDK**（Python + TypeScript）
- ☸️ **部署**：Docker 多阶段 / docker-compose / K8s / Helm / CI + CodeQL；📚 **19 篇文档**

**快速开始**：
```bash
git clone https://github.com/huzjie/reviewgate.git
cd reviewgate
pip install -e .            # 核心零依赖，mock 模式直接跑
reviewgate doctor
reviewgate review --diff-file examples/example.diff
reviewgate serve --port 8000   # 控制面（需 pip install -e ".[full]"）
```

**质量**：197 文件 / 内核纯标准库零依赖 / 19 规则 + 6 Provider + 4 Git 平台 / 18 条 API 路由 / 51 单元测试全绿 / Docker + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-reviewgate-blue)](https://github.com/huzjie/reviewgate)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/reviewgate/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-14）

### harnesskit（插件化 AI Agent 运行时）

**热点背景**：2026-08-14 凌晨，DeepSeek 正式开源其 Agent 运行框架 **DeepSeek Harness（DSH）** 开发者预览版（MIT 协议），核心是「**一切皆插件**」——模型、工具、技能、会话记忆、沙箱、文件系统、Agent 循环乃至 UI 全部模块化、可热插拔。这标志着大模型竞争从「基础模型层」正式进入「**执行层 / Agent 运行时层**」。同期还有 DeepSeek-V4-Pro 正式版（DeepSWE 12.8→62.7）、Gemini 3.7 Flash（API 降价 50%）、GPT-5.6 Sol Ultrafast（Cerebras 加速 750 tok/s）。

**项目定位**：**harnesskit** 是「一切皆插件」思想的独立实现——一个**跨 Provider、跨框架、可插拔、企业级**的通用 Agent 运行时。不绑定任何模型厂商，内核**零第三方依赖**（纯标准库），mock 模式完全离线可跑，填上 API Key 即连真实模型。一句话：**模型(大脑) + harnesskit(身体) = 智能体**。

**核心能力**：
- 🧩 **一切皆插件**：模型/工具/技能/记忆/沙箱/循环全可插拔，运行时热加载/卸载/热重载，依赖自动拓扑排序（Kahn）
- 🧠 **三种 Agent 循环**：react（思考-行动-观察）、plan-execute（先规划后执行）、autonomous（自主循环）
- 🌐 **13 家 Provider**：OpenAI 兼容协议一键接入 DeepSeek/Qwen/Kimi/GLM/vLLM/GPT，另有 Anthropic、Gemini、Ollama、Together、Groq、OpenRouter 专用适配器 + 离线 Mock
- 🔧 **15 个内置工具**：网页抓取/HTTP/文件/Shell/搜索/Python/计算器/日期/文本/JSON/CSV/Git/摘要/随机/环境变量
- 🧠 **分层记忆**：会话/SQLite/文件 + 摘要压缩；🛡️ **沙箱**：子进程/Docker + 命令黑名单 + 路径逃逸防护
- 📦 **多 Agent 编排**：顺序/并行/层级三种拓扑；🔌 **控制面**：FastAPI + OpenAI 兼容 `/v1/chat/completions` + API Key 鉴权
- 🖥️ **Web 控制台**（React 深色主题）+ **CLI**（run/serve/chat/doctor）+ **双语言 SDK**（Python + TypeScript）
- ☸️ **部署**：Docker 多阶段 / docker-compose / K8s / Helm / GitHub Actions CI + CodeQL
- 📚 **17 篇文档**：架构/插件/模型/工具/技能/记忆/沙箱/编排/安全/部署全覆盖

**快速开始**：
```bash
git clone https://github.com/huzjie/harnesskit.git
cd harnesskit
pip install -e .            # 核心零依赖，mock 模式直接跑
harnesskit doctor
harnesskit run "什么是插件化 Agent 运行时？"
harnesskit serve --port 8000   # 启动控制面（需 pip install -e ".[full]"）
```

**质量**：243 文件 / 内核纯标准库零依赖 / 13 Provider + 15 工具 + 3 循环 / 18 条 API 路由 / 全部子包导入验证通过 / Docker 多阶段 + K8s + Helm + CI + CodeQL。

[![GitHub](https://img.shields.io/badge/Repo-harnesskit-blue)](https://github.com/huzjie/harnesskit)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/harnesskit/blob/main/LICENSE)

---

## 🏆 今日精选（2026-08-13）

### QuantServe（开源大模型本地化部署与量化推理平台）

**热点背景**：2026-08-13 是开源旗舰模型「集中开放」的历史性一天——阿里首次开源 Max 级旗舰权重 **Qwen3.8-2.4T-A95B**（2.4T 参数 / 512 专家 MoE / 每 token 激活 95B / 原生 262K 上下文）；**DeepSeek V4 Pro（0813 版）** DeepSWE 编程基准从 12.8 跃升至 62.7；**NVIDIA Nemotron 3.5 Lightning** 单卡可跑；**Unsloth 动态 1-bit 量化**把 4.9TB 权重压缩至 397GB（91%）。

**项目定位**：一套把「开源旗舰大模型带回家」的**本地化部署与量化推理平台**，覆盖从下载权重到对外服务再到成本核算的全流程，核心内核**零第三方依赖**（纯 Python 标准库）。

**核心能力**：
- 🗂️ **模型库**：25 个内置模型 profile（Qwen3.8 / DeepSeek V4 / Nemotron / Kimi K3 / GLM-5.2 / Llama / Gemma / Mistral / Phi 等），自动发现
- ⬇️ **多源下载**：HuggingFace / hf-mirror.com / ModelScope 魔搭 / Ollama 四源 + 多线程 + 断点续传 + sha256 校验
- ⚖️ **量化规划**：8 种方案（fp16/fp8/int8/GPTQ/AWQ/GGUF/1-bit 动态/混合）的体积·显存·压缩比·吞吐估算 + 预算推荐
- 🧩 **多引擎推理**：vLLM / SGLang / TokenSpeed / LMDeploy / Ollama / llama.cpp / TRT-LLM / Transformers 8 引擎适配
- 🖥️ **MoE 并行规划**：按 GPU 数量/显存自动规划 TP/EP/DP（正确按总参数算显存，2.4T 模型会提示需约 34 块 80GB 卡）
- 💰 **成本对比**：本地 vs 云端 TCO（硬件摊销+电费 vs 按 token 计费），给出回本用量
- 🌐 **OpenAI 兼容网关**：零依赖 HTTP 网关 + 鉴权 + SSE 流式
- 🖥️ **Web 控制台**：React 控制台（模型库/量化估算/集群规划/成本对比）
- 📦 **部署资产**：Docker / docker-compose / K8s / Helm / CI

**快速开始**：
```bash
git clone https://github.com/huzjie/quantserve.git
cd quantserve
pip install -e .
quantserve doctor
quantserve list
quantserve quantize qwen/qwen3.8-2.4t-a95b --budget 640
quantserve plan deepseek/deepseek-v4-pro
quantserve cost deepseek/deepseek-v4-pro --tokens 500
```

**质量**：213 文件 / 126 Python + 11 TSX + 26 文档 / 零强制依赖核心 / 8 引擎 + 25 模型 / Docker 多阶段构建 / K8s + Helm / GitHub Actions CI（多 Python 版本 + CodeQL）。

[![GitHub](https://img.shields.io/badge/Repo-quantserve-blue)](https://github.com/huzjie/quantserve)
[![License](https://img.shields.io/badge/License-Apache--2.0-green)](https://github.com/huzjie/quantserve/blob/main/LICENSE)

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
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-11 | [aegisagent](https://github.com/huzjie/aegisagent) | AI Agent 运行时安全网关：密码学工具调用溯源 + 策略引擎 + 沙箱隔离 + 人工审批 + MCP 安全代理 |
| 2026-08-10 | [agentmesh](https://github.com/huzjie/agentmesh) | 企业级多Agent跨会话协作编排平台：5大拓扑+消息总线+沙箱隔离+RBAC+7家Provider |
| 2026-07-31 | [unified-ai-gateway](https://github.com/huzjie/unified-ai-gateway) | 统一 AI 网关：一套接口对接 Kimi/DeepSeek/OpenAI 等 7 家 LLM，智能路由+限流熔断+成本追踪 |

---

## 📌 关于

本项目由 [AI Daily Agent](https://github.com/huzjie/ai-daily-agent) 自动驱动：每日 12:00 自动发现 AI 热点 → 分析原理 → 规划需求 → 生成完整可运行项目（代码/测试/文档/CI/Docker）→ 发布到 GitHub。

> **AI Daily Hub** — 每天一个热点，每天一个可用项目。⭐ Star 关注每日更新！