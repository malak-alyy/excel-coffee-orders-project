# excel-coffee-orders-project
project data was obtained from mochen862 on GitHub

# Coffee Orders Sales Dashboard

An interactive Excel dashboard built from a raw, multi-table coffee order dataset. The project takes three unconnected tables — orders, customers, and products — and turns them into a clean, filterable sales dashboard.

## Overview

The raw data was split across three tables with inconsistent formatting and no direct relationships between them:
- **Orders** – individual transaction records (order ID, date, customer, product, quantity, sales)
- **Customers** – customer details (name, email, country, loyalty status)
- **Products** – coffee type, roast type, size, and pricing

## What I did

- **Cleaned and standardized the raw data** — fixed inconsistent formatting, handled missing values, and standardized coffee type and roast type abbreviations into readable names
- **Modeled relationships between tables** — linked orders to customers and products using shared keys (Customer ID, Product ID)
- **Added calculated fields** — including profit and price per 100g at the product level
- **Built summary tables** using pivot tables to aggregate sales by year, month, coffee type, country, and top customers
- **Designed an interactive dashboard** combining charts and slicers so sales can be filtered and explored without touching the underlying data

## Skills demonstrated

Data cleaning, relational data modeling, pivot tables, formula-based calculated fields, chart design, and interactive dashboard building in Excel, XLOOKUP, INDEX MATCH

## Credits

Raw dataset by [mochen862](https://github.com/mochen862/excel-project-coffee-sales)
