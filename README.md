# Xodia for your AI

Connects your own AI to [Xodia](https://xodia.ai), the visual website builder for real code. Xodia's skills load from your Xodia account once you sign in; nothing else is needed here.

## Claude Code

```sh
claude plugin marketplace add shehan979/xodia-skills
claude plugin install xodia@xodia
```

Restart Claude Code, type `/mcp`, choose **xodia** and sign in with your Xodia account. Then:

- `/xodia:build a landing page for my bakery` builds or redesigns a site
- `/xodia:work` listens for the changes you ask for in Xodia and works through them
- `/xodia:fix the menu page looks broken on phones` finds and fixes problems
- `/xodia:review` checks unsaved changes before you save
- `/xodia:seo` improves search and AI search readiness
- `/xodia:speed` makes pages load faster

## Claude app (claude.ai and Claude Desktop)

Settings, Connectors, Add custom connector: `https://staging.xodia.ai/mcp`, then sign in with your Xodia account.

## Other MCP clients

Add a remote MCP server (Streamable HTTP with OAuth) at `https://staging.xodia.ai/mcp`.

Powered by [Zuzo Studio](https://zuzostudio.com).
