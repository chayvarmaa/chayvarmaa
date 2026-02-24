<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a0000,100:8b0000&height=220&section=header&text=CHETAN%20G&fontSize=70&fontColor=ff3333&fontAlignY=40&desc=DATA%20ENGINEER%20%2F%2F%20ML%20ENGINEER%20%2F%2F%20SYSTEMS%20BUILDER&descAlignY=60&descSize=14&descColor=888888&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=18&pause=800&color=FF3333&center=true&vCenter=true&width=700&lines=import+chetan+as+engineer;engineer.build(pipelines%2C+models%2C+systems);output%3A+production-ready+code;status%3A+80%25+working+%7C+20%25+sleeping;optimizer%3A+caffeine+%2B+obsession)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-ff3333?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d0d)](https://linkedin.com/in/chayvarmaa)
[![Gmail](https://img.shields.io/badge/EMAIL-ff3333?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d0d)](mailto:chetanvarma.g17@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-ff3333?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d0d)](https://github.com/chayvarmaa)

![Profile Views](https://komarev.com/ghpvc/?username=chayvarmaa&color=ff3333&style=flat-square&label=PROFILE+VIEWS)

</div>

---

<img align="right" alt="coding" width="340" src="https://media.tenor.com/rePDfDWO3XoAAAAd/hacking.gif"/>

### whoami
```python
chetan = {
    "degree":      "BS CS + MS CS @ SIUE",
    "graduating":  "December 2025",
    "seeking":     ["Data Engineer", "ML Engineer"],
    "location":    "Frederick, MD",
    "philosophy":  "Don't just learn tools. Build systems.",
    "uptime": {
        "working":  "80%  ████████████████░░░░",
        "sleeping": "20%  ████░░░░░░░░░░░░░░░░",
    }
}
```

<br clear="right"/>

---

### cat /etc/stack.conf

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

### ls ~/projects/

> 9 systems built from scratch. real problems. real data. real code.

<table>
<tr>
<td width="50%" valign="top">

**🗺 [PotholeMap](https://github.com/chayvarmaa/pothole-map)**
`geospatial ML · dockerized · REST API`

City-scale road damage intelligence system. Citizens submit reports with GPS coordinates. DBSCAN clustering (scikit-learn, haversine metric) groups reports into hotspots automatically — no hardcoded cluster count. Priority scoring weights report density (60%) against avg severity (40%) to rank repair zones for city officials.

Full GeoJSON REST API feeds a Leaflet.js interactive map. Address autocomplete via OpenStreetMap Nominatim. Entire stack containerized with Docker + docker-compose.

`Flask` `PostgreSQL` `scikit-learn` `Docker` `Leaflet.js`

</td>
<td width="50%" valign="top">

**✈ [FlightDeal](https://github.com/chayvarmaa/FlightDeal)**
`data pipeline · time series · PostgreSQL`

Automated flight price intelligence pipeline. Integrates Amadeus Flight Offers API with OAuth2 token caching. Scans 4 departure windows per route to find cheapest options. Stores full price history using SQL window functions — LAG() for price deltas, AVG() OVER (ROWS BETWEEN) for 7-point moving averages.

Dashboard renders price trend charts. APScheduler runs price checks every 6 hours. Sends email alerts when routes drop below target price.

`Flask` `PostgreSQL` `Amadeus API` `OAuth2` `APScheduler`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🥬 [ExpiryBuddy](https://github.com/chayvarmaa/ExpiryBuddy)**
`OCR pipeline · knowledge base · NLP`

End-to-end grocery receipt processing pipeline. Extracts text from PDFs and images using pytesseract OCR. Decodes Sam's Club product codes like SPINACHWRAP using keyword extraction that tokenizes concatenated codes against a 100+ item food knowledge base.

Self-learning product dictionary — corrected items saved permanently. Estimates shelf life by category and sends automated email alerts before food expires.

`Flask` `pytesseract` `PyPDF2` `SQLite` `smtplib` `regex`

</td>
<td width="50%" valign="top">

**🐛 [DebugDiary](https://github.com/chayvarmaa/debug-diary)**
`analytics · flask · pattern detection`

Personal engineering intelligence system. Logs every bug solved with language, bug type, time spent, and frustration score (1-10). SQL aggregation surfaces patterns — most common bug types, languages causing most pain, average resolution time.

Stats dashboard uses GROUP BY + AVG + COUNT to render bar charts showing where engineering time actually goes.

`Flask` `SQLite` `Jinja2` `SQL aggregation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔗 [DeadLinkDetective](https://github.com/chayvarmaa/Dead-link-detective)**
`multi-threading · web crawling`

Multi-threaded website crawler that recursively maps an entire domain and identifies every broken link. Uses ThreadPoolExecutor for concurrent HTTP requests — checks hundreds of URLs in parallel. Validates response codes, follows redirects, handles timeouts. Generates structured HTML report sorted by HTTP status code.

`Python` `requests` `BeautifulSoup` `threading`

</td>
<td width="50%" valign="top">

**🗂 [FileOrganizer](https://github.com/chayvarmaa/file-organizer) · 😈 [RoastMyCode](https://github.com/chayvarmaa/roast-my-code) · 📓 [MoodJournal](https://github.com/chayvarmaa/mood-journal)**
`automation · AI · data viz`

**FileOrganizer** — rule-based file sorting engine using pathlib + watchdog for real-time directory monitoring.

**RoastMyCode** — submits code to OpenAI API for brutally honest quality feedback. Catches bugs, anti-patterns, and style violations.

**MoodJournal** — CLI mood tracker with SQLite persistence and matplotlib trend visualizations.

`Python` `pathlib` `watchdog` `OpenAI API` `matplotlib`

</td>
</tr>
</table>

---

### github stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=chayvarmaa&show_icons=true&theme=gruvbox&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=ff3333&icon_color=ff3333&text_color=cccccc"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chayvarmaa&layout=compact&langs_count=8&theme=gruvbox&hide_border=true&bg_color=0d0d0d&title_color=ff3333&text_color=cccccc"/>

![GitHub Streak](https://streak-stats.demolab.com?user=chayvarmaa&theme=dark&hide_border=true&background=0d0d0d&ring=ff3333&fire=ff3333&currStreakLabel=ff3333)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=chayvarmaa&theme=react-dark&hide_border=true&area=true&bg_color=0d0d0d&color=ff3333&line=ff3333&point=ffffff)

</div>

---

<div align="center">

### open to full-time opportunities

**Data Engineering · ML Engineering · Software Engineering**

BS Computer Science · MS Computer Science @ SIUE · Graduating December 2025

[![Email Me](https://img.shields.io/badge/PING%20ME-chetanvarma.g17%40gmail.com-ff3333?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d0d)](mailto:chetanvarma.g17@gmail.com)

*"Don't just learn tools. Build systems."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b0000,50:1a0000,100:0d0d0d&height=120&section=footer" width="100%"/>

</div>
