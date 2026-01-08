
# ☕ URBAN_COFFEEPOINT_SALES_ANALYSIS IN EXCEL

## 1. Project Summary

This project is an end-to-end **Excel-based data analysis and dashboarding solution** built on a coffee sales dataset.
The objective is to demonstrate proficiency in **relational data modeling, lookup functions, pivot table analysis, and interactive reporting** using Microsoft Excel.

The final deliverable is an **interactive Excel dashboard** that enables users to analyze sales performance across time, geography, customer segments, and product attributes.

---

## 2. Data Model & Source Tables

The workbook consists of **three normalized tables** representing a simplified sales database:

### Orders Table

* Order ID
* Order Date
* Customer ID (FK)
* Product ID (FK)
* Quantity

### Customers Table

* Customer ID (PK)
* Customer Name
* Email
* Phone Number
* Address Line
* City
* Post Code
* Country
* Loyalty Card (Yes/No)

### Products Table

* Product ID (PK)
* Coffee Type
* Roast Type (M, L, D)
* Size
* Unit Price
* Price per 100g
* Profit

These tables follow a **fact–dimension structure**, with the Orders table acting as the fact table and Customers and Products as dimension tables.

---

## 3. Data Enrichment & Transformation

To create an analysis-ready dataset, I used **Excel lookup functions** to join related data across tables:

### Functions Used

* `XLOOKUP`
* `INDEX` / `MATCH`

### Purpose

* Enrich the Orders table with customer attributes (name, email, country, loyalty status)
* Enrich the Orders table with product attributes (coffee type, roast type, size, pricing)
* Maintain data integrity through key-based lookups rather than manual joins

This approach simulates **relational joins** typically performed in SQL or Power BI.

---

## 4. Analytical Approach

The enriched dataset was used to create multiple **Pivot Tables** to aggregate and analyze sales metrics across key business dimensions:

* Time (Order Date)
* Geography (Country)
* Customer
* Product characteristics (Size, Roast Type)
* Loyalty status

All calculations were performed within Pivot Tables to ensure scalability and dynamic filtering.

---

## 5. Visualizations & Dashboard Components

### Sales Over Time

* Line chart displaying total sales by date
* Integrated **Timeline** for dynamic date filtering

![TotalSales Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Total%20sales.JPG)

### Sales by Country

* Bar chart showing total sales by country
* Enables regional performance comparison


![Country Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Sales%20by%20Country.JPG)

### Top 5 Customers

* Bar chart ranking customers by total sales
* Identifies high-value customers




![Customers Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Customer%20Rank.JPG)

---

## 6. Interactivity & User Controls

The dashboard includes **Slicers** connected to all Pivot Tables and charts for interactive analysis:

* Timeline


* Coffee Size

![Coffee size slicer Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Coffee_Size_Slicer.JPG)

* Roast Type Name

 ![Roast Type slicer Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Roast_Type_Slicer.JPG) 
* Loyalty Card Status

![Loyalty slicer Screenshot](https://github.com/Stanley100M/URBAN_COFFEEPOINT_SALES_ANALYSIS/blob/main/images/Loyalty_Slicer.JPG)

All visuals respond dynamically to slicer and timeline selections, enabling multi-dimensional analysis without modifying formulas.

---

## 7. Business Insights Enabled

This dashboard supports:

* Trend analysis of sales performance over time
* Identification of top-performing products and roast types
* Comparison of loyal vs non-loyal customer revenue
* Geographic analysis of sales distribution
* Customer ranking for retention and targeting strategies

---

## 8. Technical Skills Demonstrated

* Advanced Microsoft Excel
* Relational data modeling concepts
* XLOOKUP and INDEX/MATCH for table joins
* Pivot Tables and Pivot Charts
* Interactive dashboards (Slicers & Timelines)
* Data aggregation and summarization
* Business-oriented data visualization

---

## 9. Repository Contents

* `Coffee_Sales_Analysis.xlsx`

  * Source tables
  * Lookup formulas
  * Pivot tables
  * Interactive dashboard

---

## 10. How to Use

1. Download the Excel workbook from this repository
2. Open using Microsoft Excel (desktop version recommended)
3. Use slicers and timeline to filter data dynamically
4. Analyze sales trends and performance metrics


---

## 12. Author

**[STANLEY ]**
Data Analyst

---
