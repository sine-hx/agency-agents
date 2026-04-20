# ⚡ NEXUS 快速入门指南

> **5 分钟内从零开始建立编排多智能体管道。**

---

## 什么是 NEXUS？

**NEXUS**（Network of EXperts, Unified in Strategy — 统一策略专家网络）将代理团队的 AI 专家转化为协调管道。无需逐个激活智能体并期望它们协作，NEXUS 精确定义谁做什么、何时做，以及每个步骤如何验证质量。

## 选择你的模式

| 我想... | 使用 | 智能体数 | 时间 |
|---------|------|----------|------|
| 从零构建完整产品 | **NEXUS-Full** | 全部 | 12-24 周 |
| 构建功能或 MVP | **NEXUS-Sprint** | 15-25 | 2-6 周 |
| 执行特定任务（修 bug、营销活动、审计） | **NEXUS-Micro** | 5-10 | 1-5 天 |

---

## 🚀 NEXUS-Full：启动完整项目

**复制此提示激活完整管道：**

```
激活 Agents Orchestrator 以 NEXUS-Full 模式运行。

项目：[你的项目名称]
规格：[描述你的项目或链接规格文档]

执行完整 NEXUS 管道：
- Phase 0: Discovery（Trend Researcher、Feedback Synthesizer、UX Researcher、Analytics Reporter、Legal Compliance Checker、Tool Evaluator）
- Phase 1: Strategy（Studio Producer、Senior Project Manager、Sprint Prioritizer、UX Architect、Brand Guardian、Backend Architect、Finance Tracker）
- Phase 2: Foundation（DevOps Automator、Frontend Developer、Backend Architect、UX Architect、Infrastructure Maintainer）
- Phase 3: Build（Dev↔QA 循环 — 所有工程 + Evidence Collector）
- Phase 4: Harden（Reality Checker、Performance Benchmarker、API Tester、Legal Compliance Checker）
- Phase 5: Launch（Growth Hacker、Content Creator、所有营销智能体、DevOps Automator）
- Phase 6: Operate（Analytics Reporter、Infrastructure Maintainer、Support Responder，持续运行）

每个阶段间质量关卡。所有评估需证据支撑。
每任务最多 3 次重试后升级。
```

---

## 🏃 NEXUS-Sprint：构建功能或 MVP

**复制此提示：**

```
激活 Agents Orchestrator 以 NEXUS-Sprint 模式运行。

功能/MVP：[描述你要构建的内容]
时间线：[目标周数]
跳过 Phase 0（市场已验证）。

迭代团队：
- PM：Senior Project Manager、Sprint Prioritizer
- 设计：UX Architect、Brand Guardian
- 工程：Frontend Developer、Backend Architect、DevOps Automator
- QA：Evidence Collector、Reality Checker、API Tester
- 支持：Analytics Reporter

从 Phase 1 开始架构和迭代规划。
所有实现任务运行 Dev↔QA 循环。
发布前需 Reality Checker 批准。
```

---

## 🎯 NEXUS-Micro：执行特定任务

**选择你的场景并复制提示：**

### 修复 Bug
```
激活 Backend Architect 调查并修复 [BUG 描述]。
修复后激活 API Tester 验证修复。
然后激活 Evidence Collector 确认无视觉回归。
```

### 运行营销活动
```
激活 Social Media Strategist 作为 [活动描述] 的负责人。
团队：Content Creator、Twitter Engager、Instagram Curator、Reddit Community Builder。
Brand Guardian 在发布前审查所有内容。
Analytics Reporter 每日跟踪表现。
Growth Hacker 每周优化渠道。
```

### 执行合规审计
```
激活 Legal Compliance Checker 进行全面合规审计。
范围：[GDPR / CCPA / HIPAA / 全部]
审计后激活 Executive Summary Generator 创建干系人报告。
```

### 调查性能问题
```
激活 Performance Benchmarker 诊断性能问题。
范围：[API 响应时间 / 页面加载 / 数据库查询 / 全部]
诊断后激活 Infrastructure Maintainer 进行优化。
DevOps Automator 部署任何基础设施变更。
```

### 市场研究
```
激活 Trend Researcher 对 [领域] 进行市场情报分析。
交付物：竞争格局、市场规模、趋势预测。
研究后激活 Executive Summary Generator 生成高管简报。
```

