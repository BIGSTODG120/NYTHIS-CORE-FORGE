# NYTHIS FORGE COMMAND
### Multi-Agent AI System — Coding + Project Management
**Version: Obsidian Edition**

---

## What Is This

A standalone, single-file HTML application powered by the Claude API. Five specialized AI agents in one command center — built for coding, architecture, auditing, project management, and deployment. No install. No server. No babysitting.

Built by **BIGSTODG** on the NYTHIS standard: webhook-first, no fake logic, no fake success, deployable results only.

---

## Quick Start

1. Open `nythis_forge_command.html` in any modern browser
2. Get your Anthropic API key at [console.anthropic.com](https://console.anthropic.com)
3. Paste your key (`sk-ant-...`) in the top-right field
4. Select your agents, type your task, hit **Run Agents**

That's it.

---

## Deployment Options

### Option 1 — Local File (Instant)
```
Open nythis_forge_command.html in Chrome, Edge, or Firefox.
No server. No install. Works offline except for API calls.
```

### Option 2 — GitHub Pages (Free Hosting)
```
1. Create a GitHub repo
2. Upload nythis_forge_command.html as index.html
3. Go to Settings → Pages → Deploy from branch (main, /root)
4. Your URL: https://yourusername.github.io/your-repo
```

### Option 3 — Render Static Site (Production)
```
1. Create a Render account at render.com
2. New → Static Site
3. Upload nythis_forge_command.html as your root file
4. Build command: (none needed)
5. Publish directory: /
6. Your URL is live in under 60 seconds
```

### Option 4 — Vercel Static (Production)
```
1. Install Vercel CLI: npm i -g vercel
2. Put the HTML file in a folder
3. Run: vercel deploy
4. Done — Vercel hosts it globally
```

### Option 5 — Self-Hosted with Key Protection (Recommended for Teams)
```
Build a Next.js wrapper:
- Create /pages/api/claude.js as a proxy route
- Store ANTHROPIC_API_KEY in environment variables
- Frontend calls /api/claude — key never exposed to clients
- Deploy to Render or Vercel with env var configured
```

---

## The 5 Agents

| Agent | Role |
|---|---|
| **Architect** | System design, tech stack, folder structure, API contracts, data modeling |
| **Coder** | Production-ready code, real wiring, real validation, no fake shells |
| **Auditor** | No-fake audit, dead button detection, security review, structured blockers report |
| **Project Manager** | Pass reports, milestones, readiness estimates, task breakdowns |
| **Deployer** | Render-first deploy instructions, env vars, migrations, health check, smoke test |

---

## Routing Modes

| Mode | Behavior |
|---|---|
| **Auto Route** | Reads your prompt, picks the right agents automatically |
| **Chain Mode** | Runs all selected agents together in sequence |
| **Single Agent** | One agent, full focus |

---

## What Prompts To Run

**Architecture**
- Design a webhook-first n8n automation router with model lanes and structured proposal output
- Build a data model for a freight brokerage tracking system with Prisma
- Design an API contract for a multi-tenant SaaS dashboard

**Coding**
- Write a Next.js API route using Prisma with full validation and typed responses
- Build a local-first AI workflow using n8n and Ollama chat models
- Refactor this component to remove dead buttons and wire all actions to real API calls

**Auditing**
- Audit this project for fake buttons, hardcoded metrics, and missing backend wiring
- Run a no-fake product audit and return critical blockers with fix order
- Review this codebase for localStorage-as-database and TypeScript shortcuts hiding problems

**Project Management**
- Generate a project roadmap with pass reports and readiness estimates
- Create pass 37 report: CRM audit and repair
- Build a milestone breakdown for a NYTHIS CORE FORGE deployment

**Deployment**
- Write Render deployment instructions without GitHub integration
- Generate an env var checklist, health check path, and production smoke test
- Create a deployment readiness checklist for a Next.js + Prisma app on Render

---

## Context Tab

Use the **Context** tab to wire in your project before running:

- **Project Name** — e.g. NYTHIS CORE FORGE
- **Tech Stack** — e.g. Next.js, Prisma, Render, n8n, Ollama
- **Current Pass / Phase** — e.g. Pass 37 — CRM Repair
- **Constraints** — No fake logic. Webhook-first. Approved nodes only. No feature drift.
- **Output Format** — Default, Code only, Pass Report, Audit, or Project Plan

Every agent call carries this context. Sharper context = sharper output.

---

## NYTHIS Standards Baked In

Every agent operates under the NYTHIS mission:
- Webhook-first, workflow-first, business-problem-first
- No fake logic, no dead buttons, no hardcoded metrics
- No feature drift, no workaround hell
- No fake success — real verification only
- Deployable results, not hollow scaffolds

---

## Security Notes

- Your API key is stored only in your browser session — never sent to any server except Anthropic
- The `anthropic-dangerous-direct-browser-access` header is required for direct browser API calls
- For team deployment, proxy the API call through your own backend to protect your key
- Never commit your API key to a public repo

---

## Built By

**Christopher Stodghill (BIGSTODG)**
- Director, TOA Legacy Consulting Services
- CFO, Trucka Brokerage Inc.
- AI Systems Builder — NYTHIS Ecosystem

---

*NYTHIS FORGE COMMAND — Obsidian Edition*
