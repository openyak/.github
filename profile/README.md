<div align="center">

<img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-logo-tight.png" alt="OpenYak" width="240" />

# OpenYak

### Local AI workspace for files, artifacts, and real office workflows

OpenYak helps you turn documents, spreadsheets, decks, PDFs, chats, and local project context into finished deliverables while keeping the workspace on your machine.

[Website](https://open-yak.com) &nbsp;|&nbsp; [Download](https://open-yak.com/download) &nbsp;|&nbsp; [Documentation](https://github.com/openyak/openyak) &nbsp;|&nbsp; [Changelog](https://open-yak.com/changelog)

<br />

<a href="https://github.com/openyak/openyak/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/openyak/openyak/ci.yml?branch=main&style=flat-square&label=CI" alt="CI status" /></a>
<a href="https://github.com/openyak/openyak/releases/latest"><img src="https://img.shields.io/github/v/release/openyak/openyak?style=flat-square" alt="Latest release" /></a>
<a href="https://github.com/openyak/openyak/stargazers"><img src="https://img.shields.io/github/stars/openyak/openyak?style=flat-square" alt="GitHub stars" /></a>
<a href="https://github.com/openyak/openyak/blob/main/LICENSE"><img src="https://img.shields.io/github/license/openyak/openyak?style=flat-square" alt="License" /></a>
<img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="macOS, Windows, and Linux" />

</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-workflow-artifacts.gif" width="900" alt="OpenYak turns uploaded office files into a structured answer and reusable artifact" />
</p>

## Why OpenYak

OpenYak is an open-source desktop agent for people who need AI to work with actual files, not isolated prompts. It combines chat, local tools, artifacts, model choice, and workflow continuity in one desktop workspace.

| What teams need | How OpenYak helps |
|---|---|
| Work from local context | Read and synthesize DOCX, XLSX, PPTX, PDFs, CSVs, folders, and project files. |
| Produce usable outputs | Generate briefs, tables, plans, diagrams, emails, and reusable artifacts in the same thread. |
| Keep data under control | Store conversations, files, memory, and artifacts locally by default. |
| Choose the model path | Use OpenRouter, bring provider keys, connect a ChatGPT subscription, or run local models with Ollama. |
| Continue beyond one prompt | Preserve long-thread context from analysis to planning, revisions, and follow-up work. |

## Product Workflows

### From memo to executive brief

Turn dense notes or office documents into a decision-ready brief with risks, owners, next steps, and a follow-up draft.

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-memo-to-brief.gif" width="900" alt="OpenYak memo to executive brief workflow" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-docx-brief.png" width="900" alt="Close-up of a DOCX memo review result in OpenYak" />
</p>

### From spreadsheet to finance view

Use spreadsheets as working inputs. Ask for variance analysis, forecast risks, anomalies, owner-level action items, and meeting-ready talking points.

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-budget-analysis.png" width="900" alt="Spreadsheet budget analysis result in OpenYak" />
</p>

### From multiple files to an artifact

Synthesize several files in one thread and open a right-side artifact panel for reusable briefs, plans, diagrams, and structured outputs.

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-artifact-panel.png" width="900" alt="OpenYak artifact panel with a multi-file board brief" />
</p>

### Long threads that stay useful

Real work rarely fits in one message. OpenYak is designed for follow-ups, revisions, long context, and clear recovery when something needs attention.

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-auto-compress.gif" width="900" alt="OpenYak long-context auto-compress workflow" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-long-context.png" width="900" alt="OpenYak long thread with preserved context" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/openyak/.github/main/profile/assets/openyak-error-recovery.png" width="900" alt="OpenYak upload error recovery state" />
</p>

## Core Capabilities

| Area | Capabilities |
|---|---|
| File understanding | Office docs, spreadsheets, slide decks, PDFs, CSVs, local folders, and project files. |
| Artifact workspace | Markdown briefs, tables, diagrams, checklists, HTML, React, SVG, Mermaid, and PowerPoint previews. |
| Desktop tools | Read, write, edit, organize, search, and automate files with user-controlled permissions. |
| Model access | OpenRouter, Ollama, ChatGPT subscription, and OpenAI-compatible BYOK providers. |
| Remote and scheduled work | Mobile access through a secure tunnel, recurring automations, and scheduled reporting. |
| Privacy controls | Local storage, local model support, provider choice, and transparent cloud model calls. |

## Built With

| Layer | Technology |
|---|---|
| Desktop | Tauri 2, Rust |
| Frontend | Next.js 15, React 19, TypeScript, Tailwind CSS, MUI, Radix UI |
| Backend | Python 3.12+, FastAPI, SQLAlchemy 2.0, SQLite WAL |
| Integrations | Model Context Protocol, OpenRouter, Ollama, OpenAI-compatible providers |

## Get Started

1. Download the latest OpenYak release for macOS, Windows, or Linux.
2. Connect a model through OpenRouter, your own provider key, ChatGPT subscription, or local Ollama.
3. Attach a real file and ask for a deliverable: a brief, action plan, RACI, email, table, or artifact.
4. Continue in the same thread as the work becomes more specific.

```text
Please read the files I uploaded and turn them into a concise team brief.
Start with three key takeaways, then list risks, owners, and next actions.
Finally, write a follow-up email I can send to the team directly.
```

## Repositories

| Repository | Purpose |
|---|---|
| [openyak/openyak](https://github.com/openyak/openyak) | Main desktop app, frontend, backend, artifacts, and release workflow. |
| [openyak/.github](https://github.com/openyak/.github) | Organization profile and shared GitHub presentation assets. |

## Community

[Discussions](https://github.com/openyak/openyak/discussions) are the best place for questions and product ideas. Use [issues](https://github.com/openyak/openyak/issues) for bugs and reproducible problems.
