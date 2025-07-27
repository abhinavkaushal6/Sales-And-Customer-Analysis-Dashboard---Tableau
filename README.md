# 📊 Sales & Customer Performance Dashboard (2020–2023)

This Tableau project is a 2-page interactive dashboard designed to analyze sales and customer trends from 2020 to 2023. It focuses on uncovering key performance drivers, customer loyalty, product-level insights, and seasonal sales patterns—all built with clean design and data storytelling in mind.

---

## 🚀 Project Highlights

- Developed a dynamic dual-dashboard system focusing on **Sales Performance** and **Customer Behavior**.
- Designed to help businesses pinpoint their top-performing products, customers, and months.
- Packed with LOD expressions, table calculations, and context filters for deep analysis.
- Created interactivity with drill-downs, navigation buttons, and tooltips for actionable insights.

---

## 🔧 How I Built It

| Step              | Techniques / Tools |
|------------------|--------------------|
| **Data Model**   | 4 fact–dimension tables (`Customers`, `Locations`, `Orders`, `Products`) joined in Tableau |
| **Core Calculations** | - Level of Detail (LOD) & Table Calcs for:<br>  - **Max/Min Sales, Profit, Quantity** per year <br>  - **%Δ vs. PY** for Sales, Profit, Qty <br>  - **Above-average flags** for weekly Sales/Profit <br>  - **Top‑10 customers** by Sales & Profit <br>  - **Sales per Customer** aggregates |
| **Visual Design** | - Dual dashboards (Sales ↔ Customer) linked with navigation buttons <br> - Year parameter and filters for flexible analysis <br> - Color cues: Blue = Best month, Orange = Worst month |
| **Interactivity** | - Drill-downs from yearly KPIs to weekly trends <br> - Tooltip LODs for customer & product deep-dives |

---

## 📈 Headline Insights

| KPI                        | 2020     | 2021     | 2022     | 2023     | 3-Year Growth |
|---------------------------|----------|----------|----------|----------|----------------|
| **Sales**                 | $484 K   | $470 K   | $609 K   | **$733 K** | **+51 %**      |
| **Profit**                | $49 K    | $62 K    | $82 K    | **$93 K**  | **+89 %**      |
| **Quantity Sold**         | 7.6 K    | 8.0 K    | 9.8 K    | **12.5 K** | **+65 %**      |
| **Customers (2023)**      | **693** (▲ 8.6 % YoY) |
| **Orders (2023)**         | **2 K** (▲ 28 % YoY) |
| **Sales / Customer (2023)** | **$1,058** (▲ 10.8 % YoY) |

---

## 🏆 Category Highlights (2023)

- **Top Performers**: Copiers, Accessories, Paper
- **Underperformers**: Tables, Machines, Bookcases (recommended for SKU refresh)

---

## 🔍 Customer Insights (2023)

- Top-10 customers contributed **over 15% of total sales**, led by **Raymond Buch** ($14.2 K sales / $6.8 K profit)
- 60% of customers placed only **1–2 orders** — potential for growth with loyalty strategies

---

## 📅 Seasonal Trends

- **December**: Consistent peak in Sales, Profit, and Orders
- **January**: Regular dip due to post-holiday lull
- Weekly sales increased from **$9K (2020)** to **$14K (2023)**; weekly profit nearly doubled from **$0.9K → $1.8K**

---
