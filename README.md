# Amazon Sales Analysis - Power BI Project

# Project Overview
The Amazon Sales Analysis project is designed to analyze and visualize sales performance across different regions, time periods, and customer segments. This report provides key insights into sales trends, profitability, and product performance. It also includes advanced features for data filtering and interaction, allowing users to explore various sales metrics and KPIs in detail.

# Key Features

# Slicers :
Year-Wise Selection: Filter the dataset to analyze sales and performance for specific years.

# Cards :
Sales Projection: Displays projected sales based on historical data.
KPI (Key Performance Indicators): Showcases important sales metrics such as revenue, growth rates, and targets.
Product Unit: Displays the total units sold.
Returned Status (Yes/No): Tracks whether products were returned, helping analyze customer satisfaction and product performance.

# Visual Charts :
World Map: Interactive world map showing sales distribution across regions globally.
Sales by Segment (Pie Chart): Breaks down sales by customer segment, helping identify key revenue drivers.
Sales by Market (Donut Chart): Illustrates sales performance across different markets.
Profit by Customer Name (Top 10) - Clustered Bar Chart: Highlights the top 10 customers contributing to profit.
Profit by Product Name (Clustered Bar Chart): Displays profit distribution across various products.
Loss by Product Name (Clustered Bar Chart): Showcases products generating losses, useful for identifying underperforming items.

# Data Preparation and Transformation
To ensure accurate and actionable insights, the dataset was cleaned and transformed using Power Query and various data transformation techniques:
Data Transformation: Applied data cleansing steps to prepare the dataset for analysis.
Split Function: Separated fields such as customer names and product details to enable more granular analysis.
Merge Function: Merged related fields (e.g., country and region) for better visualization.
Unpivoting Columns: Converted pivoted data into a normalized structure, making it easier to work with in visualizations.
Data Filtration: Filtered data based on specific criteria, such as excluding returned products or focusing on specific markets.
DAX Formulas and Calculations

# DAX (Data Analysis Expressions) was utilized to create new calculated fields and measures for advanced data analysis:
New Columns: Added columns to calculate metrics like sales growth, profit margins, and loss ratios.
DAX Measures: Used DAX formulas to calculate key metrics, including:
Sales Projection: Forecasts future sales based on trends.
Profit: Calculates total and average profit for products and customers.
Loss Analysis: Measures and highlights products causing losses to the business.

# How to Use
Slicers: Filter data by year to view sales performance for specific time periods.
Cards: Review key metrics such as sales projections, KPIs, and returned product statuses.
Visual Charts: Explore detailed visualizations for understanding sales by region, segment, market, and customer profitability.
Profit & Loss Analysis: Use clustered bar charts to dive deeper into the profit and loss details by product and customer.
Data Transformation: Observe how the dataset has been transformed for optimized analysis, including split, merge, and unpivoting techniques.
Tools & Technologies
Power BI: For interactive data visualizations and dashboard reporting.
Power Query: Used for data transformation and cleansing.
DAX (Data Analysis Expressions): For advanced calculations and measures.
