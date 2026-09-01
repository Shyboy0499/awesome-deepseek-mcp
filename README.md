<h1 align="center">Awesome DeepSeek MCP</h1>

<p align="center">
  <strong>A curated list of MCP servers and tools for DeepSeek</strong><br />
  Hand-picked · Bilingual (English / 中文) · Auto-maintained
</p>

<p align="center">
  <a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a>
</p>

---

A curated collection of **Model Context Protocol (MCP)** servers and tools where **DeepSeek** is the model or the focus — not the harness, not generic MCP. Every entry is verified (repo resolves, carries DeepSeek relevance) and the list is **auto-maintained**: a workflow checks for dead links and renamed repos on every change.

## Contents

- [DeepSeek-API MCP servers](#deepseek-api-mcp-servers) — expose DeepSeek models to any MCP client
- [DeepSeek-powered integrations](#deepseek-powered-integrations) — bridges, delegators, and multi-agent setups
- [Specialized tools](#specialized-tools) — vision, media, and niche DeepSeek MCP servers
- [Contributing](#contributing)

---

## DeepSeek-API MCP servers

_MCP servers that expose DeepSeek's language models to Claude Code, Cursor, Codex, DSH, or any MCP client._

- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) — Model Context Protocol server for DeepSeek's advanced language models.  `⭐350`
- [arizen-dev/deepseek-mcp](https://github.com/arizen-dev/deepseek-mcp) — A tiny MCP stdio server that exposes DeepSeek as a cheap supervised worker for Claude Code, Codex, or any MCP client.  `⭐53`
- [arikusi/deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) — MCP server for DeepSeek V4 (v4-flash, v4-pro, 1M context): chat, reasoning, function calling, thinking mode, and cost tracking.  `⭐17`
- [chew-z/DeepseekMCP](https://github.com/chew-z/DeepseekMCP) — Simple MCP server in Golang to redirect questions to DeepSeek models.  `⭐4`
- [Sheshiyer/deepseek-mcp-with-MoE](https://github.com/Sheshiyer/deepseek-mcp-with-MoE) — DeepSeek MCP server with Mixture-of-Experts routing.  `⭐5`

- [moyu6027/deepseek-MCP-server](https://github.com/moyu6027/deepseek-MCP-server) — Enhances Claude's reasoning by integrating DeepSeek R1's advanced reasoning engine.  `⭐1`
- [xihe-lab/deepseek-mcp-server](https://github.com/xihe-lab/deepseek-mcp-server) — Automates DeepSeek web chat via Playwright browser automation.  `⭐1`
- [deepzhun/deepseek-mcp-server](https://github.com/deepzhun/deepseek-mcp-server) — Small, clean MCP server for the DeepSeek API: V3 generation, chat, and R1 reasoning with visible chain-of-thought.  `⭐1`
- [booleamu/deepseek-mcp-server](https://github.com/booleamu/deepseek-mcp-server) — DeepSeek API MCP server: Chat, Reasoner, FIM, file analysis; supports official API and free web client mode.  `⭐1`
- [shengku2121/deepseek-mcp-server](https://github.com/shengku2121/deepseek-mcp-server) — DeepSeek API as MCP server — cheaper AI inference for Claude Code, Cursor, Windsurf, and any MCP client.  `⭐0`

## DeepSeek-powered integrations

_MCP bridges and delegators that route work to DeepSeek from other agents._

- [fjgbue/claude-delegator-deepseek-mcp](https://github.com/fjgbue/claude-delegator-deepseek-mcp) — MCP server that delegates heavy-token tasks from Claude Code to DeepSeek, Kimi, GLM, Qwen, Grok, or any OpenAI-compatible model.  `⭐57`
- [OwlCodeTech/reasonix-bridge](https://github.com/OwlCodeTech/reasonix-bridge) — Codex ↔ DeepSeek MCP bridge: a multi-agent parallel execution engine.  `⭐7`

## Specialized tools

_Niche DeepSeek MCP servers for specific capabilities._

- [Chuyuxuan0v0/deepseek-mcp-image](https://github.com/Chuyuxuan0v0/deepseek-mcp-image) — Image-recognition MCP server for DeepSeek: lets text-only models "see" images (based on SenseNova 6.8 Flash-Lite).  `⭐4`

## Contributing

Want to add a DeepSeek MCP server? Open a PR with the entry in this format:

```
- [owner/repo](https://github.com/owner/repo) — One-line description.
```

Guidelines:
- The project must be **real, working, and DeepSeek-focused** (the model or the API is DeepSeek).
- Only add new lines — never modify or delete existing entries.
- Add to **both** `README.md` and `README.zh-CN.md` (keep them in sync).
- The automated check validates format, link reachability, and renamed repos.

## License

This list is released under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.
