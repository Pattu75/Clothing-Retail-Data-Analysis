Project Summary: Clothing Retail Data Analysis

Objective: The goal of this project is to analyze clothing retail data to gain insights that can drive sales, optimize inventory management, improve customer experience, and guide strategic decisions. 
The analysis focuses on key business metrics related to stores, products, and orders.

Key Steps:

1. Data Preparation:
- Data Loading: Imported data from multiple CSV files (Products.csv, Shipping.csv, Stores.csv, Transactions.csv) into Pandas DataFrames.
- Data Cleaning: Handled missing values, filled in null entries, and removed duplicate rows.
- Data Transformation: Modified data types, split columns, and created new columns for analysis (e.g., Discount Pct, Sale Price, Net Profit, Total Revenue, Total Cost, Total Net Profit).
- Data Integration: Merged multiple DataFrames (transactions_df, products_df, shipping_df, stores_df) to create a comprehensive orders_df DataFrame.

2. Data Analysis:
- Store Metrics: Analyzed store performance, including total revenue, total cost, and net profit by store. Identified the store with the highest and lowest revenue.
- Product Metrics: Determined the most profitable products, calculated revenue-to-cost ratios, and identified top-selling products.
- Order Metrics: Explored order patterns, including the number of orders per store, orders with multiple products, and average quantities sold by color and city.
- Outlier Detection: Used the Interquartile Range (IQR) rule to identify and analyze outliers in the data, particularly for the "Socks" product type.

3. Data Visualization:
Created visualizations to better understand the data:
- Bar Plots: Quantity sold by product, average discount percentage by city.
- Scatter Plots: Total revenue vs. total cost, with net profit as a hue.
- Line Plots: Total net profit over time.
- Heatmaps: Correlation between key metrics (e.g., total net profit, quantity, sale price).
- Boxplots: Identified outliers in total revenue by product type.

4. Key Insights:
- Store Performance: Store 3 (Vancouver) generated the highest total revenue, while Store 11 (Seoul) had the lowest.
- Product Performance: Black T-shirts were the best-selling product, and Socks with a 30% discount (for green and grey colors) had a significant impact on sales.
- Order Patterns: Orders with multiple products were relatively common, and certain cities offered higher average discounts.
- Profitability: Products with high revenue-to-cost ratios (e.g., ProductID 12) were identified as the most profitable.

5. Conclusion:
This project provides actionable insights into the clothing retail business, helping senior management make informed decisions to optimize operations, improve profitability,
and enhance customer satisfaction. The analysis highlights key areas for improvement, such as inventory management, pricing strategies, and store performance.

