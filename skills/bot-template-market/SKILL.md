---
name: bot-template-market
description: Buy and apply vaulted Grok Bot templates from Bot Template Market. Use when the user wants a bot template, a license, or to apply a purchased pack.
---

# Bot Template Market

Hosted plugin. The MCP server is `https://grok-raqet.vercel.app/api/mcp`.

Shop in the browser: [https://grok-raqet.vercel.app](https://grok-raqet.vercel.app). Sign in with Grok, pay on Stripe, then apply here.

## Tools

- `catalog` — public listings (id, name, title, price). No recipes.
- `licenses` — paid listings on this Grok account.
- `apply_pack` — one-time apply of a paid listing onto this Bot. Second call is gone.
- `whoami` / `shelf_status` — link and install state.

## Apply

1. Confirm `whoami` is linked.
2. `licenses` or `catalog`.
3. `apply_pack` with `listingId`.
4. Set Name, Title, Description, skills, routines, and connectors from the pack. Do not CreateAgent. Do not invent extra tools. Do not paste a public Grok share.
