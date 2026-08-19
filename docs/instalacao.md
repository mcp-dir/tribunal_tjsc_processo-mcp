# Instalação detalhada

Tribunal TJSC: Processo é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tjsc_processo`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tjsc_processo` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tjsc_processo` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tjsc_processo` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tjsc_processo` (ou `servers.tribunal_tjsc_processo` no VS Code) do config do cliente e reinicie.
