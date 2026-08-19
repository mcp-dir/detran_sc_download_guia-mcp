# Instalação detalhada

DETRAN SC: Guias de Débitos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_sc_download_guia`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_sc_download_guia` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_sc_download_guia` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_sc_download_guia` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_sc_download_guia` (ou `servers.detran_sc_download_guia` no VS Code) do config do cliente e reinicie.
