# Web Scraping (Python)

Webscraping allows for the collection of raw data from websites for the use of analytics or predictive modelling.

-----

This repository is a clean, real-world demonstration for collecting data from websites **responsibly** using:
- `requests` (fetch HTML)
- `BeautifulSoup` (parse content)
- `pandas.read_html` (extract tables fast)

This reporsitory is centered around the kind of issues you’ll encounter (403 blocks, rate limits, messy HTML), and fix when carrying out a webscraping project

---

## What this repo does
- Fetches web pages with a **proper User-Agent** (avoids common 403 blocks)
- Extracts:
  - **tables** (Wikipedia-like pages)
  - **text fields** (titles, ratings, tags, links)
- Saves cleaned results to `/data/` as CSV

---


