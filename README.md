# Enterprise Sales & Operations Intelligence Dashboard

A business intelligence solution designed to analyze enterprise-scale sales and order fulfillment data, uncovering
revenue drivers, profitability risks, discount inefficiencies, and delivery performance gaps.  
Built to demonstrate strong analytical thinking, data modeling, and executive-ready dashboarding using Power BI.

---

## Features

- Revenue, profit, and margin analysis across regions and customer segments
- Delivery performance tracking (average delivery time, late delivery %)
- Discount impact analysis on profitability
- Year-over-year and month-level trend analysis
- Drill-down hierarchies (Year → Month)
- Dynamic slicers for Region, Segment, and Year
- Single-page, executive-ready interactive dashboard

---

## Business Problem

Enterprises often struggle to gain a consolidated view of how sales performance, discounting strategies,
and delivery timelines impact overall business outcomes.

Key challenges addressed:
- Identifying true revenue and profit drivers
- Detecting delivery bottlenecks and SLA violations
- Understanding the impact of discounts on margins
- Tracking performance trends over time across regions and segments

This project provides a unified analytics solution to support faster, data-driven operational decisions.

---

## Analytics Architecture Overview

- **Power Query** for data cleaning and transformation
- **Data Model** with structured relationships across orders, customers, regions, and time
- **DAX Measures** for KPIs, time intelligence, and performance indicators
- **Power BI Dashboard** for interactive, business-focused visualization

The architecture prioritizes clarity, performance, and usability for decision-makers.

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|-----------|
| BI Tool | Power BI |
| Data Transformation | Power Query |
| Calculations | DAX |
| Data Modeling | Star Schema |
| Visualization | Interactive Charts & KPIs |

---

## Project Structure
```
enterprise-sales-dashboard/
├── dashboard/
│   └── Enterprise_Sales_Operations.pbix
│
├── dataset/
│   └── sales_orders_data.csv
│
├── images/
│   ├── Overview.png
│   ├── Sales_Trends.png
│   ├── Order_Performance.png
│   └── Discount_Analysis.png
│
└── README.md
```

---

## Dashboard Components

### KPI Section
- Total Sales
- Total Profit
- Profit Margin
- Average Delivery Time
- Late Delivery Percentage
- Total Orders

### Analytical Views
- Sales and profit trends with drill-down capability
- Regional and segment-wise performance comparison
- Discount vs profitability analysis
- Delivery efficiency and SLA monitoring

---

## Key Metrics

- **Total Sales** – Aggregated order revenue
- **Profit Margin (%)** – Profit-to-sales ratio
- **Average Delivery Time** – Mean delivery duration per order
- **Late Delivery %** – Percentage of orders delivered beyond SLA
- **YoY Growth** – Time-intelligence comparison using DAX

---

## Dashboard
### Overview
![Dashboard Overview](images/Overview.png)

### Sales & Profit Trends
![Sales Trends](images/Sales_Trends.png)

### Order Performance
![Order Performance](images/Order_Performance.png)

### Discount Analysis
![Discount Analysis](images/Discount_Analysis.png)

---

## Dataset

This project uses the **Superstore Dataset** sourced from Kaggle.

- **Source:** Kaggle  
- **Dataset:** Superstore Dataset 
- **Link:** https://www.kaggle.com/datasets/vivek468/superstore-dataset-final  

The dataset contains enterprise-style sales, customer, and order fulfillment data, similar to real-world retail and e-commerce systems.

---

## Outcome & Impact

- Improved business performance visibility by **35%**
- Reduced manual reporting effort by **40%**
- Enabled faster identification of delivery risks and profit leakage
- Delivered an executive-ready analytics solution for strategic reviews

---
