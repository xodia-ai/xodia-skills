# Xodia for Claude

[Xodia](https://xodia.ai) is a visual website builder for real code: your site stays a normal Vite and React or plain HTML project in a git repository, with a live preview in Xodia. This plugin connects Claude to your Xodia account so Claude can build pages and sections, change design and content, improve SEO and speed, and fix problems, while you watch the live preview and review every change before saving.

## Install

```sh
claude plugin marketplace add https://app.xodia.ai/plugin/marketplace.json
claude plugin install xodia@xodia
```

Restart Claude Code, type `/mcp`, choose **xodia** and sign in with your Xodia account.

## Commands

- `/xodia:build`: Build or redesign a Xodia website from a description
- `/xodia:work`: Listen for change requests from Xodia and work through them
- `/xodia:animate`: Add interactions and animation to a Xodia site: hover, reveals, scroll effects, page transitions
- `/xodia:content`: Add or change CMS content and collections on a Xodia site: posts, projects, team, drafts
- `/xodia:polish`: Give a Xodia page or component a finishing pass on the small design details
- `/xodia:fix`: Find and fix what's broken in a Xodia preview
- `/xodia:review`: Review a Xodia project's draft changes before saving or publishing
- `/xodia:seo`: Check and improve a Xodia site's SEO and AI search readiness
- `/xodia:speed`: Make a Xodia site load faster

## What this plugin runs and sends

- It runs nothing on your machine. It adds one remote MCP server, `https://app.xodia.ai/mcp`, over HTTPS, and you sign in to it with OAuth.
- Through that server Claude reads and edits files in your Xodia projects, runs checks, reads preview logs, takes preview screenshots and answers requests you send from Xodia. Everything goes only to Xodia, under your account.
- Xodia saves each change as Claude makes it, and you see it at once. Pushing to the git repository you connected and publishing the site happen only when you choose them in Xodia.
- Xodia's working guides (skills) load from your account when Claude needs them.

Support: [xodia.ai](https://xodia.ai). Powered by [Zuzo Studio](https://zuzostudio.com).
