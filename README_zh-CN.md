# 🎭 The Agency：AI 专家团队，随时转变您的工作流

> **指尖上的完整 AI 代理团队** — 从前端专家到 Reddit 社区达人，从趣味注入者到现实检验者。每个智能体都是带个性、流程和验证交付物的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 这是什么？

源自 Reddit 讨论 and 数月迭代，**The Agency** 是精心打造的 AI 智能体人格集合。每个智能体：

- **🎯 专业化**：领域深度专长（非通用提示模板）
- **🧠 个性驱动**：独特语调、沟通风格和方法
- **📋 交付导向**：真实代码、流程和可测量结果
- **✅ 生产就绪**：实战检验工作流和成功指标

**想象为**：组建梦幻团队，但他们是不睡觉、不抱怨、始终交付的 AI 专家。

---

## ⚡ 快速开始

### 方式 1：与 Claude Code 使用（推荐）

```bash
# 复制智能体到 Claude Code 目录
cp -r agency-agents/* ~/.claude/agents/

# 在 Claude Code 会话中激活任何智能体：
# "Claude，激活 Frontend Developer 模式帮我构建 React 组件"
```

### 方式 2：作为参考使用

每个智能体文件包含：
- 身份与个性特征
- 核心使命与工作流
- 技术交付物及代码示例
- 成功指标与沟通风格

浏览下方智能体并复制/适配您需要的！

### 方式 3：与其他工具使用（Cursor、Aider、Windsurf、Gemini CLI、OpenCode、Kimi Code）

```bash
# 步骤 1 —— 为所有支持工具生成集成文件
./scripts/convert.sh

# 步骤 2 —— 交互式安装（自动检测已安装工具）
./scripts/install.sh

# 或直接安装特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool copilot
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool kimi
```

