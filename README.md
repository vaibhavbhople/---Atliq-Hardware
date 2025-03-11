# Atliq Hardware Data Analysis
## Overview
Atliq Hardware is a leading computer hardware manufacturer based in India, with a global presence across 27 countries. The company serves 74 clients in key markets such as Asia Pacific (APAC), Europe (EU), North America (NA), and Latin America (LATAM). Atliq Hardware's management identified the need to make quick and data-informed decisions. In response, the Data Analytics team was tasked with delivering 10 ad hoc reports to address various business needs.

This repository showcases the process and SQL queries used to deliver these ad hoc reports and present actionable insights for the management team.

## Objective
The primary objective of this project was to deliver ad hoc reports as per the management’s requests and to create an insightful presentation that highlights these findings. The insights gathered from these reports will help inform key business decisions such as market expansion, product diversification, strategic marketing, and cost optimization.

## Steps Followed
▪ Data Extraction: The data was extracted into a SQL database using the IMPORT method.

▪ Data Understanding: The team analyzed the Fact and Dimension tables to gain an understanding of the data structure.

▪ Ad Hoc Requests: The management provided 10 ad hoc requests for the analysis.

▪ Database Relationships: Reverse engineering was used to define proper relationships between the Dimension and Fact tables, resulting in an ERD (Entity-Relationship Diagram).

▪ SQL Queries: Crafted SQL queries to address the specific ad hoc requests from the management.

▪ Reporting: The team presented the ad hoc reports to the stakeholders, ensuring the insights were actionable.

## Database Structure
#### Atliq Hardware's database is structured as follows:

### Tables:
▪ dim_customer: Stores customer details (IDs, names, regions, etc.)

▪ dim_product: Holds product information (IDs, names, categories, specs)

▪ fact_gross_price: Tracks product gross prices and revenue

▪ fact_manufacturing_cost: Records product manufacturing costs (materials, labor)

▪ fact_pre_invoice_deductions: Details pre-invoice deductions like discounts

▪ fact_sales_monthly: Tracks monthly sales data (units sold, revenue)

This database structure allows Atliq Hardware to effectively analyze customer, product, pricing, cost, and sales data for informed decision-making.

## SQL Concepts Used
#### Several SQL concepts were applied to generate the required reports and insights:

▪ SELECT, DISTINCT, WHERE, HAVING, GROUP BY clauses: To filter and aggregate the data.

▪ Aggregation Functions: MIN(), MAX(), AVG() for computing summaries.

▪ CASE-WHEN-THEN Statements: For conditional logic.

▪ Joins: To combine multiple tables based on defined relationships.

▪ Subqueries & CTE (Common Table Expressions): To break down complex queries.

▪ Window Functions: RANK(), PARTITION BY for advanced analytics.

## Recommendations
#### The analysis provided several key recommendations for the management team to consider:

▪ Enhance Market Penetration: Expand operations strategically in high-potential APAC markets.

▪ Product Diversification: Focus on diversifying the product portfolio, especially in high-performing segments like Accessories.

▪ Strategic Marketing: Tailor marketing strategies for each product segment based on performance insights.

▪ Cost Optimization: Review products with the highest manufacturing costs to identify opportunities for cost optimization.

▪ Customer Relationship Management: Strengthen relationships with top customers through loyalty programs or exclusive offerings.

▪ Sales Forecasting: Leverage sales data for more accurate forecasting, helping in inventory management.

▪ Strategic Sales Focus: Prioritize sales efforts based on channel contribution, focusing on retailers and direct channels.

▪ Product Performance Analysis: Continuously monitor the performance of top products to stay ahead of market trends.

## Gratitude
Special thanks to Dhaval Patel, Hemanand Vadivel, and Team Codebasics for providing this enriching opportunity to refine my SQL skills and gain hands-on experience in real-world data analysis.
