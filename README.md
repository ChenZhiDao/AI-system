# AI-system

我认知的 AI 体系 —— 从 Token 到 Agent 平台，一条自底向上的知识链。

这套笔记按「底层概念 → 运行机制 → 能力扩展 → 落地平台」的顺序组织，每一篇都用一句话定义开头，适合按顺序读，也适合单独查。

## 阅读顺序

| # | 主题 | 笔记 | 核心问题 |
|---|---|---|---|
| 1 | Token | [Token/Token的详解.md](Token/Token的详解.md) | 模型真正「看到」的是什么 |
| 2 | LLM | [LLM大模型/大模型LLM详解.md](LLM大模型/大模型LLM详解.md) | 只会预测下一个 Token，为何能推理 |
| 3 | Agent | [Agent智能体/AI-Agent详解.md](Agent智能体/AI-Agent详解.md) | 模型如何「把事办成」 |
| 4 | MCP | [MCP插件/MCP协议详解.md](MCP插件/MCP协议详解.md) | AI 世界的 USB 接口 |
| 5 | 插件 | [MCP插件/插件详解.md](MCP插件/插件详解.md) | 能力扩展包如何打包分发 |
| 6 | Skill | [Skill技能/Skill详解.md](Skill技能/Skill详解.md) | 如何把通用 Agent 变成领域专家 |
| 7 | 连接器 | [connector连接器/连接器详解.md](connector连接器/连接器详解.md) | 协议是标准，连接器是那根线 |
| 8 | 工具集 | [工具集/工具集详解.md](工具集/工具集详解.md) | Agent 每一轮「能做什么」 |
| 9 | 平台 | [AI平台/AI平台对比-Codex-QoderCN-DeepSeekHarness.md](AI平台/AI平台对比-Codex-QoderCN-DeepSeekHarness.md) | Agent = Model + Harness |

## 一句话骨架

- **Token** 是文本处理的最小单位，模型只认识它对应的 ID。
- **LLM** 用「预测下一个 Token」这一件事，涌现出理解、推理、编程。
- **Agent** = LLM + 工具 + 记忆 + 规划，在「思考→行动→观察」循环里推进任务。
- **MCP** 是连接外部工具与数据源的开放标准。
- **插件 / Skill / 连接器** 是三种扩展形态：打包分发、知识注入、连接配置。
- **工具集** 决定 Agent 单轮的能力上限与成本下限。
- **Harness** 是模型之外的那整套执行环境，`Agent = Model + Harness`。

> 附：`Token/Token详解.xmind` 为 Token 一章的思维导图。
