# Superstore Sales Performance Dashboard

**Interactive 3-Page Power BI Dashboard | Data Analyst Portfolio Project**

![Executive Overview](Executive-Overview.png)

## Problem Statement

A large retail company (Superstore) is struggling to understand its overall performance across different regions, product categories, and customer segments. Despite generating significant revenue, profitability varies widely, and leadership needs clear, data-driven insights to identify underperforming areas, optimize discounts, and improve decision-making to increase net profit and operational efficiency.

## Data Cleaning & Preparation

- Imported raw Superstore sales dataset (2011–2014) containing 9,994 rows and 21 columns
- Handled data type issues, missing values, and inconsistent formatting in Excel
- Created calculated columns and measures in Power BI (e.g., Profit Margin %, Year-over-Year growth, Average Order Value)
- Built a clean star-schema data model with proper relationships between tables (Orders, Products, Returns, etc.)
- Removed duplicates and standardized category/sub-category names

## Analysis & Modeling

- Developed key performance indicators (KPIs) using DAX measures
- Performed year-over-year (YoY) growth analysis by quarter and category
- Analyzed profitability by product category, sub-category, region, state, ship mode, and segment
- Evaluated the impact of discounts on profit margins
- Identified top-performing and under-performing products, states, and customer segments

## Visualizations

### 1. Executive Overview (High-Level KPIs & Trends)
![Executive Overview](Executive-Overview.png)

### 2. Profitability Deep Dive
![Profitability Deep Dive](Profitability-Deep-Dive.png)

### 3. Key Insights & Actionable Recommendations
![Insights & Recommendations](Insights-&-Recommendations.png)

## Key Insights & Actionable Business Recommendations

**Overall Performance**
- Generated **$2.30M** in total sales and **$286.4K** in net profit (12.47% margin) across 5,009 orders.

**Category Performance**
- **Technology** is the strongest category (highest sales + 17.40% margin)
- **Furniture** has the lowest profitability (only 2.49% margin) due to heavy discounting

**Geographic Performance**
- West and East regions drive the majority of sales and profit
- Top 3 states by net profit: California ($76K), New York ($74K), Washington ($33K)

**Discount & Shipping Impact**
- High discounts significantly hurt Furniture margins
- Standard Class and Second Class shipping contribute the most to net profit

**Actionable Recommendations**
- Prioritize promotions and marketing efforts on **Technology** products in California and New York
- Review and significantly reduce deep discounts on **Furniture** products to improve margins
- Focus sales and marketing efforts on West and East regions
- Explore bundling high-margin Office Supplies sub-categories (Labels, Paper, Envelopes)
- Optimize shipping strategy by encouraging Standard/Second Class options where possible

## Business Results & Impact

- Identified clear opportunities to **increase overall profit margin** by 3–5 percentage points through targeted discount control and category focus
- Highlighted high-potential states and segments that could drive an additional **$80K–$120K** in annual net profit
- Provided leadership with an interactive, easy-to-use dashboard for ongoing monitoring and decision-making

## Tools Used
- **Power BI Desktop** (data modeling, DAX, visualizations)
- **Microsoft Excel** (data cleaning and preparation)

## How to View the Dashboard
1. Download the full interactive file: [`Superstore Sales Performance Dashboard.pbix`](Superstore%20Sales%20Performance%20Dashboard.pbix)
2. Open it with **Power BI Desktop** (free)
3. Interact with all slicers (Year, Region, Category, Segment)

---

**Live GitHub Repository**: [https://github.com/Sumon2122-stack/superstore-sales-performance-dashboard](https://github.com/Sumon2122-stack/superstore-sales-performance-dashboard)

Made with ❤️ as part of my Data Analyst Portfolio  
Feel free to ⭐ this repo if you found it useful!
