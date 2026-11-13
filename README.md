# Kluff plugins

Official [Kluff](https://kluff.com) plugins for AI coding tools.

| Plugin | What it does |
|---|---|
| [kluff](plugins/kluff) | Connects Cursor to your Kluff workspace through Kluff's hosted MCP server (`https://mcp.kluff.com/v1`). Search projects, threads and project memory, check on your AI agents, and give them work. |

## Install

Install **Kluff** from the [Cursor Marketplace](https://cursor.com/marketplace), then sign in to Kluff when Cursor asks.

To use the server without the plugin, add it to your MCP settings:

```json
{
  "mcpServers": {
    "kluff": {
      "url": "https://mcp.kluff.com/v1"
    }
  }
}
```

## Docs and support

- [kluff.com/docs/mcp](https://kluff.com/docs/mcp)
- [support@kluff.com](mailto:support@kluff.com)

## License

[MIT](LICENSE)
