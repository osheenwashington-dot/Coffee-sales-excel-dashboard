# ☕ Coffee Sales Analysis & Interactive Dashboard

## 📌 Project Overview

An interactive coffee sales analysis and dashboard project developed in Microsoft Excel. The project consolidates customer, product, and transaction data to analyze sales performance across time, geography, customer segments, and product attributes.

The analysis combines data preparation, lookup functions, data validation, PivotTables, PivotCharts, slicers, and an interactive timeline to transform raw transactional data into a decision-oriented dashboard.

---

## 🎯 Business Objective

The objective of this project was to analyze coffee sales data and develop an interactive dashboard that enables users to:

- Monitor sales trends over time
- Compare sales performance across countries
- Identify high-value customers
- Analyze sales across coffee and roast types
- Explore sales by product size
- Segment results using loyalty status and date filters

---
## 📷 Dashboard Preview

![Coffee Sales Dashboard](Images/coffee_sales_dashboard.png)

---

## 🗂️ Dataset

The dataset consists of three related tables:

- **Orders** — transaction-level order and sales information
- **Customers** — customer details, country, email, and loyalty status
- **Products** — coffee type, roast type, size, and pricing information

The three tables were integrated into a consolidated Orders dataset for analysis.

---

## 🔧 Data Preparation

The data preparation process included:

- Integrating customer attributes into the Orders dataset using `XLOOKUP`
- Retrieving product attributes using `INDEX` and `MATCH`
- Calculating sales from unit price and quantity
- Converting abbreviated coffee and roast types into descriptive labels
- Identifying and removing duplicate and incorrect records
- Validating lookup results and resolving `#N/A` errors
- Applying absolute references to maintain consistent lookup ranges
- Structuring the cleaned dataset as an Excel Table

This process created a consistent dataset suitable for PivotTable-based analysis.

---

## 📊 Analysis & Visualization

### Sales Trend Analysis

Order dates were grouped by year and month to analyze sales performance over time.

A PivotChart was created to visualize changes in sales across the selected time period.

### Geographic Sales Analysis

Sales were aggregated by country and visualized using a bar chart to compare geographic performance.

### Customer Analysis

A Top 5 customer analysis was created using a value-based PivotTable filter to identify customers contributing the highest sales.

---

## 💼 Business Questions Tackled

The analysis was designed to address practical business questions such as:

### 1. How are sales performing over time?

The sales trend analysis provides a month-by-month and year-by-year view of sales performance, helping identify changes in demand and periods of stronger or weaker sales activity.

### 2. Which countries are contributing the most to sales?

The country-level analysis compares total sales across markets, helping identify geographic markets that contribute a larger share of revenue and those that may require further investigation.

### 3. Who are the highest-value customers?

The Top 5 customer analysis identifies customers generating the highest sales, providing a basis for understanding high-value customer segments and potential customer-retention opportunities.

### 4. How does sales performance vary across product characteristics?

The dashboard allows sales performance to be explored using coffee type, roast type, and product size, helping identify which product characteristics are associated with stronger sales.

### 5. How can customer attributes be used to segment sales?

The loyalty card slicer allows users to compare sales activity across loyalty segments and investigate whether purchasing patterns differ between customer groups.

### 6. How can managers explore sales performance interactively?

The combination of slicers and a date timeline allows users to filter the dashboard by time period, roast type, loyalty status, and product size, making it easier to investigate specific business segments.

---

## 📈 Interactive Dashboard

The final dashboard combines the analysis into a single interactive view.

### Dashboard Components

- Sales trend over time
- Sales by country
- Top 5 customers
- Order date timeline
- Roast type slicer
- Loyalty card slicer
- Size slicer

The timeline and slicers were connected to the relevant PivotTables and charts using Excel's Report Connections functionality, allowing users to dynamically filter the analysis.

---

## 🛠️ Tools & Techniques

**Tools:**

- Microsoft Excel
- Generative AI
- GitHub

**Techniques:**

- XLOOKUP
- INDEX & MATCH
- IF functions
- Data Cleaning & Validation
- Excel Tables
- PivotTables
- PivotCharts
- Slicers
- Timeline
- Data Filtering & Sorting
- Dashboard Development

---

## 🤖 AI-Assisted Analysis

Generative AI was used as a supporting analytical tool to:

- Interpret selected patterns identified through the Excel analysis
- Generate hypotheses for further investigation
- Support the development of business-oriented observations
- Structure analytical findings and recommendations

All numerical findings were validated against the underlying Excel analysis.

---


