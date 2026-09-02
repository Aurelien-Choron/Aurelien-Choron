# Kia ora, I'm Aurélien 👋

**Data Analyst at Catalina Marketing** — retail, FMCG manufacturers and shopper
marketing data. Relocating to New Zealand.

🇳🇿 **Eligible for a New Zealand Working Holiday Visa** — I can start without sponsorship.
🔎 Open to **Data Analyst / Business Analyst** roles, anywhere in New Zealand.

---

## Why this GitHub doesn't look like my CV

My day job is SQL, Power BI reporting and testing on retail and shopper data. None of it can
be published — it belongs to my employer and its clients.

So I deliberately use this account for the opposite: **what my job doesn't make me
build.** Application architecture, deployment, end-to-end data pipelines, and enough
domain modelling to argue with my own numbers. It's a lab, not a folder of work samples.

If you're looking for evidence of SQL and BI, that's on my CV. What's here is evidence
that I keep building past the brief — and that I finish things. Every project below is
deployed and running, not a notebook that stops at the last cell.

## What's in here

| Project | What it demonstrates | Live |
|---|---|---|
| **[portfolio-dashboard](https://github.com/Aurelien-Choron/portfolio-dashboard)** | Rebuilds positions, P&L and a strategic allocation from raw broker CSV exports — no broker API. Two incompatible export formats reconciled into one journal, weighted-average-cost accounting, live market data, and the risk statistics behind the strategy: volatility, beta, correlations, efficient frontier, stress scenarios. Flask + Plotly, deployed, installable as a PWA. | **[Demo](https://portfolio-dashboard-demo.onrender.com)** |
| **[museme](https://github.com/Aurelien-Choron/museme)** | Music recommender over 3,815 tracks described by 66 audio features, ranked by cosine similarity. A Dash app I first wrote in 2021 and brought back to life on Python 3.12 in 2026 — the migration log is the interesting part. | **[Demo](https://museme-s4u2.onrender.com)** |
| **[trading-bot](https://github.com/Aurelien-Choron/trading-bot)** | A daily autonomous investment agent: market data and news read by an LLM (gpt-oss-120b via Groq), then acted on. Runs are idempotent and automatically replay the market days missed after downtime. | — |

## How I work

- **Every figure traceable to its source.** No invented number: when a live price is
  missing, the app says so and falls back explicitly rather than quietly filling the gap.
- **Commit messages that explain *why*.** A bug fix names the wrong number it produced
  and what the reader would otherwise have seen.
- **Public by design, private by default.** portfolio-dashboard runs on my real
  brokerage data locally and on a fully fictional dataset in production, through the
  same code path — so the project can be open without exposing a single real position.

## Stack

**At work** (can't be shown here) · SQL · Power BI · Excel · automated testing · data pipelines
**In this lab** · Python · pandas · Flask · Dash · Plotly · yfinance · Render · PWA

## Get in touch

💼 **[LinkedIn](https://www.linkedin.com/in/aur%C3%A9lien-choron/)**
