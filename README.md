# FDE Demo Solution Architect · 多平台 Skill

这是一个平台无关的 FDE 技术方案决策与 IT 知识学习 Skill，核心目录为 [`.agents/skills/demo-solution-architect/`](./.agents/skills/demo-solution-architect/)。

主要功能：① 分析真实 FDE Demo 的不同技术实现路线、选型与最小验证；② 从项目中主动发现新 IT 知识、解释原理、举一反三并形成长期知识卡。

支持目标：Codex、WorkBuddy、Accio Work、DeepSeek Harness。**“支持”指按各平台已公开的 Skill 接口提供适配文件，不代表已经在四个平台完成实机验证。**

## 入口与文档

- [核心 SKILL.md](.agents/skills/demo-solution-architect/SKILL.md)
- [Codex 安装说明](platforms/codex.md)
- [WorkBuddy 安装说明](platforms/workbuddy.md)
- [Accio Work 安装说明](platforms/accio-work.md)
- [DeepSeek Harness 安装说明](platforms/deepseek-harness.md)
- [项目决策模板](.agents/skills/demo-solution-architect/references/decision-record-template.md)
- [IT 知识卡模板](.agents/skills/demo-solution-architect/references/knowledge-card-template.md)

## 使用方式

提出一个业务需求，例如：`用 demo-solution-architect 分析“让 AI 读取 CRM 客户历史订单并提供跟进建议”，同时给出技术学习卡。`

Skill 默认先研究方案，不直接写代码、不修改生产系统。平台所提供的联网、文件读写和授权能力将影响最终执行范围。

## 版本

- v0.3.1：新增四平台安装说明、标准目录结构与统一元数据，沿用 v0.3 项目驱动技术学习能力。
- 原始项目思路及示例以知识内容为主，实际平台导入结果须另行验证。
