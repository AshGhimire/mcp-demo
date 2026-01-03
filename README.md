# MCP Learn

## Installation

Add the following installation step to your MCP configuration:

```json
{
  "mcpServers": {
    "addnumbers": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/AshGhimire/mcp-demo.git",
        "mcp-server"
      ]
    }
  }
}
```
