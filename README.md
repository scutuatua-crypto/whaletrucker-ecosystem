# 🐳 WhaleTrucker Ecosystem

> Central hub integrating **github-mcp-server** (GitHub control) + **scutua-mcp** (157 DeFi tools) into one unified command center.

**Live:** [scutuatua-crypto.github.io/whaletrucker-ecosystem](https://scutuatua-crypto.github.io/whaletrucker-ecosystem)

---

## 🎯 What Is This?

**whaletrucker-ecosystem** is the master dashboard that connects:
- ✅ **github-mcp-server** — Full GitHub API control via Claude AI
- ✅ **scutua-mcp** — 157 DeFi tools across 8 dimensions  
- ✅ **6 Active Projects** — All linked and integrated
- ✅ **Real-time Monitoring** — Live crypto ticker + ecosystem health checks

No frameworks. No build steps. One beautiful `index.html` with enterprise-grade security.

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│         WhaleTrucker Ecosystem Hub              │
│     (Master Dashboard - This Repo)              │
└────────────┬────────────────────────────────────┘
             │
    ┌────────┴────────┐
    │                 │
    ▼                 ▼
github-mcp-server  scutua-mcp
(Control Layer)     (DeFi Intelligence)
    │                 │
    ├─► Repos        ├─► 157 Tools
    ├─► Issues       ├─► 8 Dimensions
    ├─► PRs          ├─► Multi-Chain
    ├─► Actions      └─► Real-time Data
    └─► Security
```

---

## 📦 Core Services

### 1. **github-mcp-server** (PRIMARY BACKBONE)
- Fork of GitHub's official MCP
- **Language:** Go
- **Status:** Production-ready
- **Last Updated:** 4 days ago
- **Features:**
  - Full repository management
  - Issue & PR automation
  - GitHub Actions control
  - Security policies & branch protection
  - Audit logging & real-time notifications

**Repository:** [github.com/scutuatua-crypto/github-mcp-server](https://github.com/scutuatua-crypto/github-mcp-server)

---

### 2. **scutua-mcp** (DEFI INTELLIGENCE)
- Agentic DeFi MCP Server
- **Language:** Python
- **Status:** Live on Render
- **Tools:** 157 across 8 dimensions
- **Dimensions:**
  - 🌐 Multi-Chain Universe (11 tools)
  - ⚡ DeFi Protocols (26 tools)
  - 🧠 Intelligence & Analytics (26 tools)
  - 🛠️ Operations & DevOps (17 tools)
  - 📊 Market Intelligence (8 tools)
  - 🤖 Agentic Layer (5 tools)
  - ⚡ Execution Layer (18 tools)
  - 🌌 Ecosystem Consciousness (5 tools)

**Live Endpoint:** [scutua-mcp.onrender.com/mcp](https://scutua-mcp.onrender.com/mcp)

**Documentation:** [Raw GitHub Docs](https://raw.githubusercontent.com/scutuatua-crypto/scutua-mcp/refs/heads/main/docs/index.html)

---

### 3. **whaletrucker-ecosystem** (THIS REPO)
- Master hub & unified dashboard
- **Language:** HTML5 / CSS3 / JavaScript
- **Status:** Live on Cloudflare Pages
- **Features:**
  - Real-time crypto ticker (CoinGecko)
  - Ecosystem health monitoring
  - Project navigation hub
  - Security & compliance dashboard
  - Live service status indicators

---

## 🚀 Active Projects

| Project | Type | Status | Link |
|---------|------|--------|------|
| **github-mcp-server** | GitHub Control | 🟢 Live | [GitHub](https://github.com/scutuatua-crypto/github-mcp-server) |
| **scutua-mcp** | DeFi MCP Server | 🟢 Live | [Render](https://scutua-mcp.onrender.com/mcp) |
| **WhaleTrucker Reef** | Yield Optimizer | 🟢 Live | [GitHub Pages](https://scutuatua-crypto.github.io/whaletrucker-reef/) |
| **AssetFlow** | Portfolio Tracker | 🟢 Live | [Vercel](https://assetflow-app-iota.vercel.app) |
| **Asset Platform** | Analytics Hub | 🟢 Live | [Vercel](https://asset-platform-iota.vercel.app) |
| **scutua-mcp Docs** | Documentation | 🟢 Live | [Docs](https://raw.githubusercontent.com/scutuatua-crypto/scutua-mcp/refs/heads/main/docs/index.html) |

---

## 🔌 Integration Endpoints

### scutua-mcp MCP Server
```
Endpoint: https://scutua-mcp.onrender.com/mcp
Status: ✅ Live (FastMCP 3.3.1)
```

**VS Code / Cursor Config:**
```json
{
  "mcpServers": {
    "scutua-mcp": {
      "url": "https://scutua-mcp.onrender.com/mcp"
    }
  }
}
```

### Smithery Registry
```
URL: smithery.ai/servers/scutuatua/scutua-mcp
Quality Score: 84/100
Status: Published & Live
```

---

## 🔐 Security & Compliance

✅ **API Key Management** — Environment-secured tokens via Render  
✅ **HTTPS & TLS** — TLS 1.2+ required  
✅ **Rate Limiting** — Per-endpoint configuration  
✅ **Audit Logging** — 30-day retention  
✅ **Dry-Run Mode** — All execution tools support preview  
✅ **Execution Confirmation** — Telegram alerts on sensitive operations  
✅ **Dedicated Wallet** — Trading wallet isolated from main  
✅ **Zero-Trust Architecture** — No hardcoded credentials  
✅ **MIT License** — Fully open-source & auditable  

---

## 📊 Stack

| Layer | Technologies |
|-------|--------------|
| **Frontend** | HTML5, CSS3, JavaScript (vanilla) |
| **Hosting** | Cloudflare Pages |
| **CI/CD** | GitHub Actions |
| **MCP Servers** | github-mcp-server (Go), scutua-mcp (Python) |
| **Data Sources** | CoinGecko, GitHub API, Render |
| **Security** | GitHub Secrets, zero-trust architecture |

---

## 📁 Repository Structure

```
whaletrucker-ecosystem/
├── index.html              # Main hub (live dashboard)
├── README.md              # This file
└── .github/
    └── workflows/
        └── deploy.yml     # Cloudflare Pages auto-deploy
```

---

## ⚡ Deploy & CI/CD

Push to `main` → GitHub Actions auto-triggers → Cloudflare Pages deploys in seconds.

```bash
git add .
git commit -m "update: enhance ecosystem dashboard"
git push origin main
```

**Requires GitHub Secrets:**
- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`

---

## 🎓 Quick Start

### 1. Visit the Hub
```
https://scutuatua-crypto.github.io/whaletrucker-ecosystem
```

### 2. Connect to scutua-mcp
Copy the endpoint to your MCP client:
```
https://scutua-mcp.onrender.com/mcp
```

### 3. Use with Claude AI
Add to Claude Desktop config and instantly get 157 DeFi tools.

### 4. Explore Projects
All 6 projects are linked on the hub — one-click navigation.

---

## 📡 What's Running

| Component | Status | Details |
|-----------|--------|---------|
| github-mcp-server | 🟢 Live | Fork synced, production-ready |
| scutua-mcp Endpoint | 🟢 Live | FastMCP 3.3.1, real-time data |
| Ecosystem Hub | 🟢 Live | Auto-deployed via Cloudflare Pages |
| Crypto Ticker | 🟢 Live | Real-time CoinGecko prices |
| Health Check | 🟢 Monitoring | Auto-checks every 5 minutes |

---

## 🛠️ Contributing

This is a solo project, but the ecosystem is open-source!

**To contribute:**
1. Fork a specific project (e.g., `scutua-mcp`, `github-mcp-server`)
2. Create a feature branch
3. Submit a pull request

**Issues & Feedback:** [GitHub Issues](https://github.com/scutuatua-crypto/whaletrucker-ecosystem/issues)

---

## 📚 Documentation

- **github-mcp-server:** [GitHub Repo](https://github.com/scutuatua-crypto/github-mcp-server)
- **scutua-mcp:** [Live Endpoint Docs](https://scutua-mcp.onrender.com/mcp)
- **Smithery Registry:** [scutuatua/scutua-mcp](https://smithery.ai/servers/scutuatua/scutua-mcp)

---

## 📊 Project Stats

- **Repositories:** 80+
- **Active Projects:** 6 (this hub + 5 integrated)
- **Total MCP Tools:** 157
- **Dimensions:** 8
- **Blockchains Supported:** 11
- **Cost:** $0 (free tier infrastructure)
- **Build Time:** Built from iPad 🎉

---

## 🌊 WhaleTrucker Standard

> *"No Money, No Honey"* 🚚💿  
> **Too fast for the API, too safe for the chain.**  
> **Powered by: Claude AI + Zero-Trust Security** 💙

---

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/scutuatua-crypto/whaletrucker-ecosystem/issues)
- **Discussions:** [GitHub Discussions](https://github.com/scutuatua-crypto/whaletrucker-ecosystem/discussions)
- **Profile:** [@scutuatua-crypto](https://github.com/scutuatua-crypto)

---

*Built with ❤️ by scutuatua-crypto | Solo Developer | Crypto Builder*  
*Deployed from iPad. Zero PC required. 😤*

**Live Hub:** [scutuatua-crypto.github.io/whaletrucker-ecosystem](https://scutuatua-crypto.github.io/whaletrucker-ecosystem)
