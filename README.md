# Marketing_Insights_Dashboard

# Energy Drinks — Survey Analysis (Codebasics Challenge 6)

**Project:** Consumer survey analysis of energy drink preferences  
**Author:** _Your Name_  
**Date:** _YYYY-MM-DD_

---

## Table of contents
1. [Summary](#summary)  
2. [Problem statements & solutions](#problem-statements--solutions)  
3. [Demographic insights](#demographic-insights)  
4. [Consumer preference](#consumer-preference)  
5. [Competition analysis](#competition-analysis)  
6. [Marketing channels & brand awareness](#marketing-channels--brand-awareness)  
7. [Brand penetration](#brand-penetration)  
8. [Purchase behavior](#purchase-behavior)  
9. [Product development recommendations](#product-development-recommendations)  
10. [How to reproduce / Files](#how-to-reproduce--files)  
11. [Notes & next steps](#notes--next-steps)

---

## Summary
This repository contains the analysis and findings from a consumer survey (10,000 respondents) on energy drink usage and preferences. The aim: discover demographic trends, purchase behaviors, marketing effectiveness, and product/brand recommendations.

---

## Problem statements & solutions
- **Who prefers energy drinks more?** — Males (6,038 out of 10,000; ~60%) appear to prefer energy drinks more in our sample.  
- **Which age group prefers energy drinks more?** — Age group 19–30 is the largest single cohort (>50%); ages 15–30 account for ~70% combined.  
- **Which marketing reaches the most youth (15–30)?** — Online ads reached the most youth (3,373 respondents in 15–30).  
(See detailed charts and code in `/notebooks`.)

---

## Demographic insights
- **Gender:** 60% male respondents.  
- **Age:** Majority in 19–30; 15–30 combined ~70% — indicates youth-skewed market.  
- **Channels:** Online channels (ads/social) are strongest among youth.

---

## Consumer preference
- **Ingredients:** Caffeine is the top expected ingredient; vitamins follow.  
- **Packaging:** Compact & portable cans top preference, then innovative bottle designs.

---

## Competition analysis
- **Market leaders:** Cola Coka leads, followed by Bepsi (most respondents prefer these brands).  
- **Why they win:** Brand reputation is the top reason consumers choose those brands.

---

## Marketing channels & brand awareness
- **Best channel:** Online Ads — most effective to reach maximum audience quickly and cost-effectively.  
- **Brand awareness (CodeX):** Out of 980 respondents who heard of CodeX, the average taste rating is **3.3** (industry average).

---

## Brand penetration
- **Per-city focus:** Several cities show higher neutral/negative perception — marketing should target these with positive awareness campaigns.  
- **Availability:** ~20% choose a product because of availability — distribution improvements recommended.

---

## Purchase behavior
- **Where they buy:** Supermarkets are the most common purchase point.  
- **Consumption situations:** Sports/exercise and studying/working late. Youth predominant.  
- **Price sensitivity:** 43% prefer price range 50–99 (currency).  
- **Packaging openness:** 40% prefer no change; 39% open to limited-edition packaging.

---

## Product development recommendations
1. **Availability & distribution** — increase presence in supermarkets and convenience stores.  
2. **Branding & awareness** — boost marketing in cities with low positive perception.  
3. **Limited editions** — use sparingly (campus events, sports tie-ins) to appeal to youth.  
4. **Ingredient focus** — highlight caffeine & vitamin benefits clearly.

---

## How to reproduce / Files
- `/data/` — raw survey CSVs  
- `/notebooks/` — Jupyter notebooks for cleaning, EDA, visualizations  
- `/reports/` — exported PNGs / slides / PDF with infographics  
- `/scripts/` — scripts used for aggregations and charts

**To reproduce locally:**
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
# create virtualenv, install deps
python -m venv venv
source venv/bin/activate      # linux/mac
# .\venv\Scripts\activate     # windows
pip install -r requirements.txt
jupyter notebook              # or jupyter lab
