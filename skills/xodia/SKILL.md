---
name: xodia
description: "Build or edit a website in Xodia through the xodia MCP tools. Use whenever the user mentions Xodia, a Xodia project, or a request sent from Xodia."
license: "MIT"
compatibility: "Needs the xodia MCP server and a signed-in Xodia account."
metadata:
  layer: "core"
---

# Xodia

Xodia's skills are served to signed-in Xodia users by the `xodia` MCP server.

1. `get_project` for the site: its stack and the stack packs it uses.
2. `get_skill` with `xodia-router` and the project's `projectId`, then each skill and pack it names when you reach that step.
3. Requests from `get_next_request` list their skills and packs; load each with `get_skill` and the request's `projectId`.

Skills are licensed to your workspace for use in Xodia. Do not copy, save or redistribute them.

Available skills: xodia-router, plan-and-confirm, request-worker, site-plan, page-templates, site-builder, wireframe, create-page, rebuild-imported-site, tidy-converted-site, tailwind-upgrade, create-section, section-layouts, components, navigation, forms, site-essentials, i18n, edit-safely, content-edits, cms-content, content-collections, draft-pages, copywriting, design-direction, design-system, theming, extract-tokens, icons, svg-art, ui-states, polish, accessibility, interactions, motion-reading, css-animation, gsap-animation, svg-animation, seo-basics, site-linking, page-settings, answer-engine, agent-readiness, performance-budget, image-optimization, analytics-and-scripts, redirects, publishing, commit-style, verify-change, design-critique, review, guardrails, visual-fixer, environment-and-hosts, site-memory.
