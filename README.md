# US-Logistics-Performance-Dashboard
Power BI analytics dashboard using SQL, Python, and DAX (2026)
# US Logistics Performance Dashboard
### SQL • Python • Power BI — 2026  
**Author:** Awais Shakeel Pasha  

This project delivers a **complete logistics analytics dashboard** built with Power BI, analyzing **2,000 shipments** from multiple US carriers.  
It includes KPIs, delay metrics, transit‑time benchmarking, geographic distribution, and time‑based trends, presented in a professionally polished, multi‑page report.

---

# 📊 Dashboard Overview

The dashboard is divided into **three optimized and polished pages**, each with a specific analytical purpose:

---

## 🟦 **Page 1 — Executive Summary (Polished Layout)**

This page provides a high‑level overview of shipment performance:

### ✔ Key Features  
- **KPI Cards:** Total Shipments, On‑Time Rate, Delay Rate, Avg Transit Days  
- **Total Shipments by Carrier:** Clean, full‑width horizontal bar chart  
- **Status Breakdown:** Donut chart for Delivered / Delayed / In‑Transit / Returned  
- **Shipments by Destination:** US map showing major city drop‑offs  
- **Time Filters:** Year, Quarter, and Month slicers (clean, single-row design)

### ✔ What’s Improved  
- KPI cards centered and uniformly styled  
- Redundant visuals removed  
- Slicers resized and aligned in a single compact row  
- Map and carrier chart spacing aligned  
- Cleaner visual hierarchy and white-space usage  

---

## 🟦 **Page 2 — Carrier Delivery Performance (Polished Layout)**

This page focuses on operational efficiency at the carrier level.

### ✔ Key Features  
- **Average Transit Days by Carrier**  
- **Delay % by Carrier** (color‑coded: red → orange → yellow)  
- **Slowest Routes Table** with conditional formatting  
  - Origin  
  - Destination  
  - Transit Days  
  - Shipments Count  

### ✔ What’s Improved  
- Both bar charts aligned with equal visual height  
- Consistent color palette for delay and transit metrics  
- Full‑width slowest routes table  
- Clean header and spacing adjustments  
- More readable conditional formatting for transit outliers  

---

## 🟦 **Page 3 — Geographic & Trend Analysis (Polished Layout)**

Highlights geographic distribution and monthly performance.

### ✔ Key Features  
- **Full‑width Map:** Shipment destinations across the US  
- **Shipments by State:** Ranked table with heat‑color formatting  
- **Shipments Over Time:** Monthly line chart with trendline  

### ✔ What’s Improved  
- Balanced layout (30% table / 70% line chart)  
- Reduced map bubble sizes for cleaner readability  
- Visual alignment top-to-bottom  
- Improved trendline contrast  

---

# 🚚 Key Insights from the Dashboard

- **Higher delay percentages** observed for specific carriers (DHL, Amazon Logistics)  
- **Transit times range** from ~4.7 to 5.5 days, with several **7+ day slow routes**  
- **Shipment volume is concentrated** in major hubs such as Los Angeles, Chicago, Miami, New York, and Houston  
- 2023 shows a **stable monthly shipment pattern** with moderate peaks  

> These insights vary if new or real data is used.

---

# 🧰 Tech Stack

| Layer | Tools |
|-------|--------|
| Data Extraction | SQL |
| Data Cleaning | Python (pandas, numpy) |
| Data Modeling | Power BI (DAX, Date Tables) |
| Visualization | Power BI Desktop |
| Mapping | Bing Map Visual |
| Reporting | 3‑Page Power BI Interactive Dashboard |

---

# 🗂 Recommended Repository Structure
