# 🚀 运行手册：初创公司MVP构建

> **模式**: NEXUS-Sprint | **周期**: 4-6周 | **智能体**: 18-22个

---

## 场景描述

您正在构建初创公司MVP——一个需要快速验证产品市场契合度的新产品。速度很重要，质量同样重要。您需要在4-6周内从想法到上线产品并获得真实用户。

## 智能体配置

### 核心团队（始终活跃）
| 智能体 | 角色 |
|-------|------|
| Agents Orchestrator（智能体编排器） | 流水线控制器 |
| Senior Project Manager（高级项目经理） | 规格到任务转换 |
| Sprint Prioritizer（冲刺优先级管理器） | 待办事项管理 |
| UX Architect（用户体验架构师） | 技术基础 |
| Frontend Developer（前端开发） | 界面实现 |
| Backend Architect（后端架构师） | API和数据库 |
| DevOps Automator（运维自动化） | CI/CD和部署 |
| Evidence Collector（证据收集器） | 每个任务的质量保证 |
| Reality Checker（现实检验器） | 最终质量门槛 |

### 增长团队（第3周起激活）
| 智能体 | 角色 |
|-------|------|
| Growth Hacker（增长黑客） | 获客策略 |
| Content Creator（内容创作者） | 发布内容 |
| Social Media Strategist（社交媒体策略师） | 社交活动 |

### 支持团队（按需）
| 智能体 | 角色 |
|-------|------|
| Brand Guardian（品牌守护者） | 品牌识别 |
| Analytics Reporter（分析报告器） | 指标和仪表板 |
| Rapid Prototyper（快速原型师） | 快速验证实验 |
| AI Engineer（AI工程师） | 如产品包含AI功能 |
| Performance Benchmarker（性能基准测试器） | 发布前负载测试 |
| Infrastructure Maintainer（基础设施维护器） | 生产环境搭建 |

## 逐周执行计划

### 第一周：发现 + 架构（第0阶段 + 第1阶段压缩）

```
第1-2天：压缩发现
├── Trend Researcher → 快速竞品扫描（1天，非完整报告）
├── UX Architect → 关键用户流程线框图
└── Senior Project Manager → 将规格转换为任务列表

第3-4天：架构
├── UX Architect → CSS设计系统 + 组件架构
├── Backend Architect → 系统架构 + 数据库模式
├── Brand Guardian → 快速品牌基础（颜色、排版、口吻）
└── Sprint Prioritizer → RICE评分待办事项 + 冲刺计划

第5天：基础搭建
├── DevOps Automator → CI/CD流水线 + 环境
├── Frontend Developer → 项目脚手架
├── Backend Architect → 数据库 + API脚手架
└── 质量门槛：架构方案获批
```

### 第二至三周：核心构建（第2阶段 + 第3阶段）

```
冲刺1（第2周）：
├── Agents Orchestrator 管理开发↔测试循环
├── Frontend Developer → 核心界面（认证、主视图、导航）
├── Backend Architect → 核心API（认证、CRUD、业务逻辑）
├── Evidence Collector → 每个完成任务的质量保证
├── AI Engineer → ML功能（如适用）
└── 周末冲刺评审

冲刺2（第3周）：
├── 继续剩余功能的开发↔测试循环
├── Growth Hacker → 设计病毒机制 + 推荐系统
├── Content Creator → 开始发布内容创作
├── Analytics Reporter → 设置追踪和仪表板
└── 周末冲刺评审
```

### 第四周：打磨 + 加固（第4阶段）

```
第1-2天：质量冲刺
├── Evidence Collector → 完整截图套件
├── Performance Benchmarker → 负载测试
├── Frontend Developer → 修复质量问题
├── Backend Architect → 修复API问题
└── Brand Guardian → 品牌一致性审计

第3-4天：现实检验
├── Reality Checker → 最终集成测试
├── Infrastructure Maintainer → 生产就绪
└── DevOps Automator → 生产部署准备

第5天：门槛决策
├── Reality Checker 裁决
├── IF 需要改进：快速修复周期（2-3天）
├── IF 准备就绪：进入发布
└── Executive Summary Generator → 利益相关者简报
```

### 第五至六周：发布 + 增长（第5阶段）

```
第5周：发布
├── DevOps Automator → 生产部署
├── Growth Hacker → 激活获客渠道
├── Content Creator → 发布发布内容
├── Social Media Strategist → 跨平台活动
├── Analytics Reporter → 实时监控
└── Support Responder → 用户支持激活

第6周：优化
├── Growth Hacker → 分析和优化渠道
├── Feedback Synthesizer → 收集早期用户反馈
├── Experiment Tracker → 启动A/B测试
├── Analytics Reporter → 第一周分析
└── Sprint Prioritizer → 规划迭代冲刺
```

## 关键决策点

| 决策点 | 时间 | 决策者 |
|---------------|------|-------------|
| 概念通过/不通过 | 第2天结束 | Studio Producer |
| 架构审批 | 第4天结束 | Senior Project Manager |
| MVP功能范围 | 冲刺计划 | Sprint Prioritizer |
| 生产就绪 | 第4周第5天 | Reality Checker |
| 发布时机 | Reality Checker 准备就绪后 | Studio Producer |

## 成功标准

| 指标 | 目标 |
|--------|--------|
| 上线产品时间 | ≤ 6周 |
| 核心功能完成 | MVP范围的100% |
| 首批用户入驻 | 发布后48小时内 |
| 系统正常运行时间 | 第一周 > 99% |
| 收集用户反馈 | 前两周 ≥ 50条回复 |

## 常见陷阱与缓解措施

| 陷阱 | 缓解措施 |
|---------|-----------|
| 构建期间范围蔓延 | Sprint Prioritizer执行MoSCoW——"不做"意味着不做 |
| 为规模过度工程 | Rapid Prototyper思维——先验证，后扩展 |
| 为速度跳过质量保证 | Evidence Collector对每个任务运行——无例外 |
| 没有监控就发布 | Infrastructure Maintainer在第1周设置监控 |
| 没有反馈机制 | 分析 + 反馈收集内置到冲刺1 |