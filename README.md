# rogue-pal-mcp

**Rogue Development** MCP package for agents.

Rogue PAL MCP - multi-provider tools via pal-mcp-server (uvx)

- Asset Store: https://rogue-dev-studio.github.io/rogue-asset-store/

## Requirements

- `uv` / `uvx` on PATH
- Provider API keys required by PAL

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "pal": {
      "command": "uvx",
      "args": [
        "pal-mcp-server"
      ]
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