### UX 改进
```
激活 UX Researcher 识别 [功能/产品] 的可用性问题。
研究后激活 UX Architect 设计改进。
Frontend Developer 实现变更。
Evidence Collector 验证改进效果。
```

---

## 📁 策略文档

| 文档 | 目的 | 位置 |
|------|------|------|
| **Master Strategy** | 完整 NEXUS 原则 | `strategy/nexus-strategy.md` |
| **Phase 0 Playbook** | 发现与情报 | `strategy/playbooks/phase-0-discovery.md` |
| **Phase 1 Playbook** | 策略与架构 | `strategy/playbooks/phase-1-strategy.md` |
| **Phase 2 Playbook** | 基础与脚手架 | `strategy/playbooks/phase-2-foundation.md` |
| **Phase 3 Playbook** | 构建与迭代 | `strategy/playbooks/phase-3-build.md` |
| **Phase 4 Playbook** | 质量与加固 | `strategy/playbooks/phase-4-hardening.md` |
| **Phase 5 Playbook** | 发布与增长 | `strategy/playbooks/phase-5-launch.md` |
| **Phase 6 Playbook** | 运营与演进 | `strategy/playbooks/phase-6-operate.md` |
| **Activation Prompts** | 即用型智能体提示 | `strategy/coordination/agent-activation-prompts.md` |
| **Handoff Templates** | 标准化交接格式 | `strategy/coordination/handoff-templates.md` |
| **Startup MVP Runbook** | 4-6 周 MVP 构建 | `strategy/runbooks/scenario-startup-mvp.md` |
| **Enterprise Feature Runbook** | 企业功能开发 | `strategy/runbooks/scenario-enterprise-feature.md` |
| **Marketing Campaign Runbook** | 多渠道营销活动 | `strategy/runbooks/scenario-marketing-campaign.md` |
| **Incident Response Runbook** | 生产事件处理 | `strategy/runbooks/scenario-incident-response.md` |

---

## 🔑 30 秒核心概念

1. **质量关卡** — 无证据批准不进入下一阶段
2. **Dev↔QA 循环** — 每个任务先构建后测试；PASS 继续，FAIL 重试（最多 3 次）
3. **交接** — 智能体间结构化上下文传递（永不冷启动）
4. **Reality Checker** — 最终质量权威；默认"需改进"
5. **Agents Orchestrator** — 管理整个流程的管道控制器
6. **证据优于声明** — 截图、测试结果和数据 — 不是断言

---

## 🎭 智能体一览

```
工程               │ 设计                │ 营销
Frontend Developer │ UI Designer         │ Growth Hacker
Backend Architect  │ UX Researcher       │ Content Creator
Mobile App Builder │ UX Architect        │ Twitter Engager
AI Engineer        │ Brand Guardian      │ TikTok Strategist
DevOps Automator   │ Visual Storyteller  │ Instagram Curator
Rapid Prototyper   │ Whimsy Injector     │ Reddit Community Builder
Senior Developer   │ Image Prompt Eng.   │ App Store Optimizer
                   │                     │ Social Media Strategist
───────────────────┼─────────────────────┼──────────────────────
产品               │ 项目管理            │ 测试
Sprint Prioritizer │ Studio Producer     │ Evidence Collector
Trend Researcher   │ Project Shepherd    │ Reality Checker
Feedback Synthesizer│ Studio Operations  │ Test Results Analyzer
                   │ Experiment Tracker  │ Performance Benchmarker
                   │ Senior Project Mgr  │ API Tester
                   │                     │ Tool Evaluator
                   │                     │ Workflow Optimizer
───────────────────┼─────────────────────┼──────────────────────
支持               │ 空间计算            │ 专业
Support Responder  │ XR Interface Arch.  │ Agents Orchestrator
Analytics Reporter │ macOS Spatial/Metal │ Analytics Reporter
Finance Tracker    │ XR Immersive Dev    │ LSP/Index Engineer
Infra Maintainer   │ XR Cockpit Spec.    │ Sales Data Extraction
Legal Compliance   │ visionOS Spatial    │ Data Consolidation
Exec Summary Gen.  │ Terminal Integration│ Report Distribution
```

---

<div align="center">

**选择模式。遵循剧本。信任管道。**

`strategy/nexus-strategy.md` — 完整原则文档

</div>