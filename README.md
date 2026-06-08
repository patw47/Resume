# Patricia Wintrebert

**AI Builder · Agentic Workflow Engineer · Systems That Ship**

📍 Crans-Montana, Switzerland · 🌍 Full Remote  
📧 patricia@wintrebert.ch · 🔗 [LinkedIn](https://linkedin.com/in/patriciawintrebert) · 💻 [GitHub](https://github.com/patw47)

---

## What I Do

I build autonomous systems. Not prototypes — production agents that scan, decide, notify, and act without a human in the loop.

My stack: **Claude API · n8n · OpenClaw · Python · MCP connectors · VPS self-hosted**.  
My default mode: ship first, document after.

15 years in software engineering. 5 years building ML and AI systems in production.  
Currently designing multi-agent pipelines from scratch — architecture, orchestration, scoring logic, deployment.

Trilingual: French (native) · English (fluent) · German (fluent).  
Swiss C permit holder. Available immediately.

📄 [Download CV (PDF)](https://github.com/patw47/Resume/blob/main/PatriciaWintrebert_Resume.pdf)

---

## What I've Shipped

### 🕵️ The Hunter — Autonomous Job Search Agent *(in progress)*
> n8n · Claude API · Indeed MCP · Notion MCP · Google Drive MCP · Telegram Bot API · OpenClaw

Fully autonomous job-hunting pipeline. Scans Indeed + LinkedIn daily, runs two scoring layers (deterministic filter + keyword match rate against a master skills matrix), and notifies via Telegram only when a match exceeds threshold. CV and cover letter generated on validation. Zero manual browsing.

I automated my own job search using n8n + Claude API because applying manually is a solved problem.

---

### 📊 Warren — Autonomous Market Intelligence Agent *(live on VPS)*
> n8n · Claude Haiku · OpenClaw · Python · systemd · GitHub Actions CI/CD · Telegram

Two-layer autonomous market monitoring system running on a self-hosted VPS.

**Layer A — Daily news briefing:** scans 15+ tickers (portfolio + watchlist) every weekday at market close. Claude Haiku runs parallel web searches per ticker, Warren (OpenClaw agent) deduplicates against a rolling per-ticker memory, clusters by sector, and delivers a structured French executive briefing via Telegram. Cost: ~$0.008/day.

**Layer B — EOD anomaly detection *(in progress)*:** statistical price/volume anomaly engine designed to detect idiosyncratic movements *before* the news breaks. MAD-based z-score with a macro market gate (IWM/VIX) to filter systemic risk-off days. Fires Warren only on confirmed idiosyncratic signals — not on beta correlation. Targets micro/small-caps in quantum, nuclear SMR, AI defence, and AR sectors.

**Infra:** three systemd services (n8n, OpenClaw gateway, Python HTTP bridge). Self-hosted GitHub Actions runner for zero-SSH continuous deployment — pushes to `main` auto-deploy, validate, and notify via Telegram.

→ [github.com/patw47/stock-tracker](https://github.com/patw47/stock-tracker)

---

### 📈 SmallCaps Screener — Dockerized Stock Discovery Dashboard *(live)*
> FastAPI · React/Vite · Docker · yfinance · Finviz

Discovers and ranks US small-cap candidates from NASDAQ and Finviz. Applies hard filters, computes a setup score, exposes results via FastAPI consumed by a React frontend. Built for fast visual review before a potential rally.

→ [github.com/patw47/smallcaps-screener](https://github.com/patw47/smallcaps-screener)

---

### 🧠 AI Trading Copilot — Cognitive Architecture *(private)*
> OpenClaw · Claude API · n8n · custom Trade Journal system

Institutional-style cognitive trading architecture. Separates real-time market intelligence, historical pattern analysis, structured reasoning (OpenClaw agents), and behavioral self-review (Trade Journal). Designed to understand context, reason probabilistically, and learn from its own mistakes over time.

*Private repo — details available on request.*

---

## Core Stack

| Domain | Tools |
|---|---|
| **Agentic systems** | OpenClaw, n8n, Claude API (Sonnet + Haiku), MCP |
| **AI / ML** | Python, PyTorch, Transformers, LangChain, RAG, fine-tuning |
| **Backend** | FastAPI, Django, REST APIs, Airflow, Docker |
| **Frontend** | React, Next.js, TypeScript, Vite |
| **Data** | PostgreSQL, pgvector, Qdrant, Pinecone, Pandas |
| **Cloud / Infra** | AWS, Azure, CI/CD, MLOps, GitHub Actions, self-hosted VPS |
| **Orchestration** | n8n, Make, Zapier, Playwright |

---

## Experience

### Data IQ AG — Zug, Switzerland *(07/2023 – Present)*
**ML/AI Lead Engineer · Project Manager**

Built RAG-based AI systems for enterprise clients. Managed delivery end-to-end: requirements → architecture → deployment → client onboarding. Ran remote dev teams. Automated CI/CD pipelines. Deployed on AWS and Azure.

---

### Insight Lab AI — Zug, Switzerland *(07/2023 – Present)*
**ML Engineer · CTO**

Qualitative research platform automating the full workflow from transcription to reporting. Designed the technical architecture. Built AI modules for transcription, anonymization, and text analysis. Managed sprints and offshore development. Deployed on AWS.

---

### InsightSphere — Zurich, Switzerland *(08/2024 – 11/2024)*
**AI Engineer**

AI-powered tools for conversational data analysis.

---

### Women++ — Zurich, Switzerland *(09/2023 – 11/2023)*
**ML Engineer**

Applied ML projects in a collaborative tech environment.

---

## Education

- **Mines ParisTech – PSL** · Master's in Machine Learning Engineering *(2023)*
- **University of Strasbourg** · Bachelor's in Computer Science *(2013)*

---

## Wins

- 🥇 **Deploy Impact Hackathon** — Winner, Zurich (2023)
- 🥈 **Hack'n'Lead Hackathon** — 2nd place, Zurich (2023)
- 🧠 Member, **Mensa Switzerland** & **Intertel**

---

## Languages

🇫🇷 French — Native · 🇬🇧 English — Fluent · 🇩🇪 German — Fluent

---

## Contact

📧 patricia@wintrebert.ch  
🔗 [LinkedIn](https://linkedin.com/in/patriciawintrebert)  
💻 [GitHub](https://github.com/patw47)
