<div align="center">

<img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/logo-dark.png" alt="OpenYak" width="120" />

# OpenYak

**Yak is all you need.**

Your local AI agent — private, powerful, remote-ready.

[Website](https://open-yak.com) &nbsp;|&nbsp; [Download](https://open-yak.com/download) &nbsp;|&nbsp; [Pricing](https://open-yak.com/pricing) &nbsp;|&nbsp; [Changelog](https://open-yak.com/changelog)

</div>

---

OpenYak is an open-source desktop AI agent that brings Claude Code-like agentic capabilities to 100+ models. It runs entirely on your machine — your files, your data, your control.

Built for people who do real work with documents, spreadsheets, and local files, not just chat.

### What it does

- **Agentic Workflows** — Multi-step tool calling with up to 3 layers of sub-agent nesting. It plans, executes, and self-corrects.
- **20+ Built-in Tools** — File read/write/edit, bash execution, glob/grep search, web fetch, artifact rendering, todo management, and more.
- **100+ AI Models** — Access Claude, GPT-4, Gemini, Llama, Mistral and others via OpenRouter. Or bring your own API key.
- **Local-First Privacy** — No cloud storage, no telemetry. Every conversation stays on your machine.
- **Artifact System** — Create and preview React, HTML, SVG, and Mermaid diagrams inline with version history.
- **Remote Access** — Expose your local AI over a secure Cloudflare tunnel, scan a QR code, and continue from your phone.

### Use cases

| Scenario | Example |
|----------|---------|
| **Office Automation** | "Rename and organize all invoices in my Downloads folder by date and vendor." |
| **Data Analysis** | "Parse these 12 Excel files, find anomalies, and export a summary report." |
| **Content & Writing** | "Turn my meeting notes into a polished status update email." |
| **Team Operations** | "Merge these PDFs and CSVs into a weekly brief with action items." |
| **Remote Workflows** | "Start on desktop, continue from my phone via secure tunnel." |

### Tech stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 15, React 19, TypeScript, Tailwind CSS 4, shadcn/ui |
| Backend | Python 3.12+, FastAPI, SQLAlchemy 2.0, SQLite WAL |
| Desktop | Tauri 2 (Rust) |
| LLM | OpenRouter, OpenAI-compatible providers |

### Get started

```bash
# Download the installer from the website
# or build from source:
git clone https://github.com/openyak/desktop.git
cd desktop
npm run dev:all
```

Free tier includes 1M tokens/week. No account required for BYOK mode.

### License

Desktop app is licensed under [AGPL-3.0](https://github.com/openyak/desktop/blob/main/LICENSE).

---

<div align="center">

**[Download OpenYak](https://open-yak.com/download)** &nbsp;&nbsp; — &nbsp;&nbsp; From install to impact in minutes.

</div>
