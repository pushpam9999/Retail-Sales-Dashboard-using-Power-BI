 Retail Sales Analytics Dashboard | Power BI
 Project Overview

This project showcases an Interactive Retail Sales Analytics Dashboard built using Power BI.
The dashboard provides a consolidated view of sales performance across categories, brands, states, and time periods, enabling data-driven business insights.

 Key KPIs

The dashboard highlights the following business metrics using DAX measures:

Total Sales: 1.88M

Total Orders: 3.50K

Total Products: 40

Average Discount: 35.51%

 Dashboard Insights

Category-wise analysis: Men, Women, Beauty, Kids

Top-performing brands: Puma, H&M, Roadster, Adidas, HRX

Top 10 states by sales contribution

Monthly order trend analysis

Product insights by color, size, and sub-category

 Tools & Technologies Used

Power BI

DAX (Data Analysis Expressions)

Power Query

Data Modeling

Interactive Slicers & Filters

Data Visualization

 DAX Measures Used (Examples)
Total Sales = SUM(Sales[Sales_Amount])

Total Orders = DISTINCTCOUNT(Sales[Order_ID])

Product Count = DISTINCTCOUNT(Products[Product_ID])

Average Discount = AVERAGE(Sales[Discount_Percentage])

 Data Preparation

Cleaned and transformed raw data using Power Query

Handled missing values and optimized data types

Created relationships between fact and dimension tables

Built a star-schema style data model

Interactive Features

Slicers for Brand, Category, City, Year, Color, and Size

Dynamic filtering across all visuals

Drill-down enabled for deeper analysis

Visuals Included

KPI Cards

Donut Chart

Bar & Column Charts

Treemap

Line Chart (Monthly Trends)

Business Value

Helps track overall sales performance

Identifies top brands and high-performing states

Analyzes category contribution and seasonal trends

Supports faster, data-driven decision making

