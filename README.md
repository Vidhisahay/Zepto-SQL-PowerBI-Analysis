# Zepto: SQL and Power BI Data Analysis Project
This project focuses on analyzing inventory availability sales performance pricing and discount behavior for Zepto, a quick commerce platform. Inventory inefficiencies pricing misalignment and over discounting can directly impact revenue customer satisfaction and operational costs in fast delivery businesses.

Through structured SQL analysis and a compact executive dashboard, this project uncovers category level revenue drivers evaluates inventory health and highlights discount patterns that influence business performance. The final Power BI dashboard provides decision makers with a clear one page view optimized for quick insights and action.

## Project Overview
The objective of this project is to simulate a real world data analyst workflow by transforming raw inventory and sales data into actionable business insights. PostgreSQL was used to clean and analyze the dataset while Power BI was used to model metrics and build an executive level dashboard.

The analysis emphasizes:

- Revenue contribution by category
- Pricing and discount behavior
- Inventory availability and stock risk
- Overall sales and operational health

The outcome is a concise yet information dense dashboard suitable for leadership review.

## Business Problem

Quick commerce companies like Zepto operate on thin margins where pricing inventory availability and discounting must be carefully balanced. The business faces several challenges:

1. Identifying which categories drive the majority of revenue
2. Ensuring high in stock availability for high demand items
3. Avoiding excessive discounting that erodes margins
4. Monitoring inventory health at a category level
5. Providing leadership with fast and clear performance visibility

This project aims to answer these challenges using data driven analysis.

## Dataset & Source
**Dataset:** Zepto Product & Inventory Dataset <br>
**Rows:** 3,732 product records <br>
**Columns:** 9 product attributes including:

- **Product Identification:** Category, Product Name
- **Pricing & Discounts:** MRP, Discounted Selling Price, Discount Percentage
- **Inventory Management:** Available Quantity, Out of Stock status
- **Physical Attributes:** Weight in grams, Unit quantity
- **Target Metrics for Analysis:** Stock levels and pricing gaps
- **Source:** [Kaggle](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv)

## Methodology Used

The project followed a structured analytical approach

1. Loaded raw data into PostgreSQL for analysis
2. Performed basic data cleaning including removal of invalid records
3. Wrote SQL queries to calculate business metrics related to revenue pricing discounts and inventory
4. Created reusable DAX measures in Power BI for KPIs and visual consistency
5. Built a compact one page dashboard optimized for executive viewing

**Tools used**
- **PostgreSQL** for SQL querying and data preparation <br>
- **Power BI** for data modeling visualization and dashboarding

<br>

![Dashboard](https://github.com/Vidhisahay/Zepto-SQL-PowerBI-Analysis/blob/main/Visuals/Dashboard%20interface.png)

## About the Dashboard

The dashboard is designed as an executive summary view providing a holistic picture of Zepto’s performance. Key components include:

- KPI cards showing total revenue total quantity sold average price per unit and in stock rate
- Revenue by category bar chart highlighting top performing categories
- Inventory health donut chart showing in stock vs out of stock distribution
- Category level discount analysis to understand pricing strategy
- Interactive filters allow slicing by category price range and inventory status.

The dashboard prioritizes clarity simplicity and actionability.

## Answers to Business Questions
1. Is inventory availability healthy overall? <br>
    Yes at an overall level inventory health is strong but category level analysis reveals specific risk areas.

2. Are higher revenues driven by higher discounts? <br>
    Not always. Some high revenue categories rely on moderate discounts while others show heavy discounting with limited payoff.

3. Where are potential operational risks? <br>
    Categories with higher out of stock rates and lower revenue contribution represent operational inefficiencies.

## Business Recommendations

Based on the analysis the following recommendations can be made

- Prioritize inventory availability for top revenue generating categories to prevent lost sales
- Re evaluate discount strategies for categories with high discount rates but weak revenue impact
- Monitor out of stock rates at category level rather than relying only on overall inventory metrics
- Use combined pricing and inventory metrics to protect margins while sustaining demand

These actions can help improve revenue efficiency customer satisfaction and operational effectiveness.

## Acknowledgements

This project uses a publicly available dataset from Kaggle for educational and portfolio development purposes. The analysis is intended to simulate real world business scenarios and does not represent actual internal data from Zepto.

Thanks to the open source community and tools that made this analysis possible ❤️
