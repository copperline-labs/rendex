# Rendex

**Rendering API for automation builders and AI agents.** _Render anything. Instantly._

Rendex turns HTML, a URL, or Markdown into images and PDFs with a single, fast API call — built for n8n, Make, Zapier, and AI agents on MCP. PNG, JPEG, WebP, or PDF output, running on Cloudflare's edge with zero cold starts. (Yes, URL screenshots are one mode.)

| | |
|---|---|
| 🌐 **Website** | [rendex.dev](https://rendex.dev) |
| 📚 **Docs** | [rendex.dev/docs](https://rendex.dev/docs) |
| 🔌 **API** | [api.rendex.dev](https://api.rendex.dev) |
| 🆓 **Free tier** | 100 calls/month — [get a key](https://rendex.dev/login) (no credit card) |
| 🟢 **Status** | [rendex.dev/status](https://rendex.dev/status) |

```bash
npm install @copperline/rendex        # JavaScript / TypeScript
pip install rendex                     # Python
npx @copperline/rendex-mcp            # MCP server (AI agents)
```

## What Rendex does

- **Render** HTML, a URL, or Markdown → PNG, JPEG, WebP, or PDF
- **Data templating** — fill `{{placeholders}}` in HTML/Markdown from a JSON object (invoices, reports, certificates)
- **Hosted og:image links** — a signed URL that renders once and caches, for `<meta og:image>`
- **Content extraction** — turn any URL into clean Markdown, JSON, or article HTML
- **Batch** up to 500 URLs per request, async with signed webhooks (Starter+)
- **Device presets, full-page capture, dark mode, geo-targeting** (geo on Pro and up)

## Rendex Watch

**Monitor any URL for changes.** Rendex Watch re-renders a page on a schedule and detects **any change** — a real-Chrome **visual diff** with a highlighted overlay, an extracted-**text diff**, or both (the default, out of the box). Every change leads with a **crop of exactly what changed** and a plain-English **"what changed" summary**, delivered by email (every plan) or a signed webhook (Starter and up) — the webhook payload carries the summary, a cropped image URL, and the normalized change region. It runs on the **same key and credit pool** as the rendering API, and it's available across the REST API, the JS/Python SDKs, the MCP server, and the n8n + Zapier integrations.

→ [rendex.dev/watch](https://rendex.dev/watch) · [Watch docs](https://rendex.dev/docs/watch)

## About this repository

Rendex is a **hosted API** — the core product is closed-source. **This repo is the public feedback front door**, not the API source:

- 🐛 **Found a bug?** [Open a bug report](https://github.com/copperline-labs/rendex/issues/new/choose)
- 💡 **Want a feature?** [Request it here](https://github.com/copperline-labs/rendex/issues/new/choose)
- ❓ **Have a question?** Check the [docs](https://rendex.dev/docs) first, then open an issue or email [support@rendex.dev](mailto:support@rendex.dev)
- 🔒 **Security issue?** See [SECURITY.md](https://github.com/copperline-labs/.github/blob/main/SECURITY.md) — please don't open a public issue.

## Open-source integrations

The product is closed, but the integration tooling is open — contributions welcome:

| Repo | What it is |
|---|---|
| [rendex-mcp](https://github.com/copperline-labs/rendex-mcp) | MCP server — use Rendex from Claude, Cursor, Windsurf, and other AI agents |
| [rendex-n8n](https://github.com/copperline-labs/rendex-n8n) | n8n community node for no-code/low-code workflows |
| [rendex-zapier](https://github.com/copperline-labs/rendex-zapier) | Zapier integration |

Rendex is also available natively on **Make**, **Activepieces**, and **Pipedream**, and from the official **JavaScript** and **Python** SDKs — see [rendex.dev/integrations](https://rendex.dev/integrations).

---

Rendex is a product of [Copperline Labs LLC](https://copperlinelabs.com).

