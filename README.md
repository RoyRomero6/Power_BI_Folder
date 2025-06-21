# 📊 Financial Dashboard in Power BI

### 🔗 [Power BI Dashboard Link](https://app.powerbi.com/links/DnY9niFyUc?ctid=70986ee4-5379-4586-bd23-5a90b4ec2c0e&pbi_source=linkShare)

## 📌 Project Overview

This Power BI dashboard helps organizations break down and analyze key financial metrics such as **Total Sales**, **Total Profit**, and **Total Units Sold**, across multiple dimensions including **Country**, **Product**, **Segment**, and **Time (Month)**.
The insights are derived from five main countries:
- 🇺🇸 USA
- 🇲🇽 Mexico
- 🇨🇦 Canada
- 🇫🇷 France
- 🇩🇪 Germany

The dashboard is divided into two main report pages: **Overview** and **Detailed Analysis**.

---

## 🔍 Page 1: Overview
The **Overview** page presents high-level insights using multiple visuals:

### ✅ Area Chart:
- **X-axis**: Month
- **Y-axis (2 measures)**: `Total Profit` and `Total Sales`
- Allows trend analysis over time

### ✅ Area Chart by Country:
- Similar to the above, but broken down by **Country**
- Offers geographical comparison of performance

### ✅ Bar Chart:
- Visualizes `Total Sales` and `Total Profit` by **Product**
- Useful for identifying best- and worst-performing products
- ### ✅ Donut Charts (3 Total):
Visualize metrics by **Segment** (Enterprise, Government, Midmarket, Small Business, Others):
- Donut Chart 1: Total Sales
- Donut Chart 2: Total Profit
- Donut Chart 3: Total Units

These help understand which segments contribute most to business success.

---

## 🔍 Page 2: Detailed Analysis

This page dives deeper into the sales data from various perspectives:

### ✅ Donut Chart - Total Sales by Discount Band
- Identifies the impact of discounting strategies

### ✅ Donut Chart - Total Sales by Segment
- Offers another angle on segment performance

### ✅ Funnel Chart - Total Sales by Product
- Helps to visualize sales volume and conversion drop-off per product

### ✅ Treemap - Total Sales by Country
- Provides a quick visual of sales concentration geographically

### ✅ Area Chart with KPI:
- **X-axis**: Month
- **Y-axis (2 measures)**: Total Profit & Total Sales
- **KPI Goal Line**: Set at `9,000,000`
- Helps monitor actuals vs. target over time

---
## 🧠 Purpose

The dashboard was designed to:
- Track and compare **sales and profit trends over time**
- Understand which **segments, countries, and products** contribute most
- Analyze performance **against a sales KPI**
- Highlight potential areas for **strategic improvements**

---

## 🔧 DAX Measures Used

Several DAX expressions were created to enable analysis:

- `CALCULATE` – for context-based evaluations
- `SAMEPERIODLASTYEAR` – to create year-over-year comparisons
- `DISTINCTCOUNT` – for counting unique elements (e.g., customers or products)
- `SUM` – for aggregating profit, sales, and units

These allowed the creation of dynamic and filter-sensitive visuals.

---

## 📤 How to Use

1. Download the `.pbix` file from the repository.
2. Open in **Power BI Desktop**.
3. Apply your own filters or slicers by country, product, or time to derive new insights.
4. Optionally, publish to Power BI Service to share with your team.

---

## 📷 Snapshots
### 📌 Overview Page

![Image](https://github.com/user-attachments/assets/331c3ac0-6dcb-4a14-ad3c-3785e9b6aaf6)

### 📌 Detailed Analysis Page

![Image](https://github.com/user-attachments/assets/cca4e1d8-6135-4aba-9b07-fedfd80b03e8)

---

## 📎 Notes

- Null or 0 values have been appropriately excluded where they were not applicable (e.g., missing product data).
- The layout includes proper use of theme, text boxes, and KPIs to ensure clarity and storytelling.

---

## 🙌 Author

**Roy Romero**  
Data Analyst | Power BI Developer

---

