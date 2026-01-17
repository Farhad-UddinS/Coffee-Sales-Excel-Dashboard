# Coffee Sales Dashboard ☕📊

## Overview

This repository contains an Excel-based **Coffee Sales Dashboard** built to analyse sales performance across time, geography, products, and customers.

The file demonstrates how raw order data can be transformed into an interactive dashboard using **lookup formulas, calculated fields, and Excel visuals**.

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

## Lookup Logic Used

* **XLOOKUP**: to pull customer details (name, country, loyalty status) into the orders table
* **INDEX + MATCH (VLOOKUP-style)**: to retrieve product attributes such as price, size, and roast type

This approach avoids column-order dependency and keeps the model flexible.

---

## Tools & Skills Demonstrated

* Advanced Excel formulas (XLOOKUP, INDEX, MATCH)
* Dashboard design and visual storytelling
* Data modelling and aggregation

## Dashboard
 ![Dashboard](https://github.com/Farhad-UddinS/Coffee-Sales-Excel-Dashboard/blob/main/Screenshot%202026-01-04%20013707.png)
