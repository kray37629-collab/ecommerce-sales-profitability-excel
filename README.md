# E-Commerce Sales & Profitability Optimization Dashboard

## Executive Summary
This project analyzes 9,900+ transaction records from the Sample Superstore dataset to identify drivers of profit leakage, evaluate regional sales performance, and optimize promotional discount strategies.

![Dashboard Preview](dashboard_preview.png)

---

## Key Insights
* **Discount Erosion Threshold**: Discounts exceeding **20%** consistently push profit margins into negative territory (dropping as low as -300%).
* **High-Risk Products**: **Tables** and **Bookcases** generate high sales volume but drive net operating losses due to aggressive discounting.
* **Regional Performance**: The **West** region leads in profitability, whereas the **Central** region experiences severe margin compression.

---

## Technical Features Built
* **Executive KPI Cards**: Real-time summary metrics for Total Revenue, Total Profit, and Average Margin using `=SUM()` and `=AVERAGE()`.
* **Dynamic Slicers**: Interactive cross-filtering across Category, Segment, and Ship Mode.
* **Dual-Axis Combo Chart**: Sub-category breakdown comparing Sales volume against Profit line markers.
* **Scatter Plot Analysis**: X/Y plot illustrating the direct impact of Discount % on Profit Margins.

---

## Recommendations
1. **Cap Promotional Discounts**: Restrict discounts to a maximum of **15%** across all product categories.
2. **Restructure Furniture Pricing**: Adjust base pricing and freight handling costs for Tables and Bookcases to eliminate net operating losses.
3.
