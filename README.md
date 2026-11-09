<!-- ============================================================
     GitHub Profile README 草稿（未发布）
     · 使用前：把仓库名改为与 GitHub 用户名完全一致（lengfengng-tech）
     ============================================================ -->

<div align="center">

<!-- 打字机标题 -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+a+Python+Full-Stack+Engineer;10+%E5%B9%B4%E5%90%8E%E7%AB%AF+%C2%B7+%E7%84%A6%E7%82%B9+AI+Agent+%2F+%E5%A4%9A%E6%99%BA%E8%83%BD%E4%BD%93%E7%BC%96%E6%8E%92;LangGraph+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+PMP%C2%AE+%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86)](https://git.io/typing-svg)

**十年 Python 全栈 → AI Agent 工程师 · PMP® 认证**
*从薪酬 SaaS 到医药平台，再到多智能体 AI 产品，一直在做"把复杂业务变成可靠系统"这件事*

[![PMP Certified](https://img.shields.io/badge/PMP%C2%AE-%E8%AE%A4%E8%AF%81%E9%A1%B9%E7%9B%AE%E7%BB%8F%E7%90%86-2F81F7?style=flat)](https://www.pmi.org/certifications/project-management-pmp)
[![GitHub followers](https://img.shields.io/github/followers/lengfengng-tech?style=flat&color=2F81F7)](https://github.com/lengfengng-tech)
![Profile Views](https://komarev.com/ghpvc/?username=lengfengng-tech&color=2F81F7&style=flat)

</div>

---

## 🧑‍💻 关于我

- 🐍 **10 年后端经验**，Python 为主，可独立扛全栈（React / Flutter / 小程序）
- 🤖 近年专注 **AI Agent 工程化**：LangGraph 多智能体编排、RAG、MCP、提示词工程、AI 编程工作流
- 🏅 **PMP® 认证项目经理**——既写得了核心代码，也带得好团队、控得住交付
- 🏗️ 相信**规格驱动开发**（OpenSpec）+ AI 结对编程是下一代开发范式，已在团队落地推行
- 🚀 极客，热爱技术与开源，自己造轮子并发布到 npm
- 📝 技术博客：[CSDN](https://blog.csdn.net/qq_31603575?type=blog)

## 👥 技术管理与团队

- 📐 **主导制定团队级技术规范并推动落地**：HTTP 路由设计规范（冒号动作段、子资源保留字 fail-closed）+ 静态路由审计测试，新增路由必须同步 OpenAPI 契约与 Mock BFF 白名单
- 🔄 **推行规格驱动开发流程**：提案 → 设计 → 实现 → 验证 → 归档的 OpenSpec 工作流，维护 `AGENTS.md` 边界约束（不让 LLM 编造业务事实、不可逆动作必须幂等键 + 人工确认）
- 🤝 **跨角色协作**：与产品、业务、审批方对齐需求，把模糊的业务诉求拆解成可评审、可交付、可回归的技术规格
- 🧑‍🏫 **AI 结对编程布道者**：在团队落地 Cursor / Claude Code / Codex / DeepSeek Harness 协作范式，把个人效率工具变成团队交付标准

## 🔥 高光时刻

| 成果 | 数字 |
|---|---|
| 算薪引擎回溯性能优化 | **+80%** 回算速度 |
| 异步任务化重构（Celery + Redis） | **-85%** 接口等待时间 |
| 页面静态化 + 缓存优化 | **-70%** 请求数 |
| 主导设计 AI 多智能体平台领域模型（租户隔离 / Memory 三作用域） | 从 0 到 1 落地生产 |

## 🛠️ 技术栈

<!-- 图标库：https://skillicons.dev 增删即可 -->
[![My Skills](https://skillicons.dev/icons?i=py,fastapi,react,ts,flutter,docker,postgres,redis,rabbitmq,git,vite&perline=11)](https://skillicons.dev)

**AI / Agent**：LangGraph · LangChain · RAG 知识引用 · MCP · DashScope/OpenAI 兼容 API · 提示词工程
**后端**：Python · FastAPI · Django · Flask · Odoo（二次开发 5 年+）· Spring Boot · Celery
**前端 / 跨端**：React · TypeScript · Vite · Ant Design · uni-app · Flutter · 微信小程序
**数据 / 基建**：PostgreSQL（多 Schema + Alembic）· Redis · RabbitMQ · Loki / Grafana · Docker Compose · 阿里云 OSS

## 🌟 代表作

### 🤖 AI 营销多智能体平台（当前，某 SaaS 公司）
> LangGraph · FastAPI · Flutter · React · PostgreSQL · RabbitMQ

- 作为**技术负责人**设计 **单主 Planner + 专用 Agent** 的多智能体协作链路：身份解析 → 槽位确认 → Campaign 冻结 → 生成执行，冻结后调参不改写既有数据
- 落地 **DomainPack 调参控制面**：Prompt / 业务规则 / 表单 / 风格按行业维护，走「作者态 → 评测 → 审批 → 不可变发布 → 灰度/回滚」全生命周期治理
- 基于 **Outbox 模式 + RabbitMQ** 构建异步打标链路，外部登记未配置时 **fail-closed**；全链路日志可按 `ai_query_id` 在 Loki/Grafana 追踪
- 主导领域模型设计：以 `tenant_id + subject_id` 隔离会话与消息，Memory 分 tenant-shared / subject-explicit / subject-inferred 三作用域

### 💰 薪酬 SaaS 核心模块（4 年，某 HR SaaS 公司）
> Python / Odoo · Java / Spring Boot · NumPy

- 定制算薪回溯功能，**回算速度提升 80%**，保障年金/加班/假期扣款正确回溯
- 财务过账报表（GL）自动生成；SQL 重写 ORM，大数据量导入性能显著优化
- 2021 年项目转 Java：搭建 e2e 框架、动态 Excel 公式计算引擎、报酬管理状态机，负责香港整体算薪定制

### 🧩 开源：DSH 桌面端插件
> DeepSeek Harness · Cordis · React

- [`dsh-workspace-memories`](https://github.com/lengfengng-tech/dsh-workspace-memories)：给 DSH 加"工作区记忆 + 全局记忆"，Markdown 注入系统提示，npm 已发布

## 📈 GitHub 统计

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=lengfengng-tech&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://streak-stats.demolab.com?user=lengfengng-tech&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">

*在业务里做工程，在工程里做艺术。*

</div>
