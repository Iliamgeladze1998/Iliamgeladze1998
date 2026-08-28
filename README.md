<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d5c5c&height=120&section=header&text=Ilia%20Mgeladze&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>

<br>

<table>
<tr>
<td align="center">

**Senior Backend Engineer**

`Python` · `ETL` · `Distributed Scraping` · `Security`

</td>
<td align="center">

🇬🇪 Tbilisi, Georgia

</td>
</tr>
</table>

<br>

<table>
<tr>
<td align="center" width="33%">
<a href="https://github.com/Iliamgeladze1998?tab=followers">
<img src="https://img.shields.io/badge/Followers-16-blue?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</td>
<td align="center" width="33%">
<a href="https://github.com/Iliamgeladze1998?tab=repositories">
<img src="https://img.shields.io/badge/Repos-11-blue?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</td>
<td align="center" width="33%">
<a href="https://acoustic.ge">
<img src="https://img.shields.io/badge/Company-Acoustic.ge-0d5c5c?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>
</td>
</tr>
</table>

</div>

---

<!-- Animated typing header -->
<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0D5C5C&center=true&vCenter=true&random=false&width=600&lines=Senior+Backend+Engineer;Production+Data+Pipeline+Architect;Distributed+Web+Scraping+at+Scale;AI+Browser+Automation+Engineer;E-commerce+Systems+Builder" alt="Typing SVG" />

</div>

---

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Animated%20Emojis/Objects/Hammer%20and%20Wrench.png" width="28" height="28" /> Tech Stack

<div align="center">

<table>
<tr>
<th>Category</th>
<th>Technologies</th>
</tr>
<tr>
<td align="left"><b>Backend & APIs</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST](https://img.shields.io/badge/REST%20API-FF6C37?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)

</td>
</tr>
<tr>
<td align="left"><b>Scraping & Browser</b></td>
<td>

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Camoufox](https://img.shields.io/badge/Camoufox-FF6B35?style=flat-square)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![browser-use](https://img.shields.io/badge/browser--use-0066CC?style=flat-square)
![CDP](https://img.shields.io/badge/Chrome%20CDP-4285F4?style=flat-square)

</td>
</tr>
<tr>
<td align="left"><b>Data & ETL</b></td>
<td>

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)
![gspread](https://img.shields.io/badge/gspread-4A90D9?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square)

</td>
</tr>
<tr>
<td align="left"><b>Automation & DevOps</b></td>
<td>

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cron](https://img.shields.io/badge/Cron-23B05E?style=flat-square)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![cPanel](https://img.shields.io/badge/cPanel-FF6C2C?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

</td>
</tr>
<tr>
<td align="left"><b>AI & LLM</b></td>
<td>

![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B35?style=flat-square)
![browser-use](https://img.shields.io/badge/browser--use-0066CC?style=flat-square)

</td>
</tr>
</table>

</div>

---

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Animated%20Emojis/Objects/Rocket.png" width="28" height="28" /> Production Systems

<details open>
<summary><b>acoustic-server</b> — Distributed Price Intelligence Platform</summary>

> Production system monitoring **7 music instrument stores** across Georgia. 6 independent scrapers run in parallel `screen` sessions, scraping every 8 hours, merging data, syncing to Google Sheets, and sending real-time Telegram alerts for price changes.

```
┌─────────┐    ┌──────────┐    ┌───────────┐    ┌──────────────┐    ┌───────────────┐
│ Scraper │───▶│ Data ETL │───▶│  Merger   │───▶│ Google Sheets │───▶│ Telegram Bot  │
│  (x6)   │    │ Pipeline │    │ Normalize │    │   (Live API)  │    │  (Alerts)     │
└─────────┘    └──────────┘    └───────────┘    └──────────────┘    └───────────────┘
     │                                                                               │
     ▼                                                                               ▼
┌─────────────┐    ┌──────────────────┐    ┌─────────────────────────────────────────┐
│ Playwright  │    │  Shared Cache    │    │  Circuit Breaker + Rate Limiting         │
│ + Camoufox  │    │  (Single Source) │    │  (Anti-ban protection)                   │
└─────────────┘    └──────────────────┘    └─────────────────────────────────────────┘
```

- **6 competitor stores** tracked (Largo, JinoMusic, Musikis-Saxli, Musicroom, Geovoice, Mireli)
- **Shared cache architecture** — single fetcher, 0 redundant requests to target sites
- **Circuit breaker** — aborts after 5 consecutive failures to avoid IP bans
- **Price change detection** with formatted Telegram alerts
- **Google Sheets API** with conditional formatting, dropdowns, filters
- **Anti-detection** — Camoufox fingerprinting, rate limiting, shared cache layer

</details>

<details>
<summary><b>review-redirect</b> — QR Analytics & Review Funnel</summary>

> QR code redirect system for acoustic.ge Google Maps reviews. Flask backend with real-time analytics dashboard, visitor IP tracking, and sentiment-based routing.

- QR code generation and redirect logic
- Analytics dashboard with visitor tracking (IP, ISP, geo)
- Positive/negative feedback routing
- Deployed on production server with Nginx + SSL

</details>

<details>
<summary><b>browser-agent</b> — LLM-Powered Browser Automation</summary>

> Ready-to-use AI browser agent combining browser-use + Google Gemini + headless Chrome via CDP. Give natural language tasks, the agent executes them.

- Natural language task execution
- Headless Chrome via CDP for server environments
- Google Gemini 2.0 Flash as LLM
- Single-file plug-and-play script

</details>

<details>
<summary><b>acoustic-invoice-generator</b> — Automated Invoice System</summary>

> Telegram bot for automated invoice generation for acoustic.ge online store. Reads product catalog, generates PDF invoices, sends via Telegram.

</details>

<details>
<summary><b>acoustic-smart-filler</b> — AI Product Form Filler</summary>

> Scrape competitor product → AI generates description → Auto-fills admin forms on acoustic.ge. End-to-end automation for product onboarding.

</details>

<details>
<summary><b>8-ball-pool-helper</b> — Chrome Extension</summary>

> Chrome extension that draws a transparent practice overlay for 8-ball pool — sketch aim guide lines and visualize cushion-reflection angles.

</details>

---

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Animated%20Emojis/Objects/Chart%20Increasing.png" width="28" height="28" /> GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Iliamgeladze1998&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true&include_all_commits=true" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Iliamgeladze1998&layout=compact&theme=chartreuse-dark&hide_border=true&langs_count=8" height="170" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Iliamgeladze1998&theme=chartreuse-dark&hide_border=true" height="170" />
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Iliamgeladze1998&theme=chartreuse-dark&hide_border=true&area=true" width="90%"/>

</div>

---

### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Animated%20Emojis/People/Man%20Technologist.png" width="28" height="28" /> Connect

<div align="center">

<a href="https://www.linkedin.com/in/ilia-mgeladze-4b6b582a7/">
<img src="https://img.shields.io/badge/LinkedIn-Ilia%20Mgeladze-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:iliamgeladze@acoustic.ge">
<img src="https://img.shields.io/badge/Email-iliamgeladze@acoustic.ge-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/Iliamgeladze1998">
<img src="https://img.shields.io/badge/GitHub-Iliamgeladze1998-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d5c5c&height=80&section=footer" width="100%"/>

<br>

<i>Building systems that work in production — not just in demos.</i>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Iliamgeladze1998&label=Profile%20Views&color=0d5c5c&style=flat-square" alt="Profile Views" />

</div>
