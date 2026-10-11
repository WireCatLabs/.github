# WireCat — your context. Any agent.

WireCat is a local-first context and action layer for AI agents. It gives the agent you already use —
Claude Code, Codex, Cursor, Gemini CLI or any MCP client — your messages, meetings, notes and mail,
with local search, source references and limits you set. What the tools read is kept in a local
database on your machine.

**Start with Telegram:** `npm install -g @wirecat/tg-cli`, then follow the
[five-minute guide](https://wirecat.dev/en/docs/tg). Docs for every tool: [wirecat.dev](https://wirecat.dev).

## Tools

| Tool | What it gives your agent | Install |
| --- | --- | --- |
| [tg](https://github.com/WireCatLabs/tg-cli) | Your whole Telegram account and the Bot API: read, search, reply, MCP server | [![npm](https://img.shields.io/npm/v/@wirecat/tg-cli)](https://www.npmjs.com/package/@wirecat/tg-cli) |
| [max](https://github.com/WireCatLabs/max-cli) | MAX messenger: personal account and Bot API, MCP and skills (docs in Russian) | [![npm](https://img.shields.io/npm/v/@wirecat/max-cli)](https://www.npmjs.com/package/@wirecat/max-cli) |
| [zm](https://github.com/WireCatLabs/zoom-cli) | Zoom meetings and transcripts: local archive, search, read-only MCP | [![npm](https://img.shields.io/npm/v/@wirecat/zoom-cli)](https://www.npmjs.com/package/@wirecat/zoom-cli) |
| [memo](https://github.com/WireCatLabs/cli-memo) | Notes, documents and mail in the same local store, linked to people | [![npm](https://img.shields.io/npm/v/@wirecat/cli-memo)](https://www.npmjs.com/package/@wirecat/cli-memo) |

The tools share one local store, so a question can reach across Telegram, MAX, meetings and notes.

## Building blocks

[cli-messaging](https://github.com/WireCatLabs/cli-messaging) (the shared store, search and messenger
commands), [cli-meetings](https://github.com/WireCatLabs/cli-meetings) (meetings and transcripts),
[cli-tasks](https://github.com/WireCatLabs/cli-tasks), [cli-core](https://github.com/WireCatLabs/cli-core)
(the CLI framework) and [cli-testing](https://github.com/WireCatLabs/cli-testing).

## Get involved

Questions and ideas go to each tool's Discussions; bugs to its issues. Read
[CONTRIBUTING](https://github.com/WireCatLabs/community/blob/main/contributing/README.md) before a pull
request, and report vulnerabilities privately under
[SECURITY](https://github.com/WireCatLabs/community/blob/main/security/README.md).
