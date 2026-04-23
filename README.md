# FMCG Sales Analysis & Demand Forecasting
Data-driven analysis of retail sales to uncover profitability drivers, demand patterns, and pricing inefficiencies.

---

## Key Takeaway
Profitability — not revenue — is the core issue. Growth can be achieved by fixing pricing, discounting, and product mix rather than increasing sales volume.

---

## Overview
This project analyzes 9,994 FMCG retail transactions across 4 years (2014–2017) to identify trends in sales, profitability, and customer behavior. The focus is on extracting actionable insights that support better business decisions.

---

## Objective
To analyze sales and profit patterns, identify inefficiencies in discounting and product performance, and recommend strategies to improve profitability.

---

## Key Business Findings

### Profitability Issues
- 59.9% of Furniture orders with >20% discount are loss-making (693 out of 1,157 orders)
- Machines generates $189K revenue but only $3.3K profit (1.8% margin)
- Tables, Bookcases, and Supplies operate at negative margins (-8.6%, -3.0%, -2.5%)
-  Nearly 60% of heavily discounted Furniture orders are loss-making — indicating systemic pricing failure, not isolated inefficiency

### Revenue Concentration Risk
- Top 3 sub-categories (Phones, Chairs, Storage) contribute 38.4% of total revenue ($882K of $2.29M) — heavy reliance on 3 of 17 sub-categories is a structural business risk

### Regional Performance Gap
- Central region operates at 7.9% profit margin vs West's 14.9% — nearly half the efficiency despite comparable sales volume

### Customer Segment Insight
- Home Office is the most efficient segment (14% margin vs 11.5% Consumer), despite lower order volume

###  Overall Insight
- High revenue does not guarantee profit — pricing and discount strategies are misaligned across multiple categories and regions

---

## Business Recommendations
- **Cap discounts at 20%** → prevents margin erosion across Furniture and other categories
- **Re-evaluate Tables, Bookcases, and Supplies** → loss-making SKUs actively dragging down overall profitability
- **Audit Central region** → investigate pricing, logistics, and operational cost inefficiencies
- **Prioritise Home Office segment** → highest margin segment (14%), most efficient to grow
- **Diversify beyond top 3 sub-categories** → reduces structural revenue concentration risk
- **Build inventory 6–8 weeks before November** → seasonal peak is consistent and predictable

---

## Visualisations

### Monthly Sales Trend
![Monthly Sales Trend](monthly_sales_trend.png)

### Top Sub-Categories by Revenue
![Top Sub-Categories](top_subcategories.png)

### Regional Sales & Profit
![Region Performance](region_performance.png)

### Sales Forecast — 3-Month Moving Average
![Sales Forecast](sales_forecast.png)

### Profit Margin by Sub-Category
![Profit Margin](profit_margin_analysis.png)

### Discount vs Profit Impact
![Discount vs Profit](discount_vs_profit.png)

### Customer Segment Analysis
![Customer Segments](customer_segments.png)

---


## Business Questions & Analysis

**Peak Demand**
- November–December show consistent spikes ($100K–$120K monthly)
- January is the weakest month ($10K–$20K)
- Build inventory 6–8 weeks before peak; plan January clearance

**Sales Growth**
- Sales grew ~62% from 2014 to 2017 (avg 15–18% year-over-year)
- Sustain growth by fixing profitability leaks identified above

**Discount Impact**
- Negative correlation (r = -0.219) between discount rate and profit
- High discounts (>20%) frequently result in loss-making orders
- Cap discounts to protect margins

**Regional Performance**
- West leads at 14.9% margin; Central underperforms at 7.9%
- Audit Central region for pricing and cost inefficiencies

**Customer Segments**
- Consumer drives highest volume; Home Office delivers highest efficiency
- Target Home Office for high-margin growth campaigns

---

## Forecasting Approach
- 3-month moving average used to estimate short-term sales trend
- Smooths monthly volatility but does not account for seasonality or external factors
- Not suitable for production forecasting
- Future improvement: Implement ARIMA or Facebook Prophet for more accurate predictions

---

## Tools & Technologies
- Python 3 (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub
- Dataset: Sample Superstore Sales (Kaggle — 9,994 transactions)

---

## Project Structure

FMCG-Sales-Analysis/
│
├── analysis.ipynb
├── README.md
├── monthly_sales_trend.png
├── top_subcategories.png
├── region_performance.png
├── sales_forecast.png
├── profit_margin_analysis.png
├── discount_vs_profit.png
└── customer_segments.png


## Conclusion

This analysis reveals a structural profitability problem: high-revenue categories
and regions are not translating into profit due to aggressive discounting and
inefficient cost structures.

By correcting pricing strategies, removing loss-making products, and focusing
on high-margin segments, the business can improve profitability without increasing
sales — shifting the strategy from growth by expansion to growth by optimisation.
