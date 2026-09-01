# Contributing to Awesome DeepSeek MCP

Thanks for helping grow the list!

## What belongs here

MCP servers and tools where **DeepSeek** is the model or the focus — e.g. MCP servers that expose DeepSeek models to any agent, or bridges that route work to DeepSeek.

## How to add an entry

1. Fork this repo.
2. Add your entry to the right section in **both** `README.md` and `README.zh-CN.md` (keep them in sync).
3. Use this exact format:
   ```
   - [owner/repo](https://github.com/owner/repo) — One-line description.
   ```
   (Chinese file uses ` —— ` as the separator.)
4. **Only add new lines** — never modify or delete existing entries. Alphabetical order within a section where practical.
5. Open one PR per logical change.

## Quality bar

- The project must be **real, working, and DeepSeek-focused**.
- Descriptions must be **factual** — no hype.
- Prefer the canonical source repo.

## Automated check

Every PR runs an auto-check that validates added lines for:
- **Format** — `- [Name](url) — description.`
- **Dead links** — the URL must resolve.
- **Renamed repos** — the listed name must match the repo's canonical name.

If something fails, the bot posts a comment with exactly what to fix. Push a fix and the check re-runs.
