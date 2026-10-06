# Online Retail II — Data Quality & Sales Analysis

## Project Overview

Analysis of the Online Retail II transactional dataset, completed in two stages: data quality analysis in Excel and sales reporting in Power BI.

## Stage 1 — Excel: Data Quality & Analysis

### Data Quality

Before the business analysis, I reviewed the dataset for missing, inconsistent, and non-standard records.

The main issues identified were:

- Missing Customer IDs — 26.43% of records
- Missing product descriptions — approximately 0.9%
- Zero-price transactions — approximately 0.96%
- Cancelled and operational transactions
- Different descriptions used for the same product code
- Different sales units for the same product

I standardized product descriptions, created a reference description library, and classified special transaction types.

### Sales Analysis

I then analyzed the period around Christmas to understand how sales changed after the holiday season.

Key findings:

- Revenue decreased by 22.85% in January and by a further 13.69% in February.
- Returning customers generated only 9% less revenue in January despite placing 19.5% fewer orders.
- Seasonal products showed the largest post-Christmas declines.
- Approximately 25% of products generated 80% of revenue in both December and January.
- Revenue analysis was preferred over quantity-based comparison because some products were sold in different packaging units.

## Stage 2 — Power BI: Sales Dashboard

The cleaned data was used to create a Power BI sales dashboard.

### Dashboard

Key metrics:

- **Total Revenue:** 1.96M
- **Total Customers:** 2K
- **Total Quantity Sold:** 1M
- **Average Revenue per Customer:** 1.11K

The dashboard includes:

- Revenue by Country
- Revenue Trend
- Top 10 Products by Revenue

## Tools

**Excel:** Data Cleaning · Data Validation · VLOOKUP · Pivot Tables · Sales Analysis

**Power BI:** Data Visualization · KPI Reporting · Sales Dashboard

## Project Files

- `online_retail_dashboard.pbix` — Power BI dashboard
- `online_retail_dashboard.pdf` — PDF preview of the dashboard
