# Product Sales Analytics | ABC Analysis · Google Sheets
**Tool:** Google Sheets 

**Dataset:** E-commerce orders, Europe & Western Asia


Analysis of e-commerce sales based on a dataset of **1,321 orders** across **45 countries**. Total revenue — **$1.69B**, profit — **$497M**, ~**6.5M units** sold. The goal was to identify priority product categories through ABC analysis and uncover patterns in sales channels, geography, and time-based metrics.

**Tech stack:** Excel — pivot tables, calculated fields, conditional formatting, charts.

**Tools used:** `SUM`, `IF`, and cumulative percentage formulas for ABC classification; pivot tables across product categories, regions, sales channels, weekdays, and shipping intervals; bar and pie charts to visualize revenue, profit, and units sold distribution.

**ABC analysis** was conducted across three dimensions simultaneously. By **revenue**: class A — Office Supplies and Cosmetics. By **profit**: class A expands to Cosmetics, Office Supplies, Household, and Snacks. By **units sold**: class A — Beverages and Snacks. **Cosmetics** is the only category that lands in class A across all three dimensions. Beverages is a notable outlier — class A by volume but class C by profit, signaling a margin compression issue.

**Conclusions:** marketing investment and inventory should be concentrated on Cosmetics and Office Supplies. Beverages requires a pricing or cost structure review. Cereal and Fruits are consistently class C — candidates for SKU reduction or renegotiated supply terms.
