## Project Overview

This project delivers a fully interactive business intelligence dashboard for a fictional retail chain - **Arasaka** - selling smartphones across multiple Indian cities. The goal is to transform raw transactional sales data into actionable insights through intuitive visual reporting in Power BI.

The dashboard allows stakeholders to monitor KPIs in real time, drill down by month, brand, city, and payment mode, and identify top-performing products and regions at a glance.

**Use Case:** Retail sales performance tracking, brand strategy, regional demand analysis, and customer behaviour profiling.

---

## Dataset Description

The dataset is a flat Excel table (`Mobile_Sales_Data.xlsx`) where each row represents a single sales transaction.

### Dataset Scope

| Attribute | Value |
|---|---|
| Total Transactions | 3,835 |
| Total Units Sold | 19,150 |
| Total Revenue | ₹76.92 Crore |
| Time Period | October 2021 – December 2024 |
| Cities Covered | 19 |
| Brands | 5 (Apple, Samsung, OnePlus, Vivo, Xiaomi) |
| Phone Models | 15 |
| Customer Age Range | 18 – 59 years (Mean: 38 years) |

---

## Dashboard Features & Visuals

The dashboard is a single-page Power BI report with slicers and cross-filtering enabled across all visuals.

### Filter Panel
A vertical **month slicer** (January–December) on the left sidebar filters all visuals by selected month(s). Three dropdown slicers at the top allow simultaneous filtering by **Brand**, **Payment Mode**, and **City**.

---

### KPI Cards

Four headline cards summarise top-level performance at a glance:

| KPI | Value |
|---|---|
| Total Revenue | ₹76.92 Crore |
| Total Quantity Sold | 19,150 units |
| Most Sold Brand (by units) | Apple - 3,932 units |
| Most Active City (by transactions) | Delhi - 1,008 transactions |

---

### Customer Ratings Distribution
A horizontal bar chart showing post-purchase ratings (1–5):

| Rating | Count | Share |
|---|---|---|
| 5 ⭐ | 1,488 | 38.8% |
| 4 ⭐ | 843 | 22.0% |
| 3 ⭐ | 652 | 17.0% |
| 2 ⭐ | 543 | 14.2% |
| 1 ⭐ | 309 | 8.1% |

Average customer rating: **3.69 / 5.0**

---

### Total Sales in Every City (Map)
An interactive Bing Maps bubble chart where each bubble represents a city and bubble size corresponds to sales volume. Key observations:
- **Delhi** is the dominant market with ₹20.39 Cr in revenue and 1,008 transactions
- **Mumbai** is a distant second at ₹12.72 Cr
- Secondary clusters appear in Ranchi, Chennai, Rajkot, Jodhpur, Bangalore, Lucknow, Madurai, and Gorakhpur

---

### Brand Performance Table
A matrix visual comparing all five brands across units sold, total revenue, and transaction count:

| Brand | Transactions | Units Sold | Total Revenue |
|---|---|---|---|
| Apple | 783 | 3,932 | ₹16.16 Cr |
| Samsung | 775 | 3,923 | ₹16.00 Cr |
| OnePlus | 768 | 3,830 | ₹15.37 Cr |
| Vivo | 766 | 3,801 | ₹15.01 Cr |
| Xiaomi | 743 | 3,664 | ₹14.38 Cr |
| **Total** | **3,835** | **19,150** | **₹76.92 Cr** |

Competition is extremely tight across all brands, with Apple holding a narrow lead.

---

### Count of Units Sold by Mobile Model
A descending bar chart showing unit counts for each of the 15 phone models. Top performers by transaction count:

1. Vivo Y51 - 283 transactions
2. iPhone SE - 280 transactions
3. OnePlus Nord - 273 transactions
4. Galaxy Note 20 - 266 transactions
5. iPhone 11 - 265 transactions

Sales are spread relatively evenly across models, suggesting no single model dominates demand.

---

## Key Insights & Findings

**1. Brand competition is nearly dead even** - All five brands perform within a narrow band. Apple leads with ₹16.16 Cr and 3,932 units, while Xiaomi trails at ₹14.38 Cr and 3,664 units - a gap of just ~12%. No brand has a dominant market position.

**2. Delhi and Mumbai together drive nearly 43% of all revenue** - Delhi alone accounts for ₹20.39 Cr (26.5% of total revenue) and Mumbai contributes ₹12.72 Cr (16.5%). The remaining 17 cities collectively share the other 57%, highlighting the importance of metro-market penetration.

**3. Payment method preferences are uniformly distributed** - UPI, Debit Card, Credit Card, and Cash each hold between 24–26% of transactions and revenue. This suggests Arasaka's customer base spans all payment demographics, and a strategy favouring one method (e.g., UPI-only discounts) risks alienating a quarter of buyers.

**4. Customer satisfaction sits at a moderate 3.69 / 5** - While 38.8% of customers gave a 5-star rating, 22.3% gave 1 or 2 stars. This bimodal distribution warrants investigation into the drivers of low-rated transactions - whether related to specific brands, models, cities, or sales agents.

**5. Apple commands the highest per-unit revenue** - With 3,932 units generating ₹16.16 Cr, Apple's implied average revenue per unit sold is ~₹41,100 - the highest of all brands. This positions Apple firmly in the premium segment.

**6. Vivo Y51 is the single most transacted model** - Despite Vivo ranking fourth overall in revenue, its Y51 model tops the transaction count chart with 283 transactions, indicating strong volume in the budget-to-mid segment even as per-unit value remains lower.

---
