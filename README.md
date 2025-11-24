# Zepto Inventory Analysis – SQL Portfolio Project :

![Zepto image](https://github.com/user-attachments/assets/d594d37c-19b1-4b2f-aed3-cc08ec035ca2)

## Overview : 

This project presents a complete SQL-based analysis of a retail inventory dataset inspired by Zepto, a quick-commerce grocery delivery platform. The objective is to demonstrate analytical problem-solving using SQL while extracting actionable insights related to pricing, discounts, availability, unit-economics, and operational efficiency.

This case study follows a structured, business-focused approach—showcasing how SQL can be used to support real-world inventory decisions.

## Objectives :

Apply SQL to analyze retail inventory datasets

Identify revenue opportunities, pricing gaps, and stock issues

Perform category-level and product-level analytics

Demonstrate SQL query design aligned with business requirements

Produce insights that support data-driven decision-making

## Dataset :

Dataset Source: The dataset was sourced from Kaggle and was originally scraped from Zepto’s official product listings. It mimics what you’d typically encounter in a real-world e-commerce inventory system.

Columns :
  - Category
  - Name
  - Mrp
  - Discount_Percent
  - Available_Quantity
  - Discounted_SellingPrice
  - Weight_InGms
  - Out_of_Stock
  - Quantity

## Tools Used :

SQL (MS SQL Server)

Spreadsheet/CSV data

## Business Questions Addressed :

The project answers eight key business questions (as listed in the uploaded PDF):

- Top 10 best-value products based on discount percentage

- Products with high MRP that are out of stock

- Estimated revenue for each category

- All products with MRP > 500 and discount < 10%

- Top 5 categories with the highest average discount percentage

- Price-per-gram for products above 100g

- Weight-based product grouping (Low, Medium, Bulk)

- Total inventory weight per category

## Key Insights :

- Identified the Top 10 highest-discount products, highlighting value-driven SKUs for promotions.

- Detected high-MRP out-of-stock products, signaling revenue loss and stock gaps.

- Estimated category-level revenue, revealing which segments drive the most financial contribution.

- Found high-MRP items with minimal discounts, indicating potential pricing inefficiencies.

- Revealed the Top 5 discount-heavy categories, useful for margin and promotional planning.

- Calculated price-per-gram metrics, identifying best-value bulk items and unit-economics alignment.

- Classified products into Low, Medium, and Bulk weight groups to support warehouse operations.

- Aggregated total inventory weight per category, helping optimize storage and logistics.

## Recommendations :
-  Prioritize Replenishment of High-Value Out-of-Stock Products

Premium SKUs that are unavailable should be restocked urgently to avoid revenue leakage and maintain consistent customer experience.

-  Optimize Pricing and Promotions for High-MRP, Low-Discount Items

Products with high MRP but limited discounts represent an opportunity for improved pricing strategy or promotional depth to boost conversions.

-  Improve Warehouse Efficiency Through Weight-Based Product Classification

Using weight tiers (Low, Medium, Bulk) alongside category-level weight insights can optimize warehouse layout, picker routing, and delivery logistics.

## Conclusion :

This SQL Inventory Analysis project demonstrates how data-driven insights can significantly enhance decision-making in fast-commerce environments. By analyzing discount behavior, stock availability, revenue potential, unit-economics, and inventory weight distribution, the study uncovers practical opportunities to strengthen pricing strategies, operational efficiency, and inventory management.

## License
MIT — feel free to fork, star, and use in your portfolio.

## Thanks for checking out the project! Your support means a lot — feel free to star ⭐
