# DeepSeek Harness 适配

## 状态
**采用可移植 Markdown Skill + 独立知识文件目录；尚未在用户实际 DeepSeek Harness 发行版本与配置上完成安装测试。**

## 适配方法
- 如使用的 Harness 支持 Agents Skills / `SKILL.md` 目录扫描：把 `.agents/skills/demo-solution-architect/` 放到其已配置的技能搜索路径（路径以目标安装实际配置为准）。
- 若使用自建或定制 Harness：把核心 SKILL.md 注册为该 Harness 的指令/Skill 入口，并保留相对引用文件。
- 不假设任何名为 DeepSeek Harness 的发行版本都具备相同的插件命名、加载机制或固定目录。
- 把 `projects/` 和 `knowledge/` 视为本地持久化文件，仅在开启对应读写工具并获得授权时修改。

## 成本与执行模式
- 默认仅做方案调查及知识微课，不开启浏览器、RPA 或大规模工具循环。
- 检索优先复用历史已验证结论；必要时再联网核查版本相关事实。
- 不调用付费工具，除非有明确允许和必要性。

## 最小验证
用一个 CRM 客户分析案例触发双模式，确认能输出多路径方案、原理微课和模拟知识卡；如果授权持久化写入，再测试一张卡的写入、重复请求时读取与更新。
