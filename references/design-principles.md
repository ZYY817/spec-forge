# 设计原则与来源

本 Skill 吸收公开项目的方法，但不复制它们的复杂命令体系。

## Spec Kit

来源：[github/spec-kit](https://github.com/github/spec-kit)

- 先明确要做什么和为什么做，再进入实现方案。
- 规格、计划、任务和实现应保持一致。
- 通过逐步细化和分析减少需求漂移。

## Addy Osmani agent-skills

来源：[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)

- 需求不清时逐步访谈，一次解决一个关键问题。
- Skill 是有步骤、检查点和退出条件的工作流，不是资料堆。
- 通过验证和反跳步规则避免快速生成低质量结果。
- 使用渐进式披露，让主流程保持精简。

## spec_driven_develop

来源：[zhu1090093659/spec_driven_develop](https://github.com/zhu1090093659/spec_driven_develop)

- 让分析、规划、执行、评审和交付形成闭环。
- 复杂任务分阶段推进，并保留可追踪的执行依据。
- 需求文档应服务后续开发，而不是写完即结束。

## 本 Skill 的取舍

- 保留“先理解、再确认、再规划、再实现”的骨架。
- 不强制用户使用固定命令、编号、完整 PRD 或复杂项目流程。
- 把专业流程隐藏在 Skill 内部，让用户看到的是适合当前工作的简洁结果。
- 优先工作需求单；AI Coding、架构和技术规划只在用户需要时展开。
