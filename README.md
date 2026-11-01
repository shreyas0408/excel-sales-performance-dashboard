# excel-sales-performance-dashboard
Excel dashboard analyzing 7,000 orders to find why sales were high but profit was negative

# Sales Performance Dashboard | Excel

## Overview
Interactive Excel dashboard analyzing 7,000 orders, 1,000 customers and 200 products (Jan-Nov 2024) to understand why a sales-heavy business is losing money.

## Business Problem
Sales were healthy and stable, but overall profit was deeply negative. The dashboard answers:
- How much are we selling and how much are we actually earning?
- Which categories and products drive the losses?
- Is the loss concentrated in one segment, or is it systemic?
- Who are the customers (gender, geography) and does it change the picture?

## Dataset
- 3 tables: SALES (7,000 rows), PRODUCT (200), CUSTOMER (1,000)
- Source: [Kaggle link]
- Period: 1 Jan 2024 - 17 Nov 2024
- Profit = Selling Price - (Cost Price x Quantity)

## Tools & Techniques
Excel Data Model (relationships across 3 tables), Pivot Tables, Pivot Charts, Slicer, Waterfall chart, KPI cards, dashboard layout design

## Data Validation
- Checked nulls, duplicates and ID matching across tables (0 issues found)
- Verified the Profit column against Cost Price x Quantity

## Key Insights
1. Total sales 7.03M but total profit -12.19M (cost 19.22M)
2. 71.4% of orders are loss-making; they lost 13.56M vs 1.38M earned by profitable orders
3. Average selling price per unit (~297) is far below average cost price (~496)
4. Loss is spread evenly across all 5 categories (19-21% each), so the issue is pricing, not one category
5. Worst products: Apple Watch, Samsung Refrigerator, Canon DSLR
6. Sales flat month to month (~650K/month), no growth trend

## Recommendations
1. Audit pricing: set a minimum selling price above cost per unit
2. Review the worst 10 loss-making products first, since they give the fastest recovery
3. Check whether discounts or data entry errors are causing below-cost pricing
4. Track "% loss-making orders" as a monthly KPI

## Dashboard
<img width="1152" height="553" alt="image" src="https://github.com/user-attachments/assets/b821a55c-4316-4c29-98f8-21ec69a519e5" />

