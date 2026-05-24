# 🍊 Swiggy Sales Analysis Dashboard

An end-to-end Excel analytics project built on Swiggy food delivery data — covering data structuring, pivot analysis, KPI calculation, and an interactive dashboard with slicers and charts.

---

## 📁 Project Structure

```
Swiggy-Sales-Analysis/
├── Swiggy Data.xlsx
│   ├── Swiggy Data       ← Raw transactional dataset
│   ├── Analysis Sheet    ← All pivot tables & charts
│   ├── Dashboard         ← Interactive visual dashboard
│   └── Sheet3            ← (Working/scratch sheet)
└── README.md
```

---

## 📊 Dataset Overview

| Field | Description |
|---|---|
| Dish Name | Name of the food item ordered |
| Food Type | Veg / Non-Veg |
| Price (INR) | Order value in Indian Rupees |
| Rating | Customer rating (1–5) |
| City | City where the order was placed |
| State | State of delivery |
| Date | Order date (Jan – Aug 2024) |

**Coverage:** January 2024 – August 2024 across 25+ Indian states

---

## ⚙️ What Was Built

### 1. KPI Calculations
Five headline metrics computed directly from the raw data:

- **Total Sales** — `SUM(Price)`
- **Average Rating** — `AVERAGE(Rating)`
- **Rating Count** — `COUNT(Rating)`
- **Total Orders** — `COUNT(Dish Name)`
- **AOV (Avg Order Value)** — `Total Sales ÷ Total Orders`

### 2. Pivot Tables (Analysis Sheet)

| Pivot | Rows | Values |
|---|---|---|
| Monthly Trend | Month | Sum of Price |
| Daily Trend | Day of Week | Sum of Price |
| Food Type Split | Food Type | Sum of Price |
| Quarterly Analysis | Quarter | Sum of Price, Avg Rating, Count |
| State Analysis | State | Sum of Price |
| Top 5 Cities | City (Top 5 filter) | Sum of Price |
| Weekly Trend | Week Number | Sum of Price |

### 3. Charts
- 📈 **Line chart** — Monthly sales trend
- 📊 **Bar chart** — Daily sales by weekday
- 🍩 **Donut chart** — Veg vs Non-Veg split
- 📊 **Horizontal bar** — Top 5 cities ranking
- 🗺️ **Bing filled map** — State-level revenue heatmap
- 📊 **Column chart** — Weekly sales trend

### 4. Interactive Dashboard
A single-page dashboard with:
- All 5 KPI cards at the top
- All charts embedded and linked to slicers
- **Slicers for:** Month, Food Category, Restaurant Name
- Orange Swiggy-branded theme throughout

---

## 📈 Key Results

| Metric | Value |
|---|---|
| Total Sales | ₹53.01M |
| Average Rating | 4.34 / 5 |
| Avg Order Value | ₹268.51 |
| Total Orders | 197,430 |
| Rating Count | 5.59M |

### Sales by Quarter
| Quarter | Revenue | Orders |
|---|---|---|
| Q1 (Jan–Mar) | ₹19.7M | 73,096 |
| Q2 (Apr–Jun) | ₹19.9M | 74,163 |
| Q3 (Jul–Aug) | ₹13.4M | 50,171 |

### Top 5 Cities
| City | Sales |
|---|---|
| Bengaluru | ₹5.46M |
| Lucknow | ₹3.12M |
| Hyderabad | ₹3.02M |
| Mumbai | ₹3.02M |
| New Delhi | ₹2.83M |

### Food Type
| Type | Sales | Share |
|---|---|---|
| Vegetarian | ₹34.7M | 65% |
| Non-Vegetarian | ₹18.3M | 35% |

---

## 💡 Key Insights

- **Weekend demand is real** — Saturday (₹7.78M) and Sunday (₹7.64M) are the top two days
- **February consistently dips** — shortest month + post-Jan slowdown creates a revenue gap
- **Bengaluru dominates** — ₹5.46M, nearly double the #2 city
- **Veg rules** — 65% of all revenue comes from vegetarian orders
- **Rating is rock-solid** — 4.34 held across all 3 quarters despite volume

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Charts, Slicers, Bing Maps, Conditional Formatting
- **Excel Functions** — `SUM`, `AVERAGE`, `COUNT`, `COUNTA`, `IF`, `TEXT`

---

## 👤 Author

Built as part of a data analytics portfolio project.  
Data Period: **January – August 2024**  
Last Updated: **May 2026**
