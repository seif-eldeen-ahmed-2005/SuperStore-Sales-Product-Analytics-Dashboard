# 🛒 SuperStore Sales & Product Analytics Dashboard

A comprehensive Power BI business intelligence solution designed to monitor retail performance, sales trends, profit margins, product category efficiency, and regional market dynamics for SuperStore.

---

## 📊 Project Overview
This project transforms raw retail transaction and order data into actionable executive insights. It empowers decision-makers to track revenue growth, evaluate sub-category profitability, identify top-selling products, and optimize regional market strategies.

---

## 🚀 Key Features & High-Level KPIs

- **Financial Controls:** Tracks total revenue at **$2.30M**, total profit at **$286.40K**, and maintains a solid **12.47% Profit Margin**.
- **Growth & Momentum:** Achieved an exceptional **46.88% Year-over-Year (YoY) Sales Growth** with cumulative running sales reaching **$2.30M**.
- **Volume Metrics:** Over **5K total orders** processed spanning **37,873 total units sold** across product categories.
- **Regional Footprint:** Detailed performance breakdown across four core territories: **West (31.58%)**, **East (29.55%)**, **Central (21.82%)**, and **South (17.05%)**.

---

## 📈 Dashboard & Technical Architecture Preview

### 1. Executive Analysis Dashboard
![Executive Analysis Dashboard](Images/Page%201.png)

### 2. Product Analysis Dashboard
![Product Analysis Dashboard](Images/Page%202.png)

### 3. Data Model (Star Schema)
![Data Model](Images/Data%20Model.png)

### 4. Data Transformation & ETL (Power Query)
![Power Query Cleaning](Images/Cleaning.png)

---

## 🛠️ Data Modeling & Technical Execution

* **ETL & Data Cleaning (Power Query):** Handled missing postal codes, standardized text fields, applied strict data typing, and established custom columns for order processing metrics.
* **Data Architecture (Star Schema):** Modeled around a central `Fact Orders` table connected via 1-to-many relationships to key dimension tables: `Dim Products`, `Dim Customers`, `Dim Locations`, `Dim Date`, and `Regional Manager`.
* **Analytics & DAX:** Authored custom DAX calculations for running totals, Year-over-Year growth percentages, sub-category profit variance, and segment performance matrices.
* **UI/UX Design:** Designed with a clean, branded SuperStore green color palette featuring high-contrast KPI cards, interactive page navigation, donut category charts, and waterfall profit breakdowns.

---

## 💡 Key Business Insights

- **Category Efficiency:** While **Office Supplies** dominates total order volume (**3,742 orders**), **Technology** leads total sales driving **$836.15K**.
- **Sub-Category Profitability:** Copiers, Phones, and Accessories generate the highest profit contributions, whereas Tables and Bookcases operate at a net loss.
- **Customer Segments:** The **Consumer** segment contributes the highest volume (**2,586 orders / $1.16M sales**), while **Home Office** yields the highest individual profit margin at **14.03%**.
