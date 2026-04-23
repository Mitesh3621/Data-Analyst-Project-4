# E-Commerce Executive Dashboard — FY 2024

---

## Problem Statement

This dashboard helps e-commerce management teams track revenue performance, profitability, campaign effectiveness, and customer satisfaction across the full financial year 2024. It enables business leaders to identify underperforming channels, monitor refund risk by category, and make data-driven decisions to improve margins and customer experience.

If refund rates are high in specific categories or CSAT scores fall below target, the dashboard surfaces these as critical signals — allowing operations and marketing teams to act quickly.

---

## Steps Followed

- **Step 1:** Designed and embedded a structured FY 2024 dataset covering 793 orders, 5 product categories, 3 sales channels, and 5 marketing campaigns.
- **Step 2:** Built the full dashboard in a single self-contained HTML file using Chart.js for all visualizations and html2canvas for export functionality.
- **Step 3:** Created 8 KPI cards with hover-activated sparkline tooltips showing monthly trends:
  - Total Revenue
  - Net Revenue (after refunds)
  - Total Profit
  - Profit Margin
  - Total Orders
  - Average Order Value
  - Refund Rate
  - Average CSAT Score
- **Step 4:** Added status badges (On Track / Watch / Critical) to each KPI for at-a-glance health assessment.
- **Step 5:** Built the following interactive charts:
  - Monthly Revenue vs Profit with Margin % overlay (Line + Bar Combo)
  - Revenue Distribution by Sales Channel (Donut Chart with center total)
  - Revenue by Category with channel filter (Horizontal Bar)
  - Campaign Performance table (Revenue · Orders · Margin %)
  - Refund Risk Monitor table with risk-level color coding by category
- **Step 6:** Implemented channel filter — clicking a segment on the donut chart filters the Revenue by Category chart dynamically.
- **Step 7:** Added Export to PNG functionality using html2canvas.
- **Step 8:** Applied a professional dark theme with blue/teal/amber/red/green color coding for status clarity.

---

## Key Features

- ✅ Interactive channel filter — donut click filters category revenue chart
- ✅ Hover sparkline tooltips on every KPI card
- ✅ Export to PNG button for reporting
- ✅ Refund Risk Monitor with target threshold alerts
- ✅ Campaign-level revenue and margin breakdown
- ✅ Single-file HTML — no backend or external data source required

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Chart.js 4.4.1** — for all charts and visualizations
- **html2canvas 1.4.1** — for PNG export
- **Google Fonts** — DM Sans + JetBrains Mono

---

## Dashboard Snapshot

> *<img width="3072" height="1390" alt="Image" src="https://github.com/user-attachments/assets/5ab61769-dab1-4f92-80f0-e430f3caae95" />*

---

## Live Demo

🔗 [View Live Dashboard](https://mitesh3621.github.io/Data-Analyst-Project-4/ecommerce_dashboard_2024.html)

---

## KPIs Overview — FY 2024

| KPI | Value | Status |
|---|---|---|
| Total Revenue | ₹46.6L | Reported |
| Net Revenue | ₹43.9L | ✅ On Track |
| Total Profit | ₹10.9L | ✅ On Track |
| Profit Margin | 23.32% | ✅ On Track (Target >20%) |
| Total Orders | 793 | Reported |
| Avg Order Value | ₹5,882 | Reported |
| Refund Rate | 8.58% | ⚠ Watch (Target <5%) |
| Avg CSAT Score | 2.87 / 5 | ✗ Critical (Target >3.0) |

---

## Channel Revenue Breakdown

| Channel | Revenue |
|---|---|
| Mobile App | ₹21.0L |
| Website | ₹20.6L |
| Social Media | ₹5.0L |

---

## Campaign Performance

| Campaign | Revenue | Orders | Margin % |
|---|---|---|---|
| Organic | ₹13.8L | 229 | 23.4% |
| Summer Sale | ₹12.2L | 218 | 22.8% |
| New Year Blast | ₹8.5L | 146 | 23.9% |
| Clearance | ₹6.9L | 121 | 22.1% |
| Flash Deal | ₹5.4L | 79 | 24.1% |

---

## Refund Risk by Category

| Category | Refund Rate | Risk Level |
|---|---|---|
| Home & Kitchen | 14.65% | 🔴 Critical |
| Beauty | 8.66% | 🟡 Watch |
| Fashion | 8.15% | 🟡 Watch |
| Electronics | 7.25% | 🟡 Watch |
| Grocery | 3.79% | ✅ OK |

---

## Insights

1. **CSAT is critically below target (2.87/5 vs >3.0)** — immediate customer experience intervention required.
2. **Home & Kitchen has the highest refund rate (14.65%)** — 3x the 5% target, indicating product quality or delivery issues.
3. **Organic traffic is the top revenue driver (₹13.8L)** — outperforming all paid campaigns.
4. **Flash Deal has the highest margin (24.1%)** despite the lowest order volume — most efficient campaign.
5. **Mobile App and Website are nearly equal in revenue** — strong multi-channel balance.

---

## Conclusion

This dashboard provides a complete financial and operational view of e-commerce performance for FY 2024. It helps management track revenue health, identify refund risk categories, evaluate campaign ROI, and prioritize customer satisfaction improvements for better retention and profitability.

---

## About

**Data Analyst Portfolio Project 4**  
Built by Mitesh | B.Tech CSE (AI/ML) | Guru Nanak Institute of Technology, Hyderabad
