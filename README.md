# Coffee Sales Dashboard ☕📊

## Overview

Developed an interactive sales dashboard enabling executives to monitor sales trends, identify top products and customers, and make informed business decisions. This project showcases my ability to translate raw data into actionable insights, combining time-series analysis, segmentation, and KPI reporting**.

---
## Business Problem Solved

* Sales Trend Analysis
  
Tracked total sales over time by coffee type (Arabica, Excelsa, Liberica, Robusta).
Identified seasonal trends and growth patterns, enabling forecasting and production planning.

* Product & Roast Segmentation
  
Filtered sales by Product Size (0.2kg, 0.5kg, 1kg, 2.5kg) and Roast Type (Light, Medium, Dark).
Analyzed which combinations of size, type, and roast drive the most revenue.

* Geographical Insights
  
Visualized total sales by country, identifying key markets like the United States.
Provided insights for targeted regional marketing and logistics optimization.

* Customer Analysis & Retention
  
Highlighted top 5 customers and calculated Top 10 Customer Contribution (5.76% of total sales).
Allowed the company to focus on high-value clients and develop loyalty programs.

* Interactive KPIs & Decision Support
  
Built filters and interactive charts to explore trends by quarter, year, product type, and customer segment.
Enabled executives to make informed, data-driven decisio

##

---
## Key Features

* Interactive dashboard with slicers for **Date, Roast Type, Size, and Loyalty Card**
* Sales trend analysis over time
* Sales distribution by country
* Identification of top customers by revenue

---

## Data Model

The solution follows a simple star-style structure:

* **Orders**: main fact table
* **Customers**: customer attributes
* **Products**: product attributes

The `orders` sheet is enriched using lookups and acts as the single source for all visuals.

---

## Lookup Logic & Power Query Used(another version)

* **XLOOKUP**: to pull customer details (name, country, loyalty status) into the orders table
* **INDEX + MATCH (VLOOKUP-style)**: to retrieve product attributes such as price, size, and roast type
* **Power Query**: Used in another version of the dashboard instead of Xlookup & Index

---

## Tools & Skills Demonstrated

* Advanced Excel formulas (XLOOKUP, INDEX, MATCH, Power Query)
* Dashboard design and visual storytelling
* Data modelling and aggregation

## Dashboard
 ![Dashboard](https://github.com/Farhad-UddinS/Coffee-Sales-Excel-Dashboard/blob/main/Screenshot%202026-01-04%20013707.png)
