<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a0000,100:8b0000&height=220&section=header&text=CHETAN%20G&fontSize=70&fontColor=ff3333&fontAlignY=40&desc=DATA%20ENGINEER%20%2F%2F%20ML%20ENGINEER%20%2F%2F%20SYSTEMS%20BUILDER&descAlignY=60&descSize=14&descColor=888888&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=18&pause=800&color=FF3333&center=true&vCenter=true&width=700&lines=import+chetan+as+engineer;engineer.build(pipelines%2C+models%2C+systems);%3E%3E+output%3A+production-ready+code;%3E%3E+status%3A+80%25+working+%7C+20%25+sleeping;%3E%3E+optimizer%3A+caffeine+%2B+obsession)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-ff3333?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d0d)](https://linkedin.com/in/chayvarmaa)
[![Gmail](https://img.shields.io/badge/EMAIL-ff3333?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d0d)](mailto:chetanvarma.g17@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-ff3333?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d0d)](https://github.com/chayvarmaa)

![Profile Views](https://komarev.com/ghpvc/?username=chayvarmaa&color=ff3333&style=flat-square&label=PROFILE+VIEWS)

</div>
```
█████████████████████████████████████████████████████████████████████
█                                                                   █
█   SYSTEM    : Chetan G — Data + ML Engineer                      █
█   BUILD     : BS CS + MS CS @ SIUE — Dec 2025                    █
█   LOCATION  : Frederick, MD                                      █
█   UPTIME    : 80% working // 20% sleeping                        █
█   STATUS    : actively seeking full-time roles                   █
█   SIGNAL    : chetanvarma.g17@gmail.com                          █
█                                                                   █
█   [████████████████████░░░░░] 80% — deep in the build            █
█   [████░░░░░░░░░░░░░░░░░░░░░] 20% — recharging                   █
█                                                                   █
█████████████████████████████████████████████████████████████████████
```

---

<div align="center">

## `> cat /etc/engineer.conf`

</div>
```python
#!/usr/bin/env python3
# chetan.py — system profile

class ChetanG:

    STACK = {
        "languages":    ["Python", "SQL"],
        "ml":           ["scikit-learn", "DBSCAN", "regression",
                         "classification", "time series forecasting"],
        "data":         ["pandas", "numpy", "PostgreSQL", "SQLite",
                         "psycopg2", "SQL window functions"],
        "web":          ["Flask", "FastAPI", "REST APIs", "OAuth2"],
        "infra":        ["Docker", "docker-compose", "Kubernetes",
                         "APScheduler", "Linux"],
        "tools":        ["Git", "VS Code", "Leaflet.js", "Nominatim API"],
    }

    PHILOSOPHY = [
        "Don't just learn tools. Build systems.",
        "Every project is a real problem solved, not a tutorial cloned.",
        "If it doesn't run in Docker, did you even build it?",
        "Data without a pipeline is just noise.",
    ]

    def __repr__(self):
        return "Engineer(type='full-stack-data-ml', status='available')"
```

---

<div align="center">

## `> ls -la ~/projects/`

*9 systems built from scratch. real problems. real data. real code.*

</div>

<table>
<tr>
<td width="50%" valign="top">

### 🗺 PotholeMap
**Geospatial ML · Dockerized · REST API**

City-scale road damage intelligence system. Citizens submit reports with GPS coordinates. A **DBSCAN clustering algorithm** (scikit-learn, haversine metric) groups reports into hotspots automatically — no hardcoded cluster count needed. Priority scoring weights report density (60%) against avg severity (40%) to rank repair zones for city officials.

Built a full **GeoJSON REST API** (`/api/reports`, `/api/clusters`, `/api/stats`) that feeds a **Leaflet.js** interactive map. Address autocomplete powered by OpenStreetMap Nominatim. Entire stack containerized with **Docker + docker-compose** — one command to run.

`Flask` `PostgreSQL` `scikit-learn` `DBSCAN` `Docker` `Leaflet.js` `GeoJSON` `Nominatim`

[→ view repo](https://github.com/chayvarmaa/pothole-map)

</td>
<td width="50%" valign="top">

### ✈ FlightDeal
**Data Pipeline · Time Series · PostgreSQL**

Automated flight price intelligence pipeline. Integrates **Amadeus Flight Offers API** with OAuth2 token caching. Scans 4 departure windows per route to find cheapest options. Stores full price history in PostgreSQL using **SQL window functions** — `LAG()` for price deltas, `AVG() OVER (ROWS BETWEEN)` for 7-point moving averages.

Dashboard renders price trend charts with Chart.js showing actual price vs moving average vs target. **APScheduler** runs price checks every 6 hours automatically. Sends email alerts when any route drops below user-defined target.

`Flask` `PostgreSQL` `Amadeus API` `OAuth2` `APScheduler` `SQL window functions` `Chart.js`

[→ view repo](https://github.com/chayvarmaa/FlightDeal)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🥬 ExpiryBuddy
**OCR Pipeline · NLP · Knowledge Base**

End-to-end grocery receipt processing pipeline. Extracts text from PDFs and images using **pytesseract OCR**. Parses Sam's Club/Walmart product codes like `SPINACHWRAP` and `MMWALNUTS2LB` using a keyword extraction algorithm that tokenizes concatenated codes and matches against a 100+ item food knowledge base.

Implements a **self-learning product dictionary** — when a user corrects a decoded item name, the system saves `code → product` mapping to JSON. Future receipts with the same code resolve instantly. Estimates shelf life by category (produce, dairy, meat, frozen, pantry) and sends automated email alerts via Gmail SMTP.

`Flask` `pytesseract` `PyPDF2` `SQLite` `smtplib` `APScheduler` `regex`

[→ view repo](https://github.com/chayvarmaa/ExpiryBuddy)

</td>
<td width="50%" valign="top">

### 🐛 DebugDiary
**Analytics · Flask · Pattern Detection**

Personal engineering intelligence system. Logs every bug solved with title, description, solution, language, bug type, time spent (minutes), and frustration score (1-10). SQL aggregation queries surface patterns — most common bug types, languages causing the most pain, average resolution time.

Stats dashboard uses `GROUP BY` + `AVG` + `COUNT` to render bar charts showing where time actually goes. The frustration score data alone tells a story no sprint board ever captures.

`Flask` `SQLite` `Jinja2` `SQL aggregation`

[→ view repo](https://github.com/chayvarmaa/debug-diary)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔗 DeadLinkDetective
**Multi-threading · Web Crawling · HTML Reports**

Multi-threaded website crawler that recursively maps an entire domain and identifies every broken link. Uses **ThreadPoolExecutor** for concurrent HTTP requests — checks hundreds of URLs in parallel instead of sequentially. Validates response codes, follows redirects, handles timeouts.

Generates a structured HTML report sorted by HTTP status code with full URL context. Practical tool with real utility — any website owner needs this.

`Python` `requests` `BeautifulSoup` `threading` `concurrent.futures`

[→ view repo](https://github.com/chayvarmaa/Dead-link-detective)

</td>
<td width="50%" valign="top">

### 🗂 FileOrganizer + 😈 RoastMyCode + 📓 MoodJournal

**FileOrganizer** — Rule-based file sorting engine. Watches a directory and auto-organizes files by type, extension, date modified, and size. Uses `pathlib` for cross-platform file operations and `watchdog` for real-time directory monitoring.

**RoastMyCode** — Submits code to OpenAI API and gets brutally honest quality feedback. Identifies bugs, anti-patterns, style violations, and efficiency issues.

**MoodJournal** — CLI mood tracker with SQLite persistence. Tags entries by mood, energy, and notes. Generates trend visualizations with matplotlib showing mood patterns over time.

`Python` `pathlib` `watchdog` `OpenAI API` `SQLite` `matplotlib`

[→ file-organizer](https://github.com/chayvarmaa/file-organizer) · [→ roast-my-code](https://github.com/chayvarmaa/roast-my-code) · [→ mood-journal](https://github.com/chayvarmaa/mood-journal)

</td>
</tr>
</table>

---

<div align="center">

## `> htop — resource monitor`

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=chayvarmaa&show_icons=true&theme=gruvbox&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=ff3333&icon_color=ff3333&text_color=cccccc"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chayvarmaa&layout=compact&langs_count=8&theme=gruvbox&hide_border=true&bg_color=0d0d0d&title_color=ff3333&text_color=cccccc"/>

![GitHub Streak](https://streak-stats.demolab.com?user=chayvarmaa&theme=dark&hide_border=true&background=0d0d0d&ring=ff3333&fire=ff3333&currStreakLabel=ff3333)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=chayvarmaa&theme=react-dark&hide_border=true&area=true&bg_color=0d0d0d&color=ff3333&line=ff3333&point=ffffff)

</div>

---

<div align="center">

## `> df -h — what's installed`

</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=ff3333)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d0d0d?style=for-the-badge&logo=postgresql&logoColor=ff3333)
![Flask](https://img.shields.io/badge/Flask-0d0d0d?style=for-the-badge&logo=flask&logoColor=ff3333)
![FastAPI](https://img.shields.io/badge/FastAPI-0d0d0d?style=for-the-badge&logo=fastapi&logoColor=ff3333)
![Docker](https://img.shields.io/badge/Docker-0d0d0d?style=for-the-badge&logo=docker&logoColor=ff3333)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0d0d0d?style=for-the-badge&logo=kubernetes&logoColor=ff3333)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d0d0d?style=for-the-badge&logo=scikit-learn&logoColor=ff3333)
![Pandas](https://img.shields.io/badge/Pandas-0d0d0d?style=for-the-badge&logo=pandas&logoColor=ff3333)
![NumPy](https://img.shields.io/badge/NumPy-0d0d0d?style=for-the-badge&logo=numpy&logoColor=ff3333)
![Git](https://img.shields.io/badge/Git-0d0d0d?style=for-the-badge&logo=git&logoColor=ff3333)
![Linux](https://img.shields.io/badge/Linux-0d0d0d?style=for-the-badge&logo=linux&logoColor=ff3333)
![SQL](https://img.shields.io/badge/SQL-0d0d0d?style=for-the-badge&logo=postgresql&logoColor=ff3333)

</div>

---
```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   PROCESS REPORT                                                 ║
║                                                                  ║
║   [████████████████████████████████████████░░░░░░░░░]  80%      ║
║    writing code, building systems, pushing commits               ║
║                                                                  ║
║   [████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░]  20%      ║
║    unconscious (sleeping)                                        ║
║                                                                  ║
║   current target  : Data Engineer / ML Engineer                  ║
║   education       : BS CS + MS CS @ SIUE — Dec 2025             ║
║   contact         : chetanvarma.g17@gmail.com                   ║
║                                                                  ║
║   > ready for new opportunities                                  ║
║   > ping me                                                      ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Email](https://img.shields.io/badge/PING%20ME-chetanvarma.g17%40gmail.com-ff3333?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d0d)](mailto:chetanvarma.g17@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b0000,50:1a0000,100:0d0d0d&height=120&section=footer" width="100%"/>

</div>
