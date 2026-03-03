# Zipline-Logistics-Performance-Monitor
A multi-page interactive Power BI report tracking drone-based medical supply delivery operations across health facilities in Kaduna State, Nigeria. Built to help operations teams monitor delivery efficiency, identify bottlenecks, and improve fulfillment rates for critical healthcare supplies.
---

## Project Overview

Zipline operates drone delivery networks for medical supplies to remote health facilities. This report monitors performance across 4 regions (Ikara, Kauru, Kubau, Lere) and 4 months (Aug-Nov), providing a full operational picture from executive summary down to facility-level diagnostics.

---

## Dashboard Pages

| Page | Focus |
|------|-------|
| **Executive Summary** | High-level KPIs, delivery map, volume vs. backlog trends, top use-case subcategories |
| **Delivery Operations** | Lead time analysis, on-time delivery %, delivery delay categories by region |
| **Missed Opportunities** | Cancelled units, stockout events, Pareto analysis of cancellation reasons, backlog ranking |
| **Pages 1-3** | Avg backlog wait time by facility, fulfillment rate % by drug subcategory |

---

## Key Metrics

| Metric | Value |
|--------|-------|
| Total Deliveries | 4.9K |
| Active Facilities Served | 21 |
| Avg Lead Time | 75.79 mins |
| Total Backlog Units | 616K |
| Avg Backlog Wait Time | 158 days |
| Total Stockout Events | 37 |
| Total Cancelled Units | 43 |
| On-Time Delivery % | 14.92% |

---

## Key Insights

- **Antimicrobial** drugs lead delivery volume at 1,474 deliveries, followed by Fluids (979)
- **Kauru** region has the highest average lead time at 67 mins vs. a 45-min target
- **Duplicate Orders** account for 58.14% of all cancellations - the single biggest missed opportunity
- Most drug subcategories achieve 99-100% fulfillment, but **Asthma sits at 0%** - a critical gap
- **Diabetes** (50%) and **Pregnancy** (68%) show significant fulfillment shortfalls
- Pala PHC and Yardoka HC have the worst backlog wait times at 137 days each
- Backlog units peaked in August (490K) before declining sharply in September

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard development & interactive reporting |
| Power Query | Data transformation & cleaning |
| DAX | Custom KPIs, Pareto calculations, time-based measures |
| Bing Maps (Power BI) | Geographic delivery visualization |

---

## File Structure

```
Zipline-Logistics-Performance-Monitor/
 - Zipline_Logistics_Performance_Monitor.pbix
 - images/
     - executive_summary.png
     - delivery_operations.png
     - missed_opportunities.png
     - fulfillment_rate.png
 - README.md
```

---

## How to Use

1. Clone or download this repository
2. Open the .pbix file in Microsoft Power BI Desktop
3. Use the Month and Health Facility Region slicers to filter data
4. Navigate between pages: Executive Summary > Delivery Operations > Missed Opportunities > Pages 1-3

---

## Author

**Godswill Junior** - Data Analyst | Power BI | SQL | Python | Excel

- LinkedIn: https://www.linkedin.com/in/godswilljunior16/
- Medium: https://medium.com/@godswillode16
- GitHub: https://github.com/Godswill-Jr
- Live Dashboard: https://app.powerbi.com/links/HtLBQWrXh3?ctid=19f286ca-706f-4416-ad14-7c9ea1a1398b&pbi_source=linkShare

*Feel free to star this repo if you found it helpful!*
