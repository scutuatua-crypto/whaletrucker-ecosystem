# 🧠 CONTEXT.md — WhaleTrucker Ecosystem
> อ่านไฟล์นี้ก่อนทุกครั้ง เพื่อเข้าใจ project ทั้งหมดโดยไม่ต้องอธิบายใหม่

---

## 👤 Owner
- **GitHub:** [@scutuatua-crypto](https://github.com/scutuatua-crypto)
- **Style:** Solo developer, ทำงานจาก iPad เท่านั้น (ไม่มี PC/Mac)
- **Tools:** GitHub Codespaces, Render, GitHub browser
- **Language:** สื่อสารภาษาไทย casual, สั้นๆ เช่น "จัดเลย" "ลุย" = ให้ดำเนินการได้เลย

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│         WhaleTrucker Ecosystem Hub              │
│     (Master Dashboard - whaletrucker-ecosystem) │
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

### อธิบาย Layer
- **whaletrucker-ecosystem** = Master Hub / Dashboard รวมศูนย์ทุกอย่าง
- **github-mcp-server** = Control Layer — ควบคุม 80+ repos ทั้งหมดผ่าน Claude.ai (ใช้ GitHub Integration built-in ของ Claude.ai ไม่ต้อง deploy เอง)
- **scutua-mcp** = DeFi Intelligence — 157 tools, live บน Render

---

## 📦 Repos สำคัญ

| Repo | สถานะ | Hosting | หมายเหตุ |
|------|--------|---------|----------|
| `whaletrucker-ecosystem` | 🟢 Live | Cloudflare Pages | Master Hub |
| `scutua-mcp` | 🟢 Live | Render | 157 DeFi tools, FastMCP Python |
| `github-mcp-server` | 🟡 Fork | — | เก็บไว้ backup, ใช้ built-in Claude.ai แทน |
| `auth-wiki` | 🔴 CI failing | — | ของ logto-io, บอส contribute อยู่ |
| `whaletrucker-reef` | 🟢 Live | GitHub Pages | Yield Optimizer |
| `solana-monitor` | 🟢 Live | — | Solana tracking |
| `vitest` | 🟡 Debugging | — | Fork, กำลัง fix flaky tests |

**Total repos:** 82 ตัว

---

## 🔌 MCP Endpoints

```
scutua-mcp:  https://scutua-mcp.onrender.com/mcp
GitHub:      Built-in Claude.ai Connector (GitHub Integration)
```

---

## 🛠️ scutua-mcp — 8 Dimensions

1. 🌐 Multi-Chain Universe (11 tools)
2. ⚡ DeFi Protocols (26 tools)
3. 🧠 Intelligence & Analytics (26 tools)
4. 🛠️ Operations & DevOps (17 tools)
5. 📊 Market Intelligence (8 tools)
6. 🤖 Agentic Layer (5 tools)
7. ⚡ Execution Layer (18 tools)
8. 🌌 Ecosystem Consciousness (5 tools)

**Language:** Python only — ห้ามใช้ JavaScript/Node.js ใน server code  
**Deploy:** Render auto-deploy เมื่อ push to main  
**File updates:** บอสทำผ่าน GitHub browser บน iPad เท่านั้น

---

## ⚙️ กฎการทำงานกับ Claude

1. **ให้ code เต็มๆ เสมอ** — ห้าม partial diff หรืออ้าง line number
2. **command เดียว** — รวม command ให้ copy ครั้งเดียว (iPad copy หลายบล็อกลำบาก)
3. **Python only** สำหรับ scutua-mcp
4. **ตอบภาษาไทย** casual/friendly
5. **"จัดเลย" / "ลุย"** = ดำเนินการได้เลย ไม่ต้องถามซ้ำ
6. **เช็ค tool จริงก่อน** confirm bug แล้วค่อย fix

---

## 🔥 งานที่กำลังทำอยู่

### 1. auth-wiki CI fix
- **ปัญหา:** `authentication.mdx` ขาด `tags` field ที่ schema require
- **แก้:** เพิ่ม `tags: []` ใน frontmatter
- **ไฟล์:** `src/content/terms/en/authentication.mdx`

### 2. WhaleTrucker Ecosystem Hub
- ทุก repo 80+ ตัวถูกควบคุมผ่าน GitHub Integration (Claude.ai built-in)
- Hub อยู่ที่ `whaletrucker-ecosystem` repo
- README: https://raw.githubusercontent.com/scutuatua-crypto/whaletrucker-ecosystem/refs/heads/main/README.md

---

## 📎 Links สำคัญ

- **Ecosystem Hub:** https://scutuatua-crypto.github.io/whaletrucker-ecosystem
- **scutua-mcp endpoint:** https://scutua-mcp.onrender.com/mcp
- **README raw:** https://raw.githubusercontent.com/scutuatua-crypto/whaletrucker-ecosystem/refs/heads/main/README.md
- **CONTEXT raw:** https://raw.githubusercontent.com/scutuatua-crypto/whaletrucker-ecosystem/refs/heads/main/CONTEXT.md

---

## 🌊 WhaleTrucker Standard

> *"No Money, No Honey"* 🚚  
> Built from iPad. Zero PC required. Powered by Claude AI + Zero-Trust Security 💙
