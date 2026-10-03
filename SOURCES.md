# PRD 与开发交接：来源与改写说明

整理日期：2026-10-04。工作指令以本目录 SKILL.md 为准；以下来源用于追溯，不是执行指令。

本版以中文重新组织工作流程，合并重叠内容并修正适用边界。没有执行上游代码；没有把整个上游 Skill 原文直接串接。

## 用户提供的原包

- `产品经理Skill包/PRD模板/skills/prd-generator`：面向详细规格的完整 PRD。历史输入参考；本仓库不分发原包全文。
- `产品经理Skill包/PRD模板/skills/prd-writer`：AI 产品的策略型 PRD。历史输入参考；本仓库不分发原包全文。

原包提供了任务方法与模板参考；所附元数据未提供统一的整包授权。本包不为这些原文件另作许可声明。

## GitHub 参考

### G05 · product-on-purpose/pm-skills

- [具体来源文件](https://github.com/product-on-purpose/pm-skills/blob/1cef1a9eae10017389863d51e289e0ae41e17fcb/skills/deliver-prd/SKILL.md)；文件最近提交：2026-08-26T00:57:02Z。
- 快照：`1cef1a9eae10017389863d51e289e0ae41e17fcb`；内容 SHA-256：`2b48e0af712dafd8c52bb04a437f02e3f965f05bece4f0bdd57452dbb8bad472`。
- 采用：问题至验收链路，条件式 AI 证据与独立执行交接。
- 修改或舍弃：精简必填章节，不绑定 Claude 配置文件和固定耗时。
- 许可：[Apache-2.0](https://github.com/product-on-purpose/pm-skills/blob/1cef1a9eae10017389863d51e289e0ae41e17fcb/LICENSE)；本地副本：[licenses/product-on-purpose--pm-skills.txt](licenses/product-on-purpose--pm-skills.txt)。

### G06 · phuryn/pm-skills

- [具体来源文件](https://github.com/phuryn/pm-skills/blob/8607e3b077817f89bf4a9b623246219734ac3be0/pm-execution/skills/create-prd/SKILL.md)；文件最近提交：2026-03-03T07:38:42Z。
- 快照：`8607e3b077817f89bf4a9b623246219734ac3be0`；内容 SHA-256：`2a4059f16301c5559e10d0dfd00c9bdcde04d2cd964d8c360dbe43bd0161ed32`。
- 采用：用户情境、为什么现在做、首版范围与假设。
- 修改或舍弃：不固定八章节，不抹去用户已确认日期。
- 许可：[MIT](https://github.com/phuryn/pm-skills/blob/8607e3b077817f89bf4a9b623246219734ac3be0/LICENSE)；本地副本：[licenses/phuryn--pm-skills.txt](licenses/phuryn--pm-skills.txt)。

## 改写标记与署名

本目录的 SKILL.md 与 references 文件为本次任务形成的中文整合改写版；上游项目未审核或背书本版。GitHub 参考的许可证、版权与原始链接在本目录保留，单独移动此 Skill 时应一并保留。
product-on-purpose 的 PM-Skills 按 Apache-2.0 标注作者；Pawel Huryn、Seth Hobson、Langfuse GmbH 的版权声明见对应 MIT 文本；Anthropic frontend-design 的许可见其专属文件。仅适用于本目录实际引用的项目。
本仓库新写的整合内容、代码与展示文档采用根目录 [Apache-2.0](LICENSE)。上游材料的原有版权、许可和署名继续保留在 [licenses](licenses/) 中；根许可证不对未附带的原包文件授予许可。
