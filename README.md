# 🇮🇳 India Growth – State-wise Progress Analysis

## 📌 Project Overview

The **India Growth Dashboard** is an interactive Power BI project created to analyse and compare state-wise development achievements across India for **2025 and 2026**.

The dashboard transforms raw state and sector data into meaningful insights using KPI cards, charts, an India map, slicers, and a detailed achievement table.

---

## 🎯 Project Objectives

- Analyse state-wise development performance.
- Compare sector performance between 2025 and 2026.
- Identify the states with the highest growth.
- Measure the contribution of different development sectors.
- Create an interactive dashboard for easier analysis.
- Present complex data through clear visual storytelling.

---

## 📊 Dashboard Preview

![India Growth Dashboard](images/india-growth-dashboard.png)

> Add the dashboard image to an `images` folder and name it  
> `india-growth-dashboard.png`.

---

## 📈 Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Achievements | 126 |
| States Covered | 28 |
| Development Sectors | 5 |
| Average Growth | 7.7% |
| Top-Performing State | Nagaland |
| 2025 Metric Value | 85K |
| 2026 Metric Value | 98K |

---

## 🔍 Key Insights

- **Nagaland** achieved the highest growth rate at approximately **18.2%**.
- **Tamil Nadu** ranked second with approximately **14.1% growth**.
- The average growth recorded across the analysed data was **7.7%**.
- The overall performance metric increased from approximately **85K in 2025** to **98K in 2026**.
- The dashboard covers **126 achievements** across **28 Indian states**.
- Five major development sectors were included in the analysis.
- State, sector, and year slicers allow users to perform focused analysis.

---

## 🖥️ Dashboard Components

The Power BI dashboard contains:

- Total Achievements KPI
- Total States KPI
- Total Sectors KPI
- Average Growth KPI
- Top-Performing State KPI
- State-wise India Map
- Top States by Growth Chart
- Sector Performance Comparison
- Sector Contribution Chart
- Achievement Details Table
- State, Sector, and Year Slicers

---

## 🛠️ Tools and Technologies

- **Microsoft Excel** – Data collection and initial preparation
- **Power Query** – Data cleaning and transformation
- **Microsoft Power BI** – Data modelling and dashboard development
- **DAX** – KPI calculations and analytical measures
- **GitHub** – Project documentation and version control

---

## 🧹 Data Preparation

The following data-cleaning operations were performed:

1. Checked and removed duplicate records.
2. Standardised state and sector names.
3. Corrected inconsistent data types.
4. Handled blank and missing values.
5. Converted year and metric columns into suitable formats.
6. Validated growth percentage calculations.
7. Created calculated columns and measures using DAX.
8. Verified state names for the Power BI map visual.

---

## 🧮 Sample DAX Measures

### Total Achievements

```DAX
Total Achievements =
COUNTROWS('India Achievements')
