# Retail Sales & Profitability Analysis Dashboard

## Objective

The goal of this project is to analyze retail sales performance and identify key factors impacting profitability, with a strong focus on understanding how discounting strategies influence profit.

---

## Tools & Technologies

* Power BI
* Microsoft Excel
* Data Cleaning & Transformation (Power Query)
* Data Modeling & DAX

---

## Dataset

* Superstore Dataset
* Contains information on orders, sales, profit, discounts, customers, and regions

---

## Dashboard Overview

### Page 1: Sales Overview

* High-level KPIs: Total Sales, Total Profit, Total Orders, Profit Margin
* Sales trends over time
* Category-wise sales and profit distribution
* Regional filtering for interactive analysis

---

### Page 2: Profitability Analysis

* Profit by sub-category to identify loss-making areas
* Product-level loss analysis
* Scatter plot showing relationship between Discount and Profit
* Identification of discount thresholds impacting profitability

---

## Key Insights

* Products with discounts above **~30% frequently generate losses**, indicating that excessive discounting negatively impacts profitability
* Sub-categories such as **Tables and Bookcases consistently incur losses**, despite having significant sales
* The **Technology category is the most profitable**, while Furniture shows weaker profit performance
* A clear **negative relationship exists between discount and profit** at the product level
* A small number of products contribute disproportionately to total losses

---

## Dashboard Preview

### Sales Overview

![Sales Overview](./images/page1.png)

### Profitability Analysis

![Profitability Analysis](./images/page2.png)

---

## Repository Contents

* `dashboard.pbix` → Power BI dashboard file
* `Superstore.csv` → Dataset
* `/images` → Dashboard screenshots
* `README.md` → Project documentation

---

## Key Learnings

* Built an end-to-end data analysis workflow from raw data to insights
* Learned how to design interactive dashboards in Power BI
* Applied DAX to create meaningful business metrics
* Gained experience in identifying business problems through data

---

## Future Improvements

* Add forecasting for sales trends
* Incorporate advanced KPIs (Customer Lifetime Value, Cohort Analysis)
* Deploy dashboard using Power BI Service

---

## Author

Yuvraj Singh