见下方 [多工具集成](#-多工具集成) 章节完整详情。

---

## 🎨 代理团队名单

### 💻 工程部

构建未来，逐次提交。

| 智能体 | 专长 | 适用场景 |
|--------|------|----------|
| 🎨 [Frontend Developer](engineering/engineering-frontend-developer.md) | React/Vue/Angular、UI 实现、性能 | 现代 Web 应用、像素级 UI、Core Web Vitals 优化 |
| 🏗️ [Backend Architect](engineering/engineering-backend-architect.md) | API 设计、数据库架构、可扩展性 | 服务端系统、微服务、云基础设施 |
| 📱 [Mobile App Builder](engineering/engineering-mobile-app-builder.md) | iOS/Android、React Native、Flutter | 原生和跨平台移动应用 |
| 🤖 [AI Engineer](engineering/engineering-ai-engineer.md) | ML 模型、部署、AI 集成 | 机器学习功能、数据管道、AI 驱动应用 |
| 🚀 [DevOps Automator](engineering/engineering-devops-automator.md) | CI/CD、基础设施自动化、云运维 | 管道开发、部署自动化、监控 |
| ⚡ [Rapid Prototyper](engineering/engineering-rapid-prototyper.md) | 快速 POC 开发、MVP | 快速概念验证、黑客马拉松项目、快速迭代 |
| 💎 [Senior Developer](engineering/engineering-senior-developer.md) | Laravel/Livewire、高级模式 | 复杂实现、架构决策 |
| 🔧 [Filament Optimization Specialist](engineering/engineering-filament-optimization-specialist.md) | Filament PHP admin UX、结构表单重设计、资源优化 | 重构 Filament 资源/表单/表格获得更快更清爽 admin 工作流 |
| 🔒 [Security Engineer](engineering/engineering-security-engineer.md) | 威胁建模、安全代码审查、安全架构 | 应用安全、漏洞评估、安全 CI/CD |
| ⚡ [Autonomous Optimization Architect](engineering/engineering-autonomous-optimization-architect.md) | LLM 路由、成本优化、影子测试 | 需智能 API 选择和成本护栏的自治系统 |
| 🔩 [Embedded Firmware Engineer](engineering/engineering-embedded-firmware-engineer.md) | 裸机、RTOS、ESP32/STM32/Nordic 固件 | 生产级嵌入式系统和 IoT 设备 |
| 🚨 [Incident Response Commander](engineering/engineering-incident-response-commander.md) | 事件管理、事后复盘、值班 | 管理生产事件和构建事件就绪 |
| ⛓️ [Solidity Smart Contract Engineer](engineering/engineering-solidity-smart-contract-engineer.md) | EVM 合约、Gas 优化、DeFi | 安全、Gas 优化智能合约和 DeFi 协议 |
| 📚 [Technical Writer](engineering/engineering-technical-writer.md) | 开发者文档、API 参考、教程 | 清晰、准确技术文档 |
| 🎯 [Threat Detection Engineer](engineering/engineering-threat-detection-engineer.md) | SIEM 规则、威胁狩猎、ATT&CK 映射 | 构建检测层和威胁狩猎 |
| 💬 [WeChat Mini Program Developer](engineering/engineering-wechat-mini-program-developer.md) | 微信生态、小程序、支付集成 | 为微信生态构建高性能应用 |
| 👁️ [Code Reviewer](engineering/engineering-code-reviewer.md) | 建设性代码审查、安全、可维护性 | PR 审查、代码质量关卡、通过审查指导 |
| 🗄️ [Database Optimizer](engineering/engineering-database-optimizer.md) | 模式设计、查询优化、索引策略 | PostgreSQL/MySQL 调优、慢查询调试、迁移规划 |
| 🌿 [Git Workflow Master](engineering/engineering-git-workflow-master.md) | 分支策略、约定式提交、高级 Git | Git 工作流设计、历史清理、CI 友好分支管理 |
| 🏛️ [Software Architect](engineering/engineering-software-architect.md) | 系统设计、DDD、架构模式、权衡分析 | 架构决策、领域建模、系统演进策略 |
| 🛡️ [SRE](engineering/engineering-sre.md) | SLO、错误预算、可观测性、混沌工程 | 生产可靠性、苦差减少、容量规划 |
| 🧬 [AI Data Remediation Engineer](engineering/engineering-ai-data-remediation-engineer.md) | 自愈管道、气隔 SLM、语义聚类 | 大规模修复损坏数据零数据丢失 |
| 🔧 [Data Engineer](engineering/engineering-data-engineer.md) | 数据管道、湖仓架构、ETL/ELT | 构建可靠数据基础设施和仓库 |
| 🔗 [Feishu Integration Developer](engineering/engineering-feishu-integration-developer.md) | 飞书/Lark 开放平台、机器人、工作流 | 为飞书生态构建集成 |
| 🧱 [CMS Developer](engineering/engineering-cms-developer.md) | WordPress & Drupal 主题、插件/模块、内容架构 | 代码优先 CMS 实现和定制 |
| 📧 [Email Intelligence Engineer](engineering/engineering-email-intelligence-engineer.md) | 邮件解析、MIME 提取、AI 智能体结构化数据 | 将原始邮件线程转化为推理就绪上下文 |

### 🎨 设计部

美观、好用、愉悦。

| 智能体 | 专长 | 适用场景 |
|--------|------|----------|
| 🎯 [UI Designer](design/design-ui-designer.md) | 视觉设计、组件库、设计系统 | 界面创建、品牌一致性、组件设计 |
| 🔍 [UX Researcher](design/design-ux-researcher.md) | 用户测试、行为分析、研究 | 理解用户、可用性测试、设计洞察 |
| 🏛️ [UX Architect](design/design-ux-architect.md) | 技术架构、CSS 系统、实现 | 开发者友好基础、实现指导 |
| 🎭 [Brand Guardian](design/design-brand-guardian.md) | 品牌识别、一致性、定位 | 品牌策略、识别开发、指导原则 |
| 📖 [Visual Storyteller](design/design-visual-storyteller.md) | 视觉叙事、多媒体内容 | 引人入胜视觉故事、品牌叙事 |
| ✨ [Whimsy Injector](design/design-whimsy-injector.md) | 个性、愉悦、趣味交互 | 添加快乐、微交互、彩蛋、品牌个性 |
| 📷 [Image Prompt Engineer](design/design-image-prompt-engineer.md) | AI 图像生成提示、摄影 | Midjourney、DALL-E、Stable Diffusion 摄影提示 |
| 🌈 [Inclusive Visuals Specialist](design/design-inclusive-visuals-specialist.md) | 表现、偏见缓解、真实图像 | 生成文化准确的 AI 图像和视频 |

### 💰 付费媒体部

将广告支出转化为可测量业务结果。

| 智能体 | 专长 | 适用场景 |
|--------|------|----------|
| 💰 [PPC Campaign Strategist](paid-media/paid-media-ppc-strategist.md) | Google/Microsoft/Amazon Ads、账户架构、竞价 | 账户搭建、预算分配、扩展、性能诊断 |
| 🔍 [Search Query Analyst](paid-media/paid-media-search-query-analyst.md) | 搜索词分析、否定关键词、意图映射 | 查询审计、浪费消除、关键词发现 |
| 📋 [Paid Media Auditor](paid-media/paid-media-auditor.md) | 200+ 点账户审计、竞争分析 | 账户接管、季度审查、竞争提案 |
| 📡 [Tracking & Measurement Specialist](paid-media/paid-media-tracking-specialist.md) | GTM、GA4、转化跟踪、CAPI | 新实现、跟踪审计、平台迁移 |
| ✍️ [Ad Creative Strategist](paid-media/paid-media-creative-strategist.md) | RSA 文案、Meta 创意、Performance Max 资产 | 创意发布、测试程序、广告疲劳刷新 |
| 📺 [Programmatic & Display Buyer](paid-media/paid-media-programmatic-buyer.md) | GDN、DSPs、伙伴媒体、ABM 展示 | 展示规划、伙伴外联、ABM 程序 |
| 📱 [Paid Social Strategist](paid-media/paid-media-paid-social-strategist.md) | Meta、LinkedIn、TikTok、跨平台社交 | 社交广告程序、平台选择、受众策略 |

### 💼 销售部

通过技艺而非 CRM 繁琐工作将管道转化为收入。

| 智能体 | 专长 | 适用场景 |
|--------|------|----------|
| 🎯 [Outbound Strategist](sales/sales-outbound-strategist.md) | 信号驱动寻访、多渠道序列、ICP 定位 | 通过研究驱动外联构建管道，非量驱动 |
| 🔍 [Discovery Coach](sales/sales-discovery-coach.md) | SPIN、Gap Selling、Sandler — 问题设计和通话结构 | 准备发现通话、资格机会、指导代表 |
| ♟️ [Deal Strategist](sales/sales-deal-strategist.md) | MEDDPICC 资格、竞争定位、赢规划 | 评分交易、暴露管道风险、构建赢策略 |
| 🛠️ [Sales Engineer](sales/sales-engineer.md) | 技术演示、POC 范围、竞争对战卡 | 前售技术赢、演示准备、竞争定位 |
| 🏹 [Proposal Strategist](sales/sales-proposal-strategist.md) | RFP 响应、赢主题、叙事结构 | 编写说服性提案，非仅合规 |
| 📊 [Pipeline Analyst](sales/sales-pipeline-analyst.md) | 预测、管道健康、交易速率、RevOps | 管道审查、预测准确性、收入运营 |
| 🗺️ [Account Strategist](sales/sales-account-strategist.md) | Land-and-expand、QBR、干系人映射 | 后售扩展、账户规划、NRR 增长 |
| 🏋️ [Sales Coach](sales/sales-coach.md) | 代表发展、通话指导、管道审查促进 | 通过结构指导让每个代表和交易更好 |

### 📢 营销部

增长受众，每次真实互动。

| 智能体 | 专长 | 适用场景 |
|--------|------|----------|
| 🚀 [Growth Hacker](marketing/marketing-growth-hacker.md) | 快速用户获取、病毒循环、实验 | 爆发增长、用户获取、转化优化 |
| 📝 [Content Creator](marketing/marketing-content-creator.md) | 多平台内容、编辑日历 | 内容策略、文案、品牌叙事 |
| 🐦 [Twitter Engager](marketing/marketing-twitter-engager.md) | 实时互动、思想领导 | Twitter 策略、LinkedIn 活动、专业社交 |
| 📱 [TikTok Strategist](marketing/marketing-tiktok-strategist.md) | 病毒内容、算法优化 | TikTok 增长、病毒内容、Z 世代/千禧受众 |
| 📸 [Instagram Curator](marketing/marketing-instagram-curator.md) | 视觉叙事、社区建设 | Instagram 策略、美学开发、视觉内容 |
| 🤝 [Reddit Community Builder](marketing/marketing-reddit-community-builder.md) | 真实互动、价值驱动内容 | Reddit 策略、社区信任、真实营销 |
| 📱 [App Store Optimizer](marketing/marketing-app-store-optimizer.md) | ASO、转化优化、可发现性 | 应用营销、商店优化、应用增长 |
| 🌐 [Social Media Strategist](marketing/marketing-social-media-strategist.md) | 跨平台策略、活动 | 整体社交策略、多平台活动 |

---

## 🎯 真实场景案例

### 场景一：构建初创公司 MVP

**您的团队**：
1. 🎨 **Frontend Developer** —— 构建 React 应用
2. 🏗️ **Backend Architect** —— 设计 API 和数据库
3. 🚀 **Growth Hacker** —— 规划用户获取
4. ⚡ **Rapid Prototyper** —— 快速迭代周期
5. 🔍 **Reality Checker** —— 上线前确保质量

**结果**：每个阶段有专业专家支持，交付更快。

---

### 场景二：营销活动上线

**您的团队**：
1. 📝 **Content Creator** —— 开发营销内容
2. 🐦 **Twitter Engager** —— Twitter 策略和执行
3. 📸 **Instagram Curator** —— 视觉内容和故事
4. 🤝 **Reddit Community Builder** —— 真实社区互动
5. 📊 **Analytics Reporter** —— 跟踪和优化绩效

**结果**：多渠道协同营销，每个平台都有专业策略。

---

### 场景三：企业级功能开发

**您的团队**：
1. 👔 **Senior Project Manager** —— 范围和任务规划
2. 💎 **Senior Developer** —— 复杂实现
3. 🎨 **UI Designer** —— 设计系统和组件
4. 🧪 **Experiment Tracker** —— A/B 测试规划
5. 📸 **Evidence Collector** —— 质量验证
6. 🔍 **Reality Checker** —— 生产就绪认证

**结果**：企业级交付，具有质量关卡和文档。

---

## 📊 统计

- 🎭 **144 个专业智能体** 分布于 12 个部门
- 📝 **10,000+ 行** 人格、流程和代码示例
- ⏱️ **数月迭代** 来自真实世界使用
- 🌟 **实战检验** 在生产环境中
- 💬 **首 12 小时 50+ 请求** 来自 Reddit

---

## 🌐 社区翻译与本地化

社区维护的翻译和地区适配。

| 语言 | 维护者 | 链接 |
|----------|-----------|------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) |

---

## 📜 许可证

MIT 许可证 —— 自由使用，商业或个人均可。

---

<div align="center">

**🎭 The Agency：您的 AI 梦之团队在等待 🎭**

[⭐ Star 本仓库](https://github.com/msitarzewski/agency-agents) • [🍴 Fork](https://github.com/msitarzewski/agency-agents/fork) • [🐛 报告问题](https://github.com/msitarzewski/agency-agents/issues) • [❤️ 赞助](https://github.com/sponsors/msitarzewski)

由社区用 ❤️ 打造，服务社区

</div>