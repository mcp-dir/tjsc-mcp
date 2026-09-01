# Instalação detalhada

Jurisprudência TJSC é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjsc`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjsc` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjsc` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjsc` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjsc` (ou `servers.tjsc` no VS Code) do config do cliente e reinicie.
