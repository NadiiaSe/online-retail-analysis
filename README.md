# Online Retail II — Data Quality & Sales Analysis

## Project Overview

Analysis of the Online Retail II transactional dataset, completed in two stages: data quality analysis in Excel and sales reporting in Power BI.

## Stage 1 — Excel: Data Quality & Analysis

### 1. Data Quality Assessment

I first reviewed the 2009–2010 and 2010–2011 datasets to identify data quality issues and non-standard transactions.

I checked:

- cancelled transactions and negative quantities
- zero-price transactions
- missing product descriptions
- missing Customer IDs
- unspecified countries
- inconsistent product descriptions

### 2. Product Description Cleaning

I compared product codes with their descriptions using VLOOKUP and found that the same product code could have different descriptions.

I cleaned the descriptions, checked duplicates, manually reviewed ambiguous cases, and created a canonical description library.

The standardized descriptions were then applied to the main dataset using VLOOKUP.

### 3. Data Quality Classification

For the analysis period, I created a separate dataset for December 2009 – February 2010 to study the Christmas and post-Christmas period.

I created status categories for the records and used Pivot Tables to measure data quality issues.

Key findings:

- Missing Customer IDs — 26.43%
- Missing product descriptions — approximately 0.9%
- Zero-price transactions — approximately 0.96%

### 4. Sales Analysis

I analyzed how sales changed after Christmas using monthly revenue, order volume, customer activity and product performance.

Key findings:

- Revenue decreased by 22.85% in January and by a further 13.69% in February.
- Returning customers generated only 9% less revenue in January despite placing 19.5% fewer orders.
- Average revenue per order increased by approximately 21.6% in January.

### 5. Product Analysis

Products were grouped into three categories based on their change in revenue after Christmas:

- **Seasonal products** — decline greater than 50%
- **Core products** — change between -20% and +20%
- **Emerging January products** — growth greater than 20%

I also performed a Pareto analysis. Approximately 25% of products generated 80% of revenue in both December and January.

Because some products were sold as individual items and others as packs or bundles, revenue-based metrics were preferred for product performance analysis.

## Stage 2 — Power BI: Sales Dashboard

The cleaned data was used to create a Power BI sales dashboard.

### Dashboard

The dashboard includes:

- Total Revenue — 1.96M
- Total Customers — 2K
- Total Quantity Sold — 1M
- Average Revenue per Customer — 1.11K
- Revenue by Country
- Revenue Trend
- Top 10 Products by Revenue
<img width="935" height="533" alt="image" src="https://github.com/user-attachments/assets/b3526374-9279-45d3-8249-3bd906eb1f4b" />


## Tools

**Excel:** Data Cleaning · Data Validation · VLOOKUP · Pivot Tables · Sales Analysis

**Power BI:** Data Visualization · KPI Reporting · Sales Dashboard

## Project Files

- `online_retail_dashboard.pbix` — Power BI dashboard
- `online_retail_dashboard.pdf` — PDF preview of the dashboard
