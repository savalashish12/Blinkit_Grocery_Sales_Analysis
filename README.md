# 🛒 Blinkit Grocery Data Analysis

> An end-to-end sales and outlet performance analysis of Blinkit - India's last-minute grocery delivery platform - built using **Excel (Pivot Tables + Dashboard)**.

![Dashboard Preview](Blinkit%20Analysis.png)

---

## 📊 Project Overview

This project analyzes **8,523 grocery items** across multiple Blinkit outlet types, locations, and sizes. The goal is to uncover actionable insights around sales performance, product fat content, outlet establishment trends, and category-wise revenue distribution.

The final deliverable is an **interactive Excel dashboard** with slicers for dynamic filtering by Outlet Size, Outlet Location, and Item Type.

---

## 📁 Dataset

**File:** `Blinkit_Grocery_Data_Analysis.xlsx`  
**Sheet:** `BlinkIT Grocery Data`  
**Rows:** 8,523 records  

### Columns

| Column | Description |
|---|---|
| `Item Fat Content` | Low Fat / Regular |
| `Item Identifier` | Unique product code |
| `Item Type` | Category (Fruits, Dairy, Snacks, etc.) |
| `Outlet Establishment Year` | Year the outlet was established (2011–2022) |
| `Outlet Identifier` | Unique outlet code |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Size` | High / Medium / Small |
| `Outlet Type` | Supermarket Type 1/2/3 or Grocery Store |
| `Item Visibility` | Shelf visibility score |
| `Item Weight` | Product weight |
| `Sales` | Total sales value (USD) |
| `Rating` | Customer rating |

---

## 📈 Key KPIs

| Metric | Value |
|---|---|
| 💰 Total Sales | **$1.20M** |
| 📦 Number of Items | **8,523** |
| 💵 Average Sales | **$141** |
| ⭐ Average Rating | **4.0** |

---

## 🔍 Analysis Highlights

### Fat Content
- **Regular** items lead with **$776.3K (65%)** of total sales
- **Low Fat** items contribute **$425.4K (35%)**

### Top Selling Item Types
1. Fruits and Vegetables - $178.12K
2. Snack Foods - $175.43K
3. Household - $135.98K
4. Frozen Foods - $118.56K
5. Dairy - $101.28K

### Outlet Location Performance
| Location | Sales |
|---|---|
| Tier 3 | $472.1K |
| Tier 2 | $393.2K |
| Tier 1 | $336.4K |

### Outlet Size Performance
- **Medium** outlets dominate with **42%** of total sales ($507.9K)
- **Small** outlets: 37% ($444.8K)
- **High** outlets: 21% ($249.0K)

### Outlet Type Comparison
| Outlet Type | Total Sales | Avg Sales | No. of Items |
|---|---|---|---|
| Supermarket Type1 | $787.5K | $141 | 5577 |
| Supermarket Type2 | $131.5K | $142 | 928 |
| Supermarket Type3 | $130.7K | $140 | 935 |
| Grocery Store | $151.9K | $140 | 1083 |

### Outlet Establishment Trend
Sales peaked in **2018 at $204.5K**, with a notable dip in 2020 (likely pandemic impact) followed by a recovery in 2022 at $131.5K.

---

## 🛠️ Tools Used

- **Microsoft Excel** - Pivot Tables, Charts, Slicers, Dashboard Design
- **Data Cleaning** - Handled within Excel (fat content normalization, nulls)

---

## 📂 Project Structure

```
Blinkit-Grocery-Analysis/
├── Blinkit_Grocery_Data_Analysis.xlsx   # Dataset + Pivot Tables + Dashboard
├── Blinkit_Analysis.png                 # Dashboard screenshot
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Blinkit_Grocery_Data_Analysis.xlsx` in Microsoft Excel
3. Navigate to the **Dashboard** sheet
4. Use the **Filter Panel** slicers on the left to filter by:
   - Outlet Size (High / Medium / Small)
   - Outlet Location (Tier 1 / 2 / 3)
   - Item Type

---

## 👤 Author

**Ashish Saval**  
MCA Student | Data Analyst

---

## 📌 Use Case

This project was built as part of a **data analytics portfolio** to demonstrate skills in:
- Business Intelligence & KPI tracking
- Data visualization and dashboard design
- Sales trend analysis and segmentation
- Excel-based reporting for business stakeholders
