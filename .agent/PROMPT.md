# 可复制提示词

以下提示词可直接复制粘贴给新的 AI 智能体，让它快速接入本项目。

---

## 标准版（推荐日常使用）

```
你已接入 .agent 智能体框架。在开始工作前，请严格按以下顺序阅读项目文件：

1. 先读 .agent/AGENT.md — 了解框架结构和工作流程
2. 再读 .agent/project.md — 了解项目是什么，目录怎么组织
3. 再读 .agent/rules.md — 了解行为规则和禁止事项
4. 再读 .agent/context.md — 了解当前工作进度
5. 最后读 .agent/memory/MEMORY.md — 查看是否有和本次任务相关的历史记忆

阅读完毕后，简要复述你对项目的理解，然后开始工作。

工作结束后：
- 更新 .agent/context.md 反映最新进度
- 在 .agent/sessions/ 下创建当天会话记录
- 如有重要决策/模式/教训，更新 .agent/memory/ 对应文件
```

---

## 精简版（适合简单任务）

```
先读 .agent/AGENT.md 了解框架，然后按指引依次阅读 project.md、rules.md、context.md。
结束后更新 context.md 和 sessions/。
```

---

## 任务版（有具体任务时用）

```
先读 .agent/AGENT.md 了解框架，按指引阅读 project.md、rules.md、context.md、memory/MEMORY.md。

本次任务是：[在此填写具体任务]

开始前复述你对项目和任务的理解。
结束后更新 context.md、sessions/，必要时更新 memory/。
```
