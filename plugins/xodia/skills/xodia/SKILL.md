---
name: xodia
description: "Build or edit a website in Xodia through the xodia MCP tools. Use whenever the user mentions Xodia, a Xodia project, or a request sent from Xodia."
---

# Xodia

Xodia's skills are served to signed-in Xodia users by the `xodia` MCP server.

1. `get_project` for the site: its stack and the stack packs it uses.
2. `get_skill` with `xodia-router`, then every skill and pack it names.
3. Requests from `get_next_request` list their skills and packs; load each with `get_skill`.

Available skills: xodia-router, plan-and-confirm, request-worker, site-builder, create-page, create-section, edit-safely, content-edits, design-system, accessibility, motion-craft, seo-basics, answer-engine, agent-readiness, performance-budget, commit-style, verify-change, review, guardrails, visual-fixer.
