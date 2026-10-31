# Coffee-Retail-Analytics
An interactive Excel dashboard analyzing retail coffee shop transactions, sales performance, peak hours, and customer footfall across multiple store locations.

# Coffee Shop Sales & Operations Dashboard

## Overview
This project features an interactive sales and operational dashboard built in Microsoft Excel. It analyzes point-of-sale (POS) transaction data for a coffee shop chain to provide actionable insights into revenue generation, store performance, customer footfall, and product popularity.

## Dataset Highlights
The analysis is driven by a detailed `Transactions` dataset that tracks individual customer purchases, including:
* **Transaction Details:** Transaction IDs, dates, times, and quantities.
* **Store Metrics:** Store IDs and geographical locations.
* **Product Catalog:** Product categories, specific product types, item details, sizes, and unit prices.
* **Calculated Financials:** Total bill amounts per transaction.
* **Time Intelligence:** Extracted months, days of the week, and peak operational hours.

## Key Features & Insights
* **Revenue & Sales Tracking:** Aggregates total sales and average bill size per customer across different timeframes.
* **Customer Footfall Analysis:** Measures store traffic by tracking distinct transaction counts by day and hour to identify peak operational times.
* **Product Performance:** Analyzes which product categories, types, and sizes drive the most volume and revenue.
* **Location Comparison:** Evaluates and compares the performance metrics across different store locations.
* **Interactive Dashboard:** Built with Excel Pivot Tables and slicers, allowing users to dynamically filter data by store, product category, or time period.

## Tools & Technologies Used
* **Microsoft Excel:** Comprehensive data manipulation and interactive visualization.
* **Pivot Tables & Pivot Charts:** Used in the `Pivot` sheet to aggregate raw transaction data for the front-end dashboard.
* **Time Intelligence functions:** Utilizing a `Calendar Table` and date/time extractions for granular time-series analysis.

## How to Use This Project
1. Clone this repository or download the `Coffee Dashboard.xlsx` file directly.
2. Open the file in **Microsoft Excel** (Version 2016 or newer recommended for full functionality).
3. Navigate to the **"Dashboard"** sheet to explore the interactive visual interface.
4. Use the on-screen slicers and timeline filters to segment the sales data by specific months, days, locations, or product types.
5. Review the underlying transaction logic in the **"Transactions"** sheet and the calculation mechanisms in the **"Pivot"** sheet.
