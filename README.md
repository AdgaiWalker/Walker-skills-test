<div align="center">

# Skills-Walker

把可复用的工作方法沉淀成能直接调用的 AI skill。

[![License](https://img.shields.io/badge/License-MIT-84cc16?style=for-the-badge)](LICENSE)
[![Repo Type](https://img.shields.io/badge/Type-AI%20Skills-2563eb?style=for-the-badge)](#技能索引)
[![Workflow](https://img.shields.io/badge/Workflow-Context%20First-111827?style=for-the-badge)](#使用方式)
[![Roadmap](https://img.shields.io/badge/Roadmap-Active-f59e0b?style=for-the-badge)](ROADMAP.md)

秋知的自创自用 AI 技能库。  
按“我要做什么”组织，而不是按零散提示词或工具名堆目录。

[项目门面生成器](创作/项目门面生成器/) · [ROADMAP](ROADMAP.md) · [CHANGELOG](CHANGELOG.md) · [CONTRIBUTING](CONTRIBUTING.md)

</div>

## 这个仓库是什么

`Skills-Walker` 用来沉淀那些可以长期复用的 AI 工作流。

它不是提示词收集夹，而是把一类任务拆成：

- 什么时候启用
- 先读什么上下文
- 怎么生成结果
- 怎么检查遗漏
- 最后怎么收尾

最终目标是让 AI 更像一个会干活的搭档，而不是一次性对话工具。

## 使用方式

1. 选择一个 skill 目录。
2. 把对应的 `skill.md` 交给你的 AI，或在支持的代理中显式启用该 skill。
3. 让 AI 先利用已有上下文工作；如果上下文不足，再补关键文件。
4. 让 skill 输出可直接使用的结果，而不只是讨论思路。

如果你第一次进入这个仓库，建议先从 [项目门面生成器](创作/项目门面生成器/) 开始。

## 当前推荐

### 项目门面生成器

把项目整理到“能见人、能介绍、能发布”的状态。  
以 `README` 为核心产物，同时补齐安装方式、检查遗漏项，并在最后给出 `LICENSE / Git` 收尾建议。

适合：

- 整个项目完成后，整理仓库首页
- 做完一个模块后，整理阶段性 README
- 已有 README 太散、太空、太像草稿，需要重构
- 技能类项目需要顺带写出安装方式和调用示例

入口：

- [README](创作/项目门面生成器/README.md)
- [skill.md](创作/项目门面生成器/skill.md)

## 技能索引

### OpenClaw

> AI 代理专项工具

| Skill | 状态 | 说明 |
|:------|:----:|:-----|
| [管理](OpenClaw/管理/) | ✅ | OpenClaw 安装、配置、卸载全流程 |
| [网关](OpenClaw/网关/) | 🚧 | AI 代理网关架构 |

### 管理

> 我要理一理

| Skill | 状态 | 说明 |
|:------|:----:|:-----|
| [决策框架](管理/决策框架/) | ✅ | 构建结构化价值决策框架 |
| [文件管理](管理/文件管理/) | ✅ | 个人文件管理体系，规划 / 执行 / 复盘 |

### 创作

> 我要写 / 做东西

| Skill | 状态 | 说明 |
|:------|:----:|:-----|
| [项目门面生成器](创作/项目门面生成器/) | ✅ | 整理项目对外展示所需的 README 与收尾材料 |

### 元能力

> 我要变强

| Skill | 状态 | 说明 |
|:------|:----:|:-----|
| [技能生成](元能力/技能生成/) | ✅ | 将对话提炼为可复用 skill |

## 仓库原则

- 人做决策，AI 做分析与执行
- 先吃上下文，再产出结果
- skill 要能直接用，不做提示词展览
- 按动作意图组织，而不是按工具名硬分类
- 输出结果要能直接交付，而不是停在讨论阶段

## 状态说明

| 标识 | 含义 |
|:----:|:-----|
| ✅ | 可直接使用 |
| 🚧 | 开发中 |
| 📋 | 规划中，见 [ROADMAP.md](ROADMAP.md) |

## 仓库文档

- [ROADMAP.md](ROADMAP.md)：未来扩展方向
- [CHANGELOG.md](CHANGELOG.md)：更新记录
- [CONTRIBUTING.md](CONTRIBUTING.md)：维护规范

## 未来方向

当前仓库以“动作意图”分类，后续会继续扩展：

- 管理：决策、文件、规划、配置
- 创作：文档、脚本、内容
- 自动化：网关、同步、发布
- 元能力：技能生成、工作流优化

详见 [ROADMAP.md](ROADMAP.md)。

## 许可证

[MIT License](LICENSE)
