# loom-mcp

MCP server metadata for [Loom](https://loom.adviciya.com), a project/task management platform for managing projects, tasks, bugs, defects, clients, and phases from AI assistants.

This repo holds only `server.json` — the MCP descriptor for Loom. It does not contain any Loom application source code.

The entry points at Loom's hosted, remote MCP endpoint (`https://loom.adviciya.com/api/v1/mcp`), which requires a personal access token (generate one from Loom → Settings → MCP) sent as an `Authorization: Bearer <token>` header.

## Publishing / updating

```bash
brew install mcp-publisher
mcp-publisher login github
mcp-publisher publish
```
