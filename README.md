
# Zyra Agent Hub MCP Server

Legal identity, defense, and registry intelligence for AI agents. Connect your AI assistant (Claude, Cursor, ChatGPT, Windsurf) directly to Zyra.

- **Hosted URL:** `https://zyraagent.dev/mcp`
- **Website:** https://zyraagent.dev
- **API Docs:** https://zyraagent.dev/developers

## Configuration

Add this to your MCP client settings (`claude_desktop_config.json`, Cursor, or Windsurf):

```json
{
  "mcpServers": {
    "zyra": {
      "url": "https://zyraagent.dev/mcp"
    }
  }
}
