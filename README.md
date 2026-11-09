<!-- ============================================================
     GitHub Profile README（lengfengng-tech）
     · English first; the Chinese version lives in a collapsible
       <details> block at the bottom — the only switch GitHub Markdown supports.
     ============================================================ -->

<div align="center">

<!-- Typing header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=680&lines=Python+Full-Stack+Engineer+%C2%B7+10+Years;Focus%3A+AI+Agent+%2F+Multi-Agent+Orchestration;LangGraph+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+PMP%C2%AE)](https://git.io/typing-svg)

**10 years of backend engineering → AI Agent engineer · PMP® certified**
*From payroll SaaS to pharma platforms to multi-agent AI products — turning complex business domains into reliable systems*

[![PMP Certified](https://img.shields.io/badge/PMP%C2%AE-Certified-2F81F7?style=flat)](https://www.pmi.org/certifications/project-management-pmp)
[![GitHub followers](https://img.shields.io/github/followers/lengfengng-tech?style=flat&color=2F81F7)](https://github.com/lengfengng-tech)
![Profile Views](https://komarev.com/ghpvc/?username=lengfengng-tech&color=2F81F7&style=flat)

</div>

---

## 🧑‍💻 About Me

- 🐍 **10 years of backend experience**, primarily Python, comfortable owning the full stack (React / Flutter / mini-programs)
- 🤖 Recently focused on **production AI Agent engineering**: LangGraph multi-agent orchestration, RAG, MCP, prompt engineering, AI-assisted development workflows
- 🏅 **PMP® certified project manager** — writes core code, leads teams, and delivers
- 🏗️ Believes **spec-driven development** (OpenSpec) + AI pair programming is the next dev paradigm; already practices it with my team
- 🚀 Geek at heart, loves open source, builds my own wheels and ships them to npm
- 📝 Tech blog (Chinese): [CSDN](https://blog.csdn.net/qq_31603575?type=blog)

## 👥 Leadership & Team

- 📐 **Owns team-level engineering standards**: HTTP routing conventions (colon action segments, fail-closed reserved sub-resources) enforced by static route audit tests; every new route ships with its OpenAPI contract and Mock BFF whitelist
- 🔄 **Drove spec-driven development adoption**: a proposal → design → implement → verify → archive OpenSpec workflow, plus `AGENTS.md` guardrails (LLMs must never invent business facts; irreversible actions require idempotency keys + human confirmation)
- 🤝 **Cross-functional collaboration**: translate fuzzy business asks into reviewable, deliverable, regression-tested technical specs with product, business, and approval stakeholders
- 🧑‍🏫 **AI pair-programming champion**: rolled out Cursor / Claude Code / Codex / DeepSeek Harness workflows, turning personal productivity tools into the team's delivery standard

## 🔥 Highlights

| Outcome | Number |
|---|---|
| Payroll back-calculation engine optimization | **+80%** speed |
| Async offloading with Celery + Redis | **-85%** API wait time |
| Page static-caching optimization | **-70%** requests |
| Domain model for a multi-agent AI platform (tenant isolation / 3-tier memory scopes) | 0 → 1 in production |

## 🛠️ Tech Stack

[![My Skills](https://skillicons.dev/icons?i=py,fastapi,react,ts,flutter,docker,postgres,redis,rabbitmq,git,vite&perline=11)](https://skillicons.dev)

**AI / Agent**: LangGraph · LangChain · RAG with knowledge citations · MCP · DashScope / OpenAI-compatible APIs · prompt engineering
**Backend**: Python · FastAPI · Django · Flask · Odoo (5+ years customization) · Spring Boot · Celery
**Frontend / Cross-platform**: React · TypeScript · Vite · Ant Design · uni-app · Flutter · WeChat mini-programs
**Data / Infra**: PostgreSQL (multi-schema + Alembic) · Redis · RabbitMQ · Loki / Grafana · Docker Compose · Alibaba Cloud OSS

## 🌟 Featured Work

### 🤖 AI Marketing Multi-Agent Platform (current, a SaaS company)
> LangGraph · FastAPI · Flutter · React · PostgreSQL · RabbitMQ

- As the **tech lead**, designed a **single-master Planner + specialized agents** collaboration pipeline: identity resolution → slot confirmation → campaign freezing → content generation; frozen campaigns are never rewritten by later tuning
- Shipped the **DomainPack tuning control plane**: prompts, business rules, form definitions, and content styles maintained per industry, governed through an author → evaluation → approval → immutable release → canary/rollback lifecycle; the runtime loads only published exact versions, strictly isolated from drafts
- Built an async tagging pipeline on the **Outbox pattern + RabbitMQ** with automatic retries, **fail-closed** when external registries are unconfigured; full-link tracing in Loki/Grafana by `ai_query_id`
- Owned the domain model: sessions and messages isolated by `tenant_id + subject_id`; memory in three scopes — tenant-shared / subject-explicit / subject-inferred

### 💰 Payroll Core Module (4 years, an HR SaaS company)
> Python / Odoo · Java / Spring Boot · NumPy

- Customized payroll back-calculation — **+80% recalculation speed**, covering annuities, overtime, unpaid-leave, maternity, and sick-leave deductions
- Automated financial posting reports (GL); rewrote ORM hot paths in SQL for large-batch imports
- When the project moved to Java in 2021: built an e2e framework, a dynamic Excel-formula calculation engine, and a state-machine-based compensation module; owned Hong Kong payroll customization

### 🧩 Open Source: DSH Desktop Plugins
> DeepSeek Harness · Cordis · React

- [`dsh-workspace-memories`](https://github.com/lengfengng-tech/dsh-workspace-memories): adds per-workspace **and cross-workspace global memory** to DeepSeek Harness — Markdown files injected into every session's system prompt; published on npm

## 📈 GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=lengfengng-tech&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://streak-stats.demolab.com?user=lengfengng-tech&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center"><em>Engineering inside business, artistry inside engineering.</em></div>

<br>

<!-- ================= 中文版（折叠，点击展开） ================= -->
<details>
<summary><b>🇨🇳 中文版（点击展开 / Click to expand）</b></summary>

## 🧑‍💻 关于我

- 🐍 **10 年后端经验**，Python 为主，可独立扛全栈（React / Flutter / 小程序）
- 🤖 近年专注 **AI Agent 工程化**：LangGraph 多智能体编排、RAG、MCP、提示词工程、AI 编程工作流
- 🏅 **PMP® 认证项目经理**——既写得了核心代码，也带得好团队、控得住交付
- 🏗️ 相信**规格驱动开发**（OpenSpec）+ AI 结对编程是下一代开发范式，已在团队落地推行
- 🚀 极客，热爱技术与开源，自己造轮子并发布到 npm
- 📝 技术博客：[CSDN](https://blog.csdn.net/qq_31603575?type=blog)

## 👥 技术管理与团队

- 📐 **主导制定团队级技术规范**：HTTP 路由设计规范（冒号动作段、子资源保留字 fail-closed）+ 静态路由审计测试，新增路由同步 OpenAPI 契约与 Mock BFF 白名单
- 🔄 **推行规格驱动开发**：提案 → 设计 → 实现 → 验证 → 归档的 OpenSpec 流程，维护 `AGENTS.md` 边界约束（LLM 不得编造业务事实、不可逆动作必须幂等键 + 人工确认）
- 🤝 **跨角色协作**：与产品、业务、审批方对齐，把模糊需求拆成可评审、可交付、可回归的技术规格
- 🧑‍🏫 **AI 结对编程布道者**：落地 Cursor / Claude Code / Codex / DeepSeek Harness 协作范式，把个人效率工具变成团队交付标准

## 🔥 高光时刻

| 成果 | 数字 |
|---|---|
| 算薪引擎回溯性能优化 | **+80%** 回算速度 |
| 异步任务化重构（Celery + Redis） | **-85%** 接口等待时间 |
| 页面静态化 + 缓存优化 | **-70%** 请求数 |
| AI 多智能体平台领域模型（租户隔离 / Memory 三作用域） | 从 0 到 1 落地生产 |

## 🛠️ 技术栈

[![My Skills](https://skillicons.dev/icons?i=py,fastapi,react,ts,flutter,docker,postgres,redis,rabbitmq,git,vite&perline=11)](https://skillicons.dev)

**AI / Agent**：LangGraph · LangChain · RAG 知识引用 · MCP · DashScope/OpenAI 兼容 API · 提示词工程
**后端**：Python · FastAPI · Django · Flask · Odoo（二次开发 5 年+）· Spring Boot · Celery
**前端 / 跨端**：React · TypeScript · Vite · Ant Design · uni-app · Flutter · 微信小程序
**数据 / 基建**：PostgreSQL（多 Schema + Alembic）· Redis · RabbitMQ · Loki / Grafana · Docker Compose · 阿里云 OSS

## 🌟 代表作

### 🤖 AI 营销多智能体平台（当前，某 SaaS 公司）
> LangGraph · FastAPI · Flutter · React · PostgreSQL · RabbitMQ

- **作为技术负责人**设计**单主 Planner + 专用 Agent** 协作链路：身份解析 → 槽位确认 → Campaign 冻结 → 生成执行，冻结后调参不改写既有数据
- 落地 **DomainPack 调参控制面**：Prompt / 业务规则 / 表单 / 风格按行业维护，走「作者态 → 评测 → 审批 → 不可变发布 → 灰度/回滚」全生命周期治理，运行时只加载已发布精确版本，与作者态严格隔离
- 基于 **Outbox 模式 + RabbitMQ** 构建异步打标链路，自动重试，外部登记未配置时 **fail-closed**；全链路日志按 `ai_query_id` 在 Loki/Grafana 追踪
- 主导领域模型：`tenant_id + subject_id` 隔离会话与消息，Memory 分 tenant-shared / subject-explicit / subject-inferred 三作用域

### 💰 薪酬 SaaS 核心模块（4 年，某 HR SaaS 公司）
> Python / Odoo · Java / Spring Boot · NumPy

- 定制算薪回溯，**回算速度提升 80%**，保障年金/加班/假期扣款正确回溯
- 财务过账报表（GL）自动生成；SQL 重写 ORM，大数据量导入性能显著优化
- 2021 年项目转 Java：搭建 e2e 框架、动态 Excel 公式计算引擎、报酬管理状态机，负责香港整体算薪定制

### 🧩 开源：DSH 桌面端插件
> DeepSeek Harness · Cordis · React

- [`dsh-workspace-memories`](https://github.com/lengfengng-tech/dsh-workspace-memories)：给 DSH 加"工作区记忆 + 全局记忆"，Markdown 注入系统提示，npm 已发布

</details>
