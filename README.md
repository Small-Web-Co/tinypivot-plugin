# TinyPivot agent plugin

Charts, pivot tables, data grids and Excel exports from CSV, JSON and SQL results, with a live Studio that shows every step. This repository holds the TinyPivot plugin for agent directories and marketplaces; the MCP server it starts is [`@smallwebco/tinypivot-mcp`](https://www.npmjs.com/package/@smallwebco/tinypivot-mcp), developed in [Small-Web-Co/tinypivot](https://github.com/Small-Web-Co/tinypivot).

Documentation: https://tiny-pivot.com/mcp · Support: https://github.com/Small-Web-Co/tinypivot/issues

## Install

| Agent | How |
|---|---|
| Claude Code | `/plugin marketplace add Small-Web-Co/tinypivot-plugin`, then `/plugin install tinypivot@tinypivot` |
| Cursor | Cursor marketplace, or copy this repository to `~/.cursor/plugins/local/tinypivot` |
| Codex | `codex plugin marketplace add Small-Web-Co/tinypivot-plugin` |
| Gemini CLI | `gemini extensions install https://github.com/Small-Web-Co/tinypivot` (the main repository) |
| Antigravity | Antigravity plugin marketplace |
| Any other agent | `npx @smallwebco/tinypivot-mcp@latest init` |

A Pro or Team license key is optional; the free tier works without one.

## Files

| Agent | Files |
|---|---|
| Claude Code | `.claude-plugin/plugin.json`, `.claude-plugin/marketplace.json`, `.mcp.json` |
| Cursor | `.cursor-plugin/plugin.json`, `mcp.json` |
| Codex | `.codex-plugin/plugin.json`, `.agents/plugins/marketplace.json`, `.mcp.json` |
| Antigravity | `plugin.json`, `mcp_config.json` |
| All | `skills/tinypivot/SKILL.md` and the icon in `assets/` |

These files are generated from `packages/mcp` in the main repository by `scripts/sync-plugin-repo.mjs`. Change them there, not here.

## License

See [LICENSE.md](LICENSE.md).
