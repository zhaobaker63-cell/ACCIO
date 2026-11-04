# Codex 适配

## 状态
**标准目录结构已提供；尚未在用户 Codex 环境中进行实际安装测试。**

## 推荐安装
- 把仓库中的 `.agents/skills/demo-solution-architect/` 整个目录复制到目标项目工作区的 `.agents/skills/demo-solution-architect/`，或安装至当前 Codex 版本支持的用户级 Skills 路径。
- 直接使用该目录中的 `SKILL.md` 作为 Skill 入口，不要只复制本仓库根目录的 README。
- 相关模板保留在同一个 Skill 目录，以便相对路径读取。

## 调用测试
在 Codex 中输入：`使用 demo-solution-architect，评估企业CRM AI客户分析Demo，比较API、只读数据库和文件导出，先做方案并教我3个IT概念，不写代码。`

## 通过标准
1. 能识别 Skill 元数据与使用场景。
2. 能读取相对引用文件，在需要时复用模板。
3. 不直接修改文件或运行代码；输出多路线比较、知识原理和验证标准。
4. 只有具备文件写入授权后才生成归档文件；不将草稿冒充已持久化。

## 限制
具体 Skills 路径和自动发现行为以所用 Codex 客户端/版本为准，需在目标环境确认。此仓库的结构支持规范化移植，不保证所有版本自动启用。
