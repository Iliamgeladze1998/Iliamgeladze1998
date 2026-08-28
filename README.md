<div align="center">

# Ilia Mgeladze

**Python Developer · Web Scraping & Data ETL · Automation Engineer · Security Researcher**

Tbilisi, Georgia 🇬🇪

[![GitHub followers](https://img.shields.io/github/followers/Iliamgeladze1998?label=Followers&style=flat-square&color=blue)](https://github.com/Iliamgeladze1998)
[![GitHub stars](https://img.shields.io/github/stars/Iliamgeladze1998?label=Stars&style=flat-square&color=yellow)](https://github.com/Iliamgeladze1998)

</div>

---

### About Me

I build production-grade data pipelines and automation systems for e-commerce. My work focuses on:

- **Web Scraping at Scale** — Multi-store price monitoring with Playwright, Camoufox, and custom scrapers
- **Data ETL Pipelines** — Scraping → Merging → Google Sheets sync → Real-time Telegram alerts
- **AI Browser Agents** — Automating browser interactions using browser-use, Gemini, and LLM-driven agents
- **Security Research** — Responsible disclosure of exposed credentials in public repositories
- **Workflow Automation** — Scheduled scraping, price change detection, and automated reporting

---

### Tech Stack

<table>
<tr>
<td align="center" width="25%">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

</td>
<td align="center" width="25%">

**Scraping & Browser**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Camoufox](https://img.shields.io/badge/Camoufox-FF6B35?style=flat-square)
![browser-use](https://img.shields.io/badge/browser--use-0066CC?style=flat-square)

</td>
<td align="center" width="25%">

**Data & APIs**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)
![gspread](https://img.shields.io/badge/gspread-4A90D9?style=flat-square)

</td>
<td align="center" width="25%">

**Web & Automation**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram%20Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
</tr>
</table>

---

### Projects

#### [acoustic-server](https://github.com/Iliamgeladze1998/acoustic-server) — Price Comparison Platform

> Production system monitoring **7 music instrument stores** in Georgia. 6 independent scrapers run in parallel `screen` sessions, scraping every 8 hours, merging data, syncing to Google Sheets, and sending real-time Telegram alerts for price changes.

```
Scraper → Excel → Data Merger → Google Sheets → Telegram Alerts
```

- 6 competitor stores tracked (Largo, JinoMusic, Musikis-Saxli, Musicroom, Geovoice, Mireli)
- Automated price change detection with formatted Telegram alerts
- Google Sheets API integration with cosmetic formatting (filters, dropdowns, conditional formatting)
- Headless browser automation with Playwright & Camoufox

#### [review-redirect](https://github.com/Iliamgeladze1998/review-redirect) — QR Review System

> QR code redirect system for acoustic.ge Google Maps reviews. Flask backend with analytics dashboard, tracking user feedback and redirecting to review page.

- QR code generation and redirect logic
- Analytics dashboard with visitor tracking
- Positive/negative feedback routing
- Deployed on Netlify

#### [browser-agent](https://github.com/Iliamgeladze1998/browser-agent) — AI Browser Automation

> Ready-to-use AI browser agent combining browser-use + Google Gemini + headless Chrome via CDP. Give natural language tasks, the agent executes them.

- Natural language task execution
- Headless Chrome via CDP for server environments
- Google Gemini 2.0 Flash as LLM
- Single-file plug-and-play script

#### [acoustic-invoice-generator](https://github.com/Iliamgeladze1998/acoustic-invoice-generator) — Invoice Automation

> Telegram bot for automated invoice generation for acoustic.ge online store.

#### [8-ball-pool-helper](https://github.com/Iliamgeladze1998/8-ball-pool-helper) — Game Assistant

> Chrome extension that draws a transparent practice overlay for 8-ball pool — sketch aim guide lines and visualize cushion-reflection angles.

---

### Open Source Contributions

| Project | PR / Issue | Description | Status |
|---------|------------|-------------|--------|
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | [PR #5310](https://github.com/browser-use/browser-use/pull/5310) | Fix: preserve empty accessibility names with explicit `None` check | ![Open](https://img.shields.io/badge/Open-yellow) |
| [SylphAI-Inc/AdalFlow](https://github.com/SylphAI-Inc/AdalFlow) | [PR #499](https://github.com/SylphAI-Inc/AdalFlow/pull/499) | Fix: strip unsupported params for reasoning models + fix `UnboundLocalError` | ![Open](https://img.shields.io/badge/Open-yellow) |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [PR #6685](https://github.com/crewAIInc/crewAI/pull/6685) | Fix: workspace package count and Python version in CONTRIBUTING.md | ![Closed](https://img.shields.io/badge/Closed-red) |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | [PR #13688](https://github.com/Significant-Gravitas/AutoGPT/pull/13688) | Fix: `ensure_ascii=True` for AGPT_VARIABLES to prevent UnicodeEncodeError | ![Closed](https://img.shields.io/badge/Closed-red) |

---

### Security Research

| Project | Issue | Severity | Status |
|----------|-------|----------|--------|
| [Antony-Figueroa/UNEFA_DASHBOARD](https://github.com/Antony-Figueroa/UNEFA_DASHBOARD) | [#29](https://github.com/Antony-Figueroa/UNEFA_DASHBOARD/issues/29) | 🔴 Critical — Supabase service role key & JWT secret exposed | ![Fix PR Open](https://img.shields.io/badge/Fix%20PR%20Open-yellow) |
| [nurdamiron/helpdesk-backend](https://github.com/nurdamiron/helpdesk-backend) | [#1](https://github.com/nurdamiron/helpdesk-backend/issues/1) | 🔴 Critical — AWS RDS, SMTP & email credentials exposed | ![Open](https://img.shields.io/badge/Open-yellow) |
| [Tuloc27062004/phongkhamVietSmile](https://github.com/Tuloc27062004/phongkhamVietSmile) | [#1](https://github.com/Tuloc27062004/phongkhamVietSmile/issues/1) | 🔴 Critical — Live Supabase DB credentials & admin passwords exposed | ![Open](https://img.shields.io/badge/Open-yellow) |
| [knqwz/gemini-telegram-bot](https://github.com/knqwz/gemini-telegram-bot) | [#1](https://github.com/knqwz/gemini-telegram-bot/issues/1) | 🟠 High — Hardcoded Telegram & Gemini credentials exposed | ![Open](https://img.shields.io/badge/Open-yellow) |

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Iliamgeladze1998&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Iliamgeladze1998&layout=compact&theme=dark&hide_border=true" height="165" />

</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Iliamgeladze1998&theme=dark&hide_border=true" height="165" />
</div>

---

### Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ilia%20Mgeladze-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ilia-mgeladze-4b6b582a7/)
[![Email](https://img.shields.io/badge/Email-iliamgeladze@acoustic.ge-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iliamgeladze@acoustic.ge)
[![GitHub](https://img.shields.io/badge/GitHub-Iliamgeladze1998-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Iliamgeladze1998)

</div>

---

<div align="center">
<i>Building tools that work in production, not just in demos.</i>
</div>
