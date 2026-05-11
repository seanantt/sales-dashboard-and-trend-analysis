# Sales Dashboard & Trend Analysis

![Power BI](https://img.shields.io/badge/PowerBI-Analytics-yellow)
![SQL](https://img.shields.io/badge/SQL-Database-blue)
![Python](https://img.shields.io/badge/Python-DataAnalysis-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Executive Dashboard Preview

> Add your dashboard screenshot here

![Dashboard Preview](dashboard/screenshots/overview.png)

---

# Executive Summary

TokoMart Indonesia operates a multi-branch retail business with uneven sales performance across branches and product categories. Without clear business visibility, the company risks inventory misallocation, delayed decision-making, and missed growth opportunities.

This project was developed to help management monitor branch performance, analyze category contribution, identify actionable sales trends, and optimize operational strategies through an executive-level analytics dashboard.

The dashboard focuses on:
- Branch performance monitoring
- Product category contribution analysis
- Trend and seasonal analysis
- Promotion timing optimization
- Business-driven recommendations

---

# Business Problems

The company faced several operational and analytical challenges:

- Sales and inventory reports were delayed by 2–3 days
- Management lacked visibility into high and low performing branches
- Promotional timing decisions were assumption-based
- Raw POS data contained inconsistencies and anomalies
- No centralized dashboard for executive decision-making

These issues created risks in:
- Stock allocation
- Promotion effectiveness
- Revenue optimization
- Strategic planning

---

# Project Objectives

This project aims to:

- Identify top-performing and underperforming branches
- Analyze product category contribution to revenue
- Detect sales trends and behavioral patterns
- Evaluate weekend and payday sales effects
- Support faster and more accurate executive decision-making
- Transform raw POS data into actionable business insights

---

# Stakeholders

This dashboard was designed for executive and commercial decision-makers:

| Stakeholder | Business Need |
|---|---|
| CEO | Business performance visibility |
| CFO | Revenue and branch profitability analysis |
| COO | Operational optimization |
| Head of Commercial | Promotion and category strategy |

---

# Dataset Overview

| Information | Details |
|---|---|
| Business Type | Multi-Branch Retail |
| Period | Q1 2025 – Q1 2026 |
| Total Clean Transactions | 5,098 |
| Product Categories | Electronics, Fashion, Home & Living, Beauty |

---

# Product Categories

| Category | Example Products | Price Range | Business Characteristic |
|---|---|---|---|
| Electronics | Smartphone, Laptop, Tablet | Rp 1.2M – 9.5M | High revenue, lower volume |
| Fashion | Shirt, Dress, Shoes | Rp 350K – 850K | High transaction volume |
| Home & Living | Blender, Rice Cooker | Rp 250K – 1.2M | Seasonal demand |
| Beauty | Skincare, Lipstick, Perfume | Rp 150K – 550K | Strong margin potential |

---

# Analytical Frameworks

## Framework 1 — Branch Segmentation

This framework categorizes branch performance to support strategic investment decisions.

| Segment | Business Meaning |
|---|---|
| Top Performer | Increase investment and stock allocation |
| Mid Performer | Maintain and monitor |
| Watchlist | Investigate operational issues |
| Underperformer | Immediate action required |

---

## Framework 2 — Product Dual Lens

Products are analyzed from two perspectives:

| Lens | Metric | Business Impact |
|---|---|---|
| Volume | Total Quantity Sold | Drives customer traffic |
| Value | Total Revenue | Drives profitability |

This framework helps distinguish between:
- Traffic-driving products
- Profit-driving products

---

## Framework 3 — Trend Analysis

Trend analysis was conducted to identify operational and promotional opportunities.

### Analysis Areas
- Weekend vs Weekday Sales
- Payday Effect
- Daily Revenue Trends
- Promotion Timing Opportunities

### Business Impact
- Better staffing allocation
- Smarter promotion scheduling
- Improved inventory planning

---

# Key Findings

## 1. Jakarta South Leads Overall Performance

- Highest branch revenue: **Rp 2.89B**
- Lowest branch revenue: **Bandung Main — Rp 2.33B**
- Performance gap: **23.8%**

### Insight
Branch performance disparity is significant and requires operational investigation.

---

## 2. Electronics Contribute 78% of Total Revenue

Although Electronics generated lower sales volume than Fashion, the category dominated revenue contribution due to high unit prices.

### Insight
The business is highly dependent on Electronics as the primary revenue driver.

---

## 3. Weekend Sales Increase by 35%

| Comparison | Daily Revenue |
|---|---|
| Weekday | Rp 52M/day |
| Weekend | Rp 71M/day |

### Insight
Weekend demand is consistently stronger and requires operational adjustment.

---

## 4. Payday Effect Generates +30% Sales Increase

| Period | Daily Revenue |
|---|---|
| Days 1–5 | Rp 72M/day |
| Days 6–31 | Rp 55M/day |

### Insight
Customers significantly increase spending during payday periods.

---

# Dashboard Features

## Revenue Analysis
- Revenue by branch
- Revenue by product category
- Revenue trend over time

## Product Analysis
- Quantity sold analysis
- Revenue concentration analysis
- Category comparison

## Trend Analysis
- Weekend performance monitoring
- Payday effect analysis
- Daily sales fluctuations

## KPI Monitoring
- Total revenue
- Total quantity sold
- Average transaction value
- Top branch
- Top category

---

# Business Recommendations

## 1. Prioritize Electronics Stock for Weekends

Increase Electronics inventory allocation in Jakarta South and top-performing branches during weekends and pre-Lebaran periods.

### Expected Impact
- Higher sales capture
- Reduced stockout risk
- Better customer experience

---

## 2. Run Promotions During Payday Window

Focus promotional campaigns during days 1–5 when purchasing power is highest.

### Recommended Categories
- Fashion
- Beauty

### Note
Electronics promotions are less necessary due to already strong demand.

---

## 3. Investigate Bandung Main Branch

Do not immediately reduce investment.

Instead, investigate:
- Location factors
- Staffing effectiveness
- Local customer demand
- Operational execution

---

# Dashboard Screenshots

## Revenue per Branch

![Revenue per Branch](dashboard/screenshots/branch_analysis.png)

---

## Product Category Analysis

![Product Analysis](dashboard/screenshots/product_analysis.png)

---

## Trend Analysis

![Trend Analysis](dashboard/screenshots/trend_analysis.png)

---

# Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI | Dashboard & visualization |
| SQL | Data querying |
| Python | Data cleaning & analysis |
| Excel | Data validation |
| Pandas | Data transformation |
| NumPy | Numerical processing |

---

# Data Cleaning Process

The raw POS data contained:
- Missing values
- Inconsistent formatting
- Duplicate records
- Invalid transactions
- Category anomalies

Cleaning steps included:
- Null handling
- Standardization
- Duplicate removal
- Data validation
- Type conversion

---

# Folder Structure

```bash
sales-dashboard-and-trend-analysis/
│
├── README.md
├── data/
├── notebooks/
├── dashboard/
├── presentation/
├── sql/
├── docs/
└── assets/
```

---

# Future Improvements

Potential future enhancements include:

- Real-time dashboard integration
- Predictive sales forecasting
- Inventory optimization modeling
- Customer segmentation analysis
- Automated anomaly detection
- Promotion ROI analysis

---

# Business Impact

This project demonstrates how business intelligence dashboards can transform raw operational data into executive-level insights that support:

- Faster decision-making
- Better inventory allocation
- Smarter promotion strategy
- Improved operational efficiency
- Revenue optimization

---

# Author

## Rafly Sean Antonio

Data Analyst Portfolio Project

📧 rseanantonio@gmail.com

---

# Disclaimer

This project was created for portfolio and educational purposes using simulated business scenarios inspired by retail analytics use cases.
