<h1 align="center">
  <img src="https://avatars.githubusercontent.com/deepseek-ai" width="64" alt="DeepSeek" /><br />
  Awesome DeepSeek MCP
</h1>

<p align="center">
  <strong>精选的 DeepSeek MCP 服务器与工具清单</strong><br />
  手工筛选 · 中英双语 · 自动维护
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="README.md"><img src="https://img.shields.io/badge/English-EN-3b82f6" alt="English"></a>
</p>

<p align="center">
  <a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a>
</p>

---

精选的 **Model Context Protocol（MCP）** 服务器与工具清单，聚焦于以 **DeepSeek** 为模型或核心的项目——不是 Harness，也不是通用 MCP。每一条目都经过核验（仓库可访问、与 DeepSeek 相关），并且本清单 **自动维护**：每次变更时工作流都会检查失效链接与改名仓库。

## 目录

- [DeepSeek-API MCP 服务器](#deepseek-api-mcp-服务器) — 向任意 MCP 客户端暴露 DeepSeek 模型
- [DeepSeek 驱动的集成](#deepseek-驱动的集成) — 桥接、委派与多智能体方案
- [专用工具](#专用工具)
- [使用 MCP 的 DeepSeek 客户端](#使用-mcp-的-deepseek-客户端) — 使用 MCP 工具的 DeepSeek 优先客户端与 agent
 — 视觉、媒体与特定场景的 DeepSeek MCP 服务器
- [贡献指南](#贡献指南)

---

## DeepSeek-API MCP 服务器

_向 Claude Code、Cursor、Codex、DSH 或任意 MCP 客户端暴露 DeepSeek 语言模型的服务器。_

- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) —— 面向 DeepSeek 高级语言模型的 Model Context Protocol 服务器。  `⭐350`
- [arizen-dev/deepseek-mcp](https://github.com/arizen-dev/deepseek-mcp) —— 一个微型 MCP stdio 服务器，把 DeepSeek 作为廉价受监督 worker 暴露给 Claude Code、Codex 或任意 MCP 客户端。  `⭐53`
- [arikusi/deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) —— 面向 DeepSeek V4（v4-flash、v4-pro、1M 上下文）的 MCP 服务器：聊天、推理、函数调用、思考模式与成本追踪。  `⭐17`
- [chew-z/DeepseekMCP](https://github.com/chew-z/DeepseekMCP) —— 用 Golang 编写的简易 MCP 服务器，将提问转发给 DeepSeek 模型。  `⭐4`
- [Sheshiyer/deepseek-mcp-with-MoE](https://github.com/Sheshiyer/deepseek-mcp-with-MoE) —— 带 Mixture-of-Experts 路由的 DeepSeek MCP 服务器。  `⭐5`

- [moyu6027/deepseek-MCP-server](https://github.com/moyu6027/deepseek-MCP-server) —— 通过集成 DeepSeek R1 的先进推理引擎，增强 Claude 的推理能力。  `⭐1`
- [xihe-lab/deepseek-mcp-server](https://github.com/xihe-lab/deepseek-mcp-server) —— 通过 Playwright 浏览器自动化操作 DeepSeek 网页聊天。  `⭐1`
- [deepzhun/deepseek-mcp-server](https://github.com/deepzhun/deepseek-mcp-server) —— 简洁的 DeepSeek API MCP 服务器：V3 生成、聊天与带可见思维链的 R1 推理。  `⭐1`
- [booleamu/deepseek-mcp-server](https://github.com/booleamu/deepseek-mcp-server) —— DeepSeek API MCP 服务器：聊天、Reasoner、FIM、文件分析；支持官方 API 与免费网页客户端模式。  `⭐1`
- [shengku2121/deepseek-mcp-server](https://github.com/shengku2121/deepseek-mcp-server) —— 将 DeepSeek API 作为 MCP 服务器——为 Claude Code、Cursor、Windsurf 及任意 MCP 客户端提供更廉价的 AI 推理。  `⭐0`

- [newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP](https://github.com/newideas99/Deepseek-Thinking-Claude-3.5-Sonnet-CLINE-MCP) —— 实现 RAT（检索增强思考）的 MCP 服务器，结合 DeepSeek 推理与 Claude。  `⭐116`
- [kamelirzouni/MCP-server-Deepseek_R1](https://github.com/kamelirzouni/MCP-server-Deepseek_R1) —— 将 Claude Desktop 与 DeepSeek R1 连接的 MCP 服务器。  `⭐69`
- [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) —— 向支持 MCP 的 AI 客户端暴露 DeepSeek 推理内容的 MCP 提供方。  `⭐69`
- [HarshJ23/deepseek-claude-MCP-server](https://github.com/HarshJ23/deepseek-claude-MCP-server) —— 将 DeepSeek R1 推理能力集成到 Claude 的 MCP 服务器。  `⭐52`
- [lyumeng/websearch-deepseek](https://github.com/lyumeng/websearch-deepseek) —— 由 DeepSeek API 驱动的网页搜索 MCP 服务器。  `⭐28`

- [dassader/deepseek-mcp](https://github.com/dassader/deepseek-mcp) —— 带浏览器 UI 的 DeepSeek V4 MCP 服务器。  `⭐1`
- [aurelienbran/Deepseek-MCP](https://github.com/aurelienbran/Deepseek-MCP) —— 面向 GitHub 自动化的 DeepSeek R1 32B + MCP 集成。  `⭐1`
## DeepSeek 驱动的集成

_把任务路由给 DeepSeek 的 MCP 桥接与委派工具。_

- [fjgbue/claude-delegator-deepseek-mcp](https://github.com/fjgbue/claude-delegator-deepseek-mcp) —— MCP 服务器，可将高 token 消耗任务从 Claude Code 委派给 DeepSeek、Kimi、GLM、Qwen、Grok 或任意 OpenAI 兼容模型。  `⭐57`
- [OwlCodeTech/reasonix-bridge](https://github.com/OwlCodeTech/reasonix-bridge) —— Codex ↔ DeepSeek MCP 桥接：多智能体并行执行引擎。  `⭐7`

## 专用工具

_面向特定能力的 DeepSeek MCP 服务器。_

- [Chuyuxuan0v0/deepseek-mcp-image](https://github.com/Chuyuxuan0v0/deepseek-mcp-image) —— 面向 DeepSeek 的识图 MCP 服务器：让不支持图片输入的 LLM 也能看图（基于商汤 SenseNova 6.8 Flash-Lite）。  `⭐4`


- [Shaohan-He/deepseek-eyes](https://github.com/Shaohan-He/deepseek-eyes) —— 给 DeepSeek 装上眼睛的 MCP 服务器：剪贴板图片转文字描述（基于通义千问 VL）。  `⭐63`
## 使用 MCP 的 DeepSeek 客户端

_使用 MCP 工具的 DeepSeek 优先客户端与 agent。_

- [zhu1090093659/deepseek-pp](https://github.com/zhu1090093659/deepseek-pp) —— DeepSeek Web 浏览器扩展：带 MCP 工具、记忆、Skills、自动化、网页搜索与对话导出的 AI agent 工作区。  `⭐1756`
- [tigicion/dao-code](https://github.com/tigicion/dao-code) —— 面向 DeepSeek-V4 的开源 TypeScript 终端编码 agent，内置 Skills/MCP/Hooks，兼容 Claude Code 配置。  `⭐1255`

- [usewhale/Whale](https://github.com/usewhale/Whale) —— 面向 DeepSeek 的终端优先 AI 编码 agent：约 98% prompt 缓存命中率、1M 上下文、MCP 工具与动态工作流。  `⭐925`
## 贡献指南

想添加一个 DeepSeek MCP 服务器？提交 PR，条目格式如下：

```
- [owner/repo](https://github.com/owner/repo) —— 一句话描述。
```

规范：
- 项目必须是**真实、可用、以 DeepSeek 为核心**（模型或 API 为 DeepSeek）。
- 只新增行——绝不修改或删除已有条目。
- 同时更新 `README.md` 与 `README.zh-CN.md`（保持同步）。
- 自动检查会校验格式、链接可用性与改名仓库。

## 许可

本清单以 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) 许可发布。
