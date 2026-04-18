# 💰 Sales Profitability Analysis Dashboard

## Project Overview
This project examines sales and profitability data for a U.S.-based retail store operating across 49 states, ~1,800 products, and 793 customers.

Using Tableau, the dashboard delivers a comprehensive view of profit performance across product sub-categories, geographies, and time; with a particular focus on how discounting practices affect the bottom line. The result is an executive-ready tool for identifying where the business is making money, where it is losing it, and what actions can reverse underperformance.

## Business Problem
**The retail store** seeks to move beyond top-line revenue tracking and develop a granular understanding of where profit is actually being generated; and where it is being eroded.

The challenge:
➡️ Identify which products, sub-categories, states, and cities are driving or undermining profitability, and determine the extent to which discounting is hurting margins.

## Dataset
- 9,994 transactions across 5,009 unique orders
- ~1,800 products, 793 customers, spanning 49 U.S. states
- Key fields include: `Profit`, `Sales`, `Discount`, `State`, `City`, `Sub-Category`, `Order Date`, `Product Name`
- Store dataset covering sales, discount, and profit performance across regions and product lines

## Tools & Technologies
- **Tableau**

## Data Preparation / Methodology
Data was clean and required no pre-processing prior to import into Tableau. All aggregations and calculations were performed directly within Tableau.

## Dashboard Features
- **Sub-category filter:** Allows users to isolate specific product sub-categories (e.g. Tables) for focused profitability analysis
- **Profit range filter:** Enables filtering of transactions by profit value to surface high-profit and loss-making orders
- **Geographic drill-down:** State and city-level maps allow users to zoom from national overview to city-level profit performance
- **Product-level exploration:** Treemap enables quick identification of the most and least profitable individual products

## Visualizations Included
- 📌 **Bar Chart — Sales Mix:** Breakdown of sales contribution across product sub-categories
- 📌 **Bar Chart — Sales/Profit Mix:** Side-by-side comparison of sales and profit across sub-categories, revealing where high sales do not translate to high profit
- 📌 **Bar Chart — Profit Sizes:** Ranked view of profit magnitude across sub-categories for quick performance comparison
- 📌 **Map — State Profits:** Choropleth map showing profit distribution across 49 U.S. states, highlighting geographic strengths and problem areas
- 📌 **Symbol Map — City Profits:** City-level profit bubbles providing granular geographic insight beyond state averages
- 📌 **Treemap — Product Profits:** Profit performance visualized by individual product, sized and colored by profit contribution
- 📌 **Scatter Plot — Profit vs. Discounts:** Reveals the relationship between discount levels and profit outcomes across transactions
- 📌**Continuous Line Chart — Profit Trend:** Tracks profit performance over time to identify growth periods, seasonal patterns, and decline phases

 [**Dashboard Overview**]
 <img width="1366" height="768" alt="Screenshot (582)" src="https://github.com/user-attachments/assets/795edf01-c96c-4281-bb5b-3abf1e9cf5da" />

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/shared/JT9PYPQ78?:display_count=n&:origin=viz_share_link)**

## Key Insights
- **Geographic concentration:** → A few states account for most of the profit, while several others consistently run at a loss — showing clear regional differences in performance
- **Discount-profit relationship:** → Higher discounts tend to lead to lower or negative profits, suggesting that the store's discounting approach is eating into margins across many orders
- **Sub-category divergence:** → Some sub-categories like Tables and Bookcases bring in decent sales but still lose money, while others are both popular and profitable — sales alone does not always mean profit
- **Product-level losses:** → Some individual products lose money on almost every order, quietly pulling down overall profit even when total sales look healthy
- **Profit trend patterns:** → Profit fluctuates over time, with clear high and low periods that may be linked to seasonal demand or the timing of discount campaigns
- **City-level disparities:** → Even within well-performing states, some cities are losing money — meaning state-level averages can hide local problem areas

## Recommendations
- **Rethink the discounting approach:** Since heavy discounts are closely linked to profit losses, the store should set discount limits by sub-category and avoid deep discounts on products that already have thin margins
- **Take a closer look at loss-making sub-categories:** Sub-categories like Tables that sell well but still lose money should be reviewed — whether that means raising prices, renegotiating supplier costs, or reducing their share of the catalogue
- **Put more focus on sub-categories that are both popular and profitable:** Marketing efforts and stock investment should lean toward products that bring in strong sales and healthy profits at the same time
- **Address underperforming states:** States that consistently lose money should be looked at more closely, whether that involves adjusting prices locally, cutting operational costs, or scaling back activity in those areas
- **Deal with products that keep losing money:** Any product that loses money order after order should be repriced, renegotiated with suppliers, or removed from the catalogue altogether
- **Time promotions and discounts better:** Rather than running discounts throughout the year, the store should use profit trend data to focus campaigns during periods when sales are naturally stronger
- **Look into city-level loss areas:** Cities that are losing money within otherwise profitable states deserve a closer look at local delivery costs, pricing, or demand patterns

## Outcome / Impact
This dashboard enables:
- ✅ Clear identification of profit drivers and loss contributors across products, sub-categories, and geographies
- ✅ Evidence-based restructuring of discounting and pricing strategies
- ✅ Geographic and product-level targeting for cost reduction and margin improvement
- ✅ Executive-ready visibility into profit trends for strategic planning and forecasting

## Next Steps
- Incorporate customer segmentation analysis to identify the most and least profitable customer groups
- Build a profit forecasting model using historical trend and seasonality data
- Integrate shipping and operational cost data to compute true net profit by region and product
