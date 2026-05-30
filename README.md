# 🐳 WhaleTrucker Ecosystem

> The central hub linking all WhaleTrucker projects, tools, and services.

**Live:** [whaletrucker-ecosystem.pages.dev](https://whaletrucker-ecosystem.pages.dev)

---

## What's This?

A single-page ecosystem hub that maps out the entire WhaleTrucker infrastructure — architecture layers, project links, and MCP integration endpoints. No framework, no build step, just one `index.html`.

---

## Stack

| Layer | Tech |
|---|---|
| Frontend | Pure HTML / CSS / JS |
| Hosting | Cloudflare Pages |
| CI/CD | GitHub Actions |
| MCP Server | [scutua-mcp](https://scutua-mcp.onrender.com/mcp) |

---

## Structure

```
whaletrucker-ecosystem/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## Deploy

Push to `main` → GitHub Actions → Cloudflare Pages auto-deploys.

```bash
git add .
git commit -m "update"
git push origin main
```

Requires two GitHub Secrets:
- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`

---

## Ecosystem Links

- **scutua-mcp** — `https://scutua-mcp.onrender.com/mcp`
- **auth-wiki** — _coming soon_
- **GitHub** — [github.com/whaletrucker](https://github.com/whaletrucker)

---

## Architecture

```
[ Application Layer ]   ecosystem hub · auth-wiki · dashboard
        ↑
[ Platform Layer    ]   scutua-mcp · claude-integration
        ↑
[ Infrastructure    ]   GitHub · Cloudflare Pages · Render
```

---

_Built with 🐳 by WhaleTrucker_
