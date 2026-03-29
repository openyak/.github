<div align="center">

<img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/mascot.png" alt="OpenYak" width="200" />

# OpenYak

**Yak is all you need.**

Your desktop AI agent — private, powerful, personal.

[Website](https://open-yak.com) &nbsp;|&nbsp; [Download](https://open-yak.com/download) &nbsp;|&nbsp; [Pricing](https://open-yak.com/pricing) &nbsp;|&nbsp; [Changelog](https://open-yak.com/changelog)

</div>

---

OpenYak is an open-source desktop AI agent that keeps your data on your machine. Connect to 100+ cloud models, run open-source models locally through Ollama, or use your ChatGPT subscription — your choice. Manage files, analyze data, draft documents, and automate workflows without uploading anything to the cloud.

Built with Tauri 2, Next.js 15, and FastAPI — for people who do real work with documents, spreadsheets, and local files.

### Highlights

- 🔒 **Local-First** — Files, conversations, and memory stay on your device. No cloud storage, no telemetry.
- 🤖 **100+ Models** — Claude Opus 4.6, GPT-4.1, Gemini 3 Flash, DeepSeek V3.2, Llama, Qwen, and more via OpenRouter, 20+ BYOK providers, or fully local with [Ollama](https://ollama.com).
- 💬 **ChatGPT Subscription** — Already paying for ChatGPT? Connect it directly — no extra API costs.
- 🛠️ **20+ Built-in Tools** — File read/write/edit, bash, glob/grep, web fetch/search, code execution, artifact rendering, long-term memory, scheduled tasks, and more.
- 🧠 **7 Agent Modes** — Specialized agents for building, planning, exploring — with multi-step tool calling and sub-agent nesting.
- 💬 **IM Integration** — Connect WhatsApp, Discord, Telegram, Slack, Feishu, Signal, iMessage through OpenClaw.
- 📱 **Remote Access** — Start on desktop, continue on your phone via secure Cloudflare tunnel with QR code.
- ⏰ **Automations** — Cron-based scheduled tasks. Daily digests, weekly reports, automated cleanup.
- 🔌 **MCP Connectors** — Integrate external tools via Model Context Protocol.
- 🎨 **Artifacts** — Create and preview React, HTML, SVG, Mermaid, and PowerPoint inline with version history.

### Use Cases

| Scenario | Example |
|----------|---------|
| **Office Automation** | "Rename and organize all invoices in Downloads by date and vendor." |
| **Data Analysis** | "Parse these 12 Excel files, find anomalies, and export a summary." |
| **Content & Writing** | "Turn my meeting notes into a polished status update email." |
| **Team Operations** | "Merge these PDFs and CSVs into a weekly brief with action items." |
| **IM Integration** | "Summarize unread Telegram messages and draft replies." |
| **Automations** | "Every Monday at 9am, generate a digest from my project folder." |

### Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 15, React 19, TypeScript, Tailwind CSS, MUI, Radix UI |
| Backend | Python 3.12+, FastAPI, SQLAlchemy 2.0, SQLite WAL |
| Desktop | Tauri 2 (Rust) |
| LLM | OpenRouter, Ollama, 20+ OpenAI-compatible providers |
