# Project notes for Claude

## Tools and plugins: free only
- Only install free tools, plugins, MCP servers and connectors.
- If something needs a paid API key or paid plan, say "not free" in one line and skip it. Don't install it or ask about it.
- Free-tier trials that run out (one-time credits) count as not free.

## What's set up
- MCP servers are in `.mcp.json`: Playwright (browser), Kinocut (video editing, needs FFmpeg + uv), DuckDuckGo (web search), Fetch (read web pages), Glyph (code outlines, needs `glyph` installed).
- The HyperFrames plugin (video from HTML) is enabled in `.claude/settings.json`.
- Email, calendar, chat and design apps (Gmail, Google Calendar, Google Drive, Slack, Notion, Canva) are connected by the owner in claude.ai Settings → Connectors, not in this repo.
