# Ahmed Nejm

CEO of **MAQAMI LLC**. MAQAMI is a hotel and flight booking platform with 3M+ hotels: [maqami.co](https://maqami.co)

I build tools that let AI assistants and agents work with travel inventory.

## MAQAMI Travel MCP server

A hosted Model Context Protocol (MCP) server for searching hotels and flights, reading hotel details, and prebooking and booking. Streamable HTTP, no API key.

```bash
claude mcp add --transport http maqami-travel https://mcp.maqami.co/
```

Any MCP client: `{"mcpServers": {"maqami-travel": {"url": "https://mcp.maqami.co/"}}}`

## Repositories

| Repository | What it is |
| --- | --- |
| [mcp-server](https://github.com/negm17111995/mcp-server) | The MAQAMI Travel MCP server: setup for each client, booking flow, Gemini CLI extension and Claude Code plugin |
| [travel-agent-examples](https://github.com/negm17111995/travel-agent-examples) | Runnable travel assistants for the OpenAI Agents SDK, LangChain and the Vercel AI SDK |

Contact: [info@maqami.co](mailto:info@maqami.co)
