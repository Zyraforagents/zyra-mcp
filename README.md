
# Zyra Agent Hub MCP Server

Legal identity, defense, and registry intelligence for AI agents. Connect your AI assistant (Claude, Cursor, ChatGPT, Windsurf) directly to Zyra.

- **Hosted URL:** `https://zyra.wevesti.com/mcp`
- **Website:** https://zyra.wevesti.com
- **API Docs:** https://zyra.wevesti.com/developers

## Configuration

Add this to your MCP client settings (`claude_desktop_config.json`, Cursor, or Windsurf):

```json
{
  "mcpServers": {
    "zyra": {
      "url": "https://zyra.wevesti.com/mcp"
    }
  }
}
