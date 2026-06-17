# 📊 Claude Usage Tracker

> A beautiful, local-first dashboard to track your Claude AI sessions, token usage, machine access grants, and permissions — all in one place.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2B%20JS-orange.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)

---

## ✨ Features

- **📊 Dashboard** — Live KPIs: total sessions, estimated tokens, active grants, and promotions
- **🪙 Token Tracker** — Estimated input/output token usage per category with cost calculation (Sonnet pricing)
- **⚖️ Budget & Reset** — Countdown timer to next session reset + visual gauge for token budget
- **🕐 Sessions** — Full searchable/filterable table of all 48 Claude Desktop sessions
- **🖥️ Local Machine** — Active app grants, permission flags, promotions, and access history
- **🔐 Permissions** — Log and manage app-level permissions with tier and status tracking
- **🏷️ Categories** — Auto-classification of sessions into 7 categories with token estimates
- **🌙 Dark Mode** — Full dark/light theme toggle with localStorage persistence

---

## 🗂️ Session Categories

| Category | Emoji | Est. Tokens/Session |
|---|---|---|
| Daily | 📋 | ~400 |
| Technical | ⚙️ | ~4,000 |
| Creative | 🎨 | ~2,500 |
| Management | 📁 | ~2,000 |
| Research | 🔬 | ~3,000 |
| Productivity | ⚡ | ~1,500 |
| Other | 📎 | ~1,000 |

---

## 🚀 Getting Started

### Option 1 — GitHub Pages (Recommended)
Just open the live link:
```
https://hossamk80.github.io/claude-usage-tracker
```

### Option 2 — Run Locally
No build tools needed. Simply open the file in your browser:
```bash
git clone https://github.com/hossamk80/claude-usage-tracker.git
cd claude-usage-tracker
# Open index.html in your browser
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML + CSS + JavaScript |
| Charts | Chart.js 4.5 |
| Storage | localStorage (no backend needed) |
| Hosting | GitHub Pages |

---

## 📸 Screenshots

| Dashboard | Tokens | Sessions |
|---|---|---|
| KPIs + Charts | Budget gauge + breakdown | Searchable full table |

---

## ⚙️ Configuration

### Update Plan Usage
Click **✏️ Edit** on the Plan card → enter values from **Claude → Settings → Usage**

### Set Token Budget
Go to **Tokens → Budget & Reset** → configure your plan limit and session start time

### Log Real Tokens
Go to **Tokens → Overview** → click **"Log Real Tokens"** → enter exact values from your Claude API dashboard

### MCP Integration (Cowork)
If running inside Claude Desktop with Cowork, the dashboard auto-fetches:
- Live session list via `mcp__session_info__list_sessions`
- Active app grants via `mcp__computer-use__list_granted_applications`

---

## 📁 Project Structure

```
claude-usage-tracker/
│
└── index.html        # Single-file app — everything included
```

---

## 🔒 Privacy

All data is stored **locally in your browser** via `localStorage`. Nothing is sent to any server.

---

## 📄 License

MIT License — free to use, modify, and share.

---

## 👤 Author

Built with ❤️ using Claude AI + Cowork  
Tracked across **48 sessions** of real Claude Desktop usage
