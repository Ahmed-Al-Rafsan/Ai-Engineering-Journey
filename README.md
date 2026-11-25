<div align="center">

# 🚀 AI Engineering Journey

**My journey from Data Analyst to AI Engineer — built in public, one project at a time.**

![Stage](https://img.shields.io/badge/current%20stage-AI%20Engineering%20Foundations-8A6A2F)
![Projects](https://img.shields.io/badge/projects-3-2E7D32)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/status-actively%20building-2E7D32)

[Portfolio](https://ahmed-al-rafsan.github.io/) · [LinkedIn](https://www.linkedin.com/in/ahmed-al-rafsan-/) · [YouTube](https://www.youtube.com/@AhmedAlRafsan)

</div>

---

## 🧭 The path

```
Data Analyst  ──►  AI Engineering foundations  ──►  Applied AI Engineer
                                ▲ you are here
```

This repo is the practice ground. Every time I learn something new — a library, a tool, a technique — I build a small, honest project with it and push it here. Each project gets its own numbered folder and its own README, so the commit history shows how I actually learn, not just the polished end result.

---

## 📚 Projects

| # | Project | Stage | Skills practised | Status |
|--:|---|---|---|---|
| 01 | [**Auto Sales — Data Cleaning & Validation**](./01-auto-sales-data-cleaning) | Data Analyst | pandas · deduplication · type validation · quarantine tables · lookup joins · Matplotlib | ✅ Complete |
| 02 | [**Retail Sales ETL & Data Quality Pipeline**](./02-retail-sales-etl-data-quality) | Data Engineering fundamentals | Python · pandas · CSV/JSON · data-quality checks · logging · exception handling | ✅ Complete |
| 03 | [**Weather API with `requests`**](./03-api-basics-requests) | AI Engineering foundations | HTTP · `requests` · query parameters · JSON responses · timeouts & error handling | ✅ Complete |

*New rows are added as I build. Newest project goes at the bottom.*

### Build 01 · Auto Sales

A messy sales export of 2,723 order lines, cleaned with a pipeline where **no row is silently deleted**: invalid rows are quarantined and the totals reconcile to the cent. It answers three questions on shipped sales — top product line, top country and peak month.

➡ [Read the full README](./01-auto-sales-data-cleaning/README.md)

---

### Build 02 · Retail Sales ETL & Data Quality

A deliberately small synthetic retail input (58 rows) becomes two traceable outputs: 53 accepted orders and 3 quarantined orders, after 2 exact duplicates are removed. Practised Python/pandas transformations, CSV/JSON exports, logging, and documenting data-quality decisions without inventing missing quantities or prices.

➡ [Explore the notebook, architecture and validation notes](./02-retail-sales-etl-data-quality/README.md)

---

### Latest build — 03 · Weather API with `requests`

A deliberately small script that calls the free Open-Meteo weather API and prints Melbourne's current temperature. The location is sent as query parameters, the request has a timeout, the status code is checked, and request errors are caught — so a wrong address or a dead connection prints a clear message instead of crashing. Practised: how a client talks to a server over HTTP, the Python `requests` library, and reading JSON responses.

➡ [Read the build notes](./03-api-basics-requests/README.md)

---

## 🗺 What's planned

These are the next steps on the path, not finished work. Each will get its own numbered folder when it is built.

| Stage | Planned practice |
|---|---|
| **Python backend** | Build my own API with FastAPI and Pydantic; test it with `pytest` |
| **LLM applications** | LLM API calls, structured output, retrieval-augmented generation (RAG) and simple agents |
| **Ship it** | Docker, cloud deployment and CI/CD — one deployed AI project |
| **Data side** | Outlier checks; rebuild project 01 in SQL; turn pipeline steps into tested functions |
| **Machine learning** | scikit-learn and PyTorch builds, including one applied to aerospace data |

---

## 🗂 Repository structure

```
Ai-Engineering-Journey/
├── README.md                          # this journey map
├── 01-auto-sales-data-cleaning/       # Data Analyst stage
│   ├── README.md
│   ├── data/
│   ├── images/
│   ├── output/
│   ├── Mini_Project_1.ipynb
│   └── requirements.txt
├── 02-retail-sales-etl-data-quality/  # Python ETL fundamentals
└── 03-api-basics-requests/            # HTTP, JSON and the requests library
```

Each project folder is self-contained: its own README, code and `requirements.txt`.

---

## 🔗 More of my work

Larger portfolio projects — employee attrition, RFM customer segmentation, fashion retail intelligence, and the school-targeting capstone — are on my [portfolio website](https://ahmed-al-rafsan.github.io/).

---

<div align="center">

**Ahmed Al Rafsan** · Melbourne, Australia
*Engineering roots. People experience. A passion for finding the story in data.*

</div>
