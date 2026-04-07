# Coffee Sales Analytics

A SQL-based data analysis project focused on extracting meaningful business insights from coffee sales data across Indian cities. This project uses a normalized relational database and SQL queries to analyze customer behavior, product demand, city-wise performance, revenue trends, and market opportunities.

## Project Overview

The main objective of this project is to analyze coffee sales data using SQL and generate insights that can support business decisions such as market expansion, product stocking, customer targeting, revenue optimization, and inventory planning.

The analysis is performed on a structured relational database containing data about cities, customers, products, and sales.

## Objectives

- Analyze coffee sales performance across different Indian cities
- Identify top-performing cities based on revenue and customer spending
- Find the best-selling coffee products
- Study customer segmentation by city
- Compare average sales with estimated rent for ROI-driven decisions
- Track monthly sales growth trends
- Generate strategic business recommendations from the data

## Tools and Technologies Used

- SQL
- Relational Database
- Joins
- Aggregation Functions
- Group By
- Filtering
- Ranking Functions
- Common Table Expressions (CTEs)

## Database Structure

The project is built on four main tables:

### 1. city
Contains city-level details such as:
- city_id
- city_name
- population
- estimated_rent
- city_rank

### 2. customers
Contains customer-related information:
- customer_id
- customer_name
- city_id

### 3. products
Contains the coffee product catalog:
- product_id
- product_name
- price

### 4. sales
Contains transaction-level sales data:
- sale_id
- sale_date
- product_id
- customer_id
- total
- rating

These tables are connected using foreign keys, enabling multi-table SQL analysis.

## Key Analyses Performed

### Estimated Coffee Consumers by City
Estimated coffee consumers were calculated using the assumption that 25% of the city population drinks coffee. This helped identify cities with high market potential.

### Total Revenue Analysis
Revenue was analyzed for the last quarter of 2023 to identify the best-performing cities.

### Product Sales Count
Sales count for each product was calculated to determine top-selling items.

### Average Sales Amount per City
Average customer spending was measured for each city to identify premium markets.

### Customer Segmentation by City
Unique customer counts were analyzed to understand customer reach and engagement by location.

### Average Sale vs Rent
Average sales per customer were compared with city rent to evaluate cost efficiency and business expansion opportunities.

### Monthly Sales Growth
Monthly sales trends were analyzed to detect growth patterns, fluctuations, and seasonal opportunities.

### Top Selling Products by City
Product preferences were studied city by city to support localized inventory and marketing strategies.

## Key Insights

- Pune generated the highest revenue in Q4 2023 and showed the best overall profitability.
- Chennai and Bangalore also performed strongly in terms of average customer spending and overall sales.
- Cold Brew Coffee Pack, Ground Espresso Coffee, and Instant Coffee Powder were the top-selling products.
- Delhi, Mumbai, and Kolkata had the highest estimated number of coffee consumers based on population.
- Chennai, Bangalore, and Delhi showed strong customer reach through high unique customer counts.
- Ahmedabad showed inconsistent but sometimes strong monthly sales growth, indicating seasonal demand patterns.
- Pune had the best balance between average sales per customer and rent, making it a strong city for expansion.

## Business Recommendations

- Prioritize Pune for business expansion due to strong profitability and cost efficiency.
- Focus promotions and inventory planning on top-selling products such as Cold Brew, Espresso, and Instant Coffee Powder.
- Use city-specific product strategies based on local preferences.
- Launch loyalty and retention campaigns in cities with high unique customer counts.
- Plan marketing and stock movement based on monthly demand trends in volatile cities.

## Example SQL Concepts Used

This project applies a variety of SQL concepts, including:

- INNER JOIN
- LEFT JOIN
- GROUP BY
- ORDER BY
- COUNT()
- SUM()
- ROUND()
- DISTINCT
- DENSE_RANK()
- CTEs
- EXTRACT() for year and quarter filtering

## Business Value

This project demonstrates how SQL can be used to transform raw sales data into actionable business insights. It highlights the role of data analysis in improving strategic planning, customer targeting, and operational decision-making in a retail environment.

## Author

Sahil Maurya

## Repository Description

SQL-based coffee sales analysis project that uncovers city-wise revenue trends, top-selling products, and customer insights using relational database queries.
