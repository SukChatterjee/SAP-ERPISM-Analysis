# 🏆 ERPSim Final Game Analysis — Team Bravo

> **1st Place** | ERPSim Simulation | Spring 2026  
> Team: Sukanya Chatterjee · Olivia Heitzman · Charles James · Pushpa Priya Sripathi

---

## Overview

This repository contains Team Bravo's written analysis of the ERPSim business simulation — a competitive SAP-based game where teams manage a dairy distribution company across 5 rounds and 50 simulated days. The analysis covers every operational dimension of the game: demand forecasting, inventory management, pricing strategy, gross margins, and supply chain cost control.

Team Bravo finished **1st overall**, achieving the highest gross margin (14.82%), the fewest zero-stock incidents (9), and the lowest warehousing and transportation costs in the cohort.

---

## What is ERPSim?

ERPSim is an SAP simulation game developed by HEC Montréal. Teams operate a fictional dairy company using a live SAP ERP system, making real business decisions — setting prices, running MRP, placing purchase orders, and managing stock transfers — while competing against other teams in the same simulated market.

Every decision is interconnected: a forecast change triggers MRP, which drives purchasing, which affects inventory levels, which flows into financial results. The game is designed to teach ERP logic by doing, not just reading.

---

## Repository Contents

```
├── ERPSim_Winner_Analysis.docx   # Full written analysis (formatted Word document)
└── README.md                     # This file
```

---

## Analysis Structure

The written report covers six sections:

| Section | Points | Topic |
|---|---|---|
| Forecast & Purchasing | 12 pts | Independent requirements, MRP, purchase order strategy |
| Inventory & Operating Costs | 18 pts | Zero-stock incidents, warehousing, transportation, transfer strategy |
| Sales, Pricing & Gross Margins | 18 pts | Volume by round, pricing history, product-level gross margins |
| Notable Events | 5 pts | Round-by-round decision log |
| Teamwork | 2 pts | Collaboration, role division, what worked and what didn't |
| Assessment + Challenges & Lessons Learned | 10 pts | Why we won, key challenges, and takeaways |

---

## Key Results

| Metric | Team Bravo | Next Best |
|---|---|---|
| Final Rank | 🥇 1st | 2nd |
| Overall Gross Margin | 14.82% | 11.75% |
| Zero-Stock Incidents | 9 | 43 |
| Warehousing Cost | €1,200 | €1,200 (tied) |
| Transportation Cost | €3,000 | €3,000 (tied) |
| Purchase Orders Placed | 5 | 5 (tied) |
| Top-Selling Product | Milk (5,792 units) | — |

---

## Winning Strategy Summary

Three decisions separated Team Bravo from the competition:

**1. Cheese re-forecast in Round 2.**  
Market demand data showed Cheese with the highest demand index (143). We were the only team to aggressively raise its independent requirement to 1,400 units while cutting back on low-demand Cream and Ice Cream. This single forecast correction drove our volume advantage for the rest of the game.

**2. Competitive pricing from Round 1.**  
Rather than testing the ceiling with high prices in the opening round, we entered with market-clearing prices informed by practice round data. This gave us early sales momentum that compounded over five rounds while competitors who over-priced in Round 1 never fully recovered their market share.

**3. Pull-based stock transfers with dynamic frequency.**  
We ran pull transfers every 3 days by default, tightening to every 2 days for the North region after detecting early stockout risk. This kept regional service levels high with only 9 zero-stock incidents total — compared to over 260 for the worst-performing team.

---

## Lessons Learned

- **Data beats intuition.** Every decision anchored in the market demand tab outperformed every decision made on instinct.
- **Early accuracy compounds.** Getting pricing right in Round 1 is worth more than any mid-game correction.
- **Fewer, smarter purchase orders win.** Proactive bulk ordering at low unit shipping cost beats reactive emergency restocking every time.
- **Regional transfers matter as much as central purchasing.** Inventory sitting in the main warehouse doesn't sell. Getting it to the right regional location before demand hits is equally critical.
- **SAP ERP is a system of interdependencies.** No module operates in isolation — understanding how forecast → MRP → purchasing → inventory → financials connect is the core skill the simulation builds.

---

## Tools Used

- **SAP ERP** (ERPSim platform) — live simulation environment
- **Microsoft Excel** — data analysis, charting, inventory and sales tracking
- **Microsoft Word** — report writing and formatting

---

## Course Context

This project was completed as part of a graduate-level Information Systems or Operations Management course using the ERPSim simulation developed by HEC Montréal. The simulation runs on a live SAP system and is widely used in business schools to teach ERP concepts through hands-on competition.
