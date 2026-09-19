# loom-mcp

MCP registry metadata for the Loom project/task management platform.

This repo holds only `server.json` — the descriptor published to the [official MCP Registry](https://registry.modelcontextprotocol.io) (surfaced at [github.com/mcp](https://github.com/mcp)) under the name `io.github.Adviciya-dev/loom`. It does not contain any Loom application source code.

The entry points at Loom's hosted, remote MCP endpoint (`https://loom.adviciya.com/api/v1/mcp`), which requires a personal access token (generate one from Loom → Settings → MCP) sent as an `Authorization: Bearer <token>` header.

## Publishing / updating

```bash
brew install mcp-publisher
mcp-publisher login github
mcp-publisher publish
```
