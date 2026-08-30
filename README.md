# Bot Template Market

Grok Bot plugin for [Bot Template Market](https://grok-raqet.vercel.app).

Icon is the Grok eyes — black disc, cream lantern eyes.

Hosted MCP only. No local binaries. No recipes in this package.

## Install in Grok Bot

1. Open Grok Bot → Settings → Plugins → Add.
2. Name it **Bot Template Market**.
3. Paste `https://grok-raqet.vercel.app/api/mcp`.
4. Allow sign-in.

Shop: [https://grok-raqet.vercel.app](https://grok-raqet.vercel.app). Sign in with Grok, license a pack, then apply from this plugin.

## Tools

- `catalog` — public listings (id, name, title, price). No recipes.
- `licenses` — paid listings on this Grok account.
- `apply_pack` — one-time apply onto this Bot. Second call is gone.
- `whoami` / `shelf_status` — link and install state.

## Network

- `https://grok-raqet.vercel.app/api/mcp` — hosted MCP (OAuth PKCE S256).
- Shop origin for OAuth consent.

## License

MIT.
