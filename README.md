# Requirement Anchor / 需求定锚器

一个帮助整理和撰写需求单的通用 Codex skill。

## 背景 / Background

这个 skill 来源于日常工作中积累的一套个人需求单写作习惯：先理解真实问题，再区分已确认事实、讨论中的方案、待确认事项和后续规划，最后整理成清晰、可执行、可验收的需求。

它不是某个公司的专属流程，也不要求用户完全采用同一套方法。你可以直接使用，也可以根据自己的团队、公司或项目习惯进行修改。

This skill is based on a personal workflow developed through everyday requirement-writing work. It helps turn messy context into clear, appropriately scoped, actionable, and testable requirements.

It is not tied to any specific company or process. Use it as-is, or customize it for your own team, organization, or project.

## 适用场景 / Use Cases

- 根据会议记录、聊天记录、截图或自由描述撰写需求单；
- 梳理产品、运营、后台和技术优化需求；
- 评审和完善已有需求；
- 从讨论内容中提取确认结论、待确认事项和后续规划；
- 在需要时补充开发、测试和实现规划。

It can be used for product, operations, admin-console, and technical-improvement requirements, as well as requirement review and refinement.

## 语言 / Language

支持中文和英文。用户可以直接指定输出语言；如果没有指定，skill 会跟随输入材料的主要语言。

Supports Chinese and English. Specify the desired output language when needed; otherwise, the skill follows the primary language of the input.

## 核心特点 / Key Principles

- 先理解问题，再生成需求；
- 优先依据已确认事实，不把猜测写成结论；
- 对会议转录中的错词和术语进行上下文校正；
- 区分当前交付范围、待确认事项和后续规划；
- 根据需求复杂度选择合适的表达方式，不强制固定模板；
- 输出可供产品、开发和测试共同使用的验收标准。

## 自定义 / Customization

你可以修改 `SKILL.md` 和 `references/` 下的内容，加入自己的需求字段、团队术语、评审规则或输出偏好。建议保留“事实提取”和“不确定性管理”相关规则，以减少需求理解偏差。

You can customize `SKILL.md` and the files under `references/` with your own fields, terminology, review rules, and output preferences. Keeping the fact-extraction and uncertainty-management rules is recommended.

## License

Choose a license that matches how you want others to use and modify this skill.
