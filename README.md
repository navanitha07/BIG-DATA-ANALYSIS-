# BIG-DATA-ANALYSIS-
COMPANY: CODTECH IT SOLUTIONS

NAME: NAVANITHA S

*INTERN ID: CT04DF827

"DOMAIN: DATA ANALYTICS

"DURATION: 4 WEEEKS

MENTOR: NEELA SANTHOSH KUMAR

DESCRIPTION:Project Overview: High-Performance Retail Data Analysis using Dask
Introduction
In today’s data-driven retail industry, extracting meaningful insights from massive datasets is essential for strategic decision-making. This project focuses on analyzing the “Superstore” sales dataset using Dask, a parallel computing library that scales data processing workflows, along with Pandas and Matplotlib for analysis and visualization. The primary goal is to uncover high-value sales transactions, regional performance trends, and top-selling product categories in a scalable, efficient manner.

Tools and Technologies Used
Dask: Used to handle large datasets that exceed memory constraints, allowing parallelized operations similar to Pandas.

Pandas: For data manipulation and structural operations on smaller chunks.

Matplotlib: For generating clear, informative visualizations like pie and line charts.

Superstore Dataset: A well-known retail dataset containing sales, discount, category, region, and sub-category details.

Dataset Loading and Preprocessing
The analysis begins with importing the Superstore dataset using dask.dataframe.read_csv(). A specific dtype for the Discount column is set to ensure type consistency. The dataset is then checked for its structure using df.dtypes and a quick glance is provided using df.head().

High-Value Sales Filtering
One of the early analyses focuses on identifying transactions with sales greater than 1000, which are considered high-value. This helps in isolating major revenue-generating entries, which are crucial for strategic marketing and business planning.

Sales by Region
Using Dask’s groupby function, the dataset is grouped by the Country column (assumed to represent regions), and the total sales per country are computed. This aggregation enables stakeholders to identify top-performing markets and explore underperforming regions that may require business development efforts.

The computed results are visualized using a line chart, making it easy to interpret regional trends in sales across the dataset. The axes are clearly labeled to reflect “Sales” and “Market” to aid readability.

Top 10 Selling Sub-Categories
Another key insight area is product performance. The dataset is grouped by Sub-Category, and the top 10 sub-categories by total sales are extracted using .nlargest(10). These results provide valuable information on which types of products are driving revenue, which can directly influence inventory planning, promotional campaigns, and pricing strategies.

This data is represented using a pie chart, giving a visual snapshot of the market share held by each top-selling sub-category. Visual enhancements such as shadows, percentage labels, and a centered layout make the chart engaging and easy to interpret.

Conclusion
This project demonstrates the powerful combination of Dask’s scalability and Pandas’ simplicity in performing efficient, high-level retail analytics. By focusing on high-value transactions, regional performance, and product-level analysis, it delivers insights that can drive real-world business decisions. The integration of Matplotlib charts further enhances the presentation of findings, making the analysis both accessible and actionable for stakeholders.
