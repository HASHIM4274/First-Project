# First-Project
## Project Overview

This project is focused on analyzing a simplified Bike Store dataset using  that I downloaded from [KAGGLE](https://www.kaggle.com/datasets/dillonmyrick/bike-store-sample-database/code) using **SQL Server Management Studio (SSMS)**.

It demonstrates how SQL can be used to explore and answer real-world business questions related to E-commerce product product analytics and give insights to help drive business decisions.

## Project Description

This analysis uses clean and normalized datasets across the following tables:

- `brands` – Contains unique brand IDs and brand names.
- `categories` – Contains category IDs and category names.
- `customers` – Contains unique customer IDs and customer details including `first_name`, `last_name`, `phone`, `email`, `street`, `city`, `state` and `zip_code`.
- `products` – Contains product details including `product_name`, `price`, `stock_quantity`, and foreign keys `brand_id` and `category_id`.\
- `order item` - Contains product details including `order_id`, `item_id`, `product_id`, `quantity`, `list_price` and `discount`.
- `orders` - Contains details such as `order_id`, `customer_id`, `order_status`, `order_date`, `required_date`, `shipped_date`, `store_id`, `staff_id`.
- `staffs` - Contains details such as `staff_id`, `first_name`, `last_name`, `email`, `phone`, `store_id`, `manager_id`.
- `stores` - Contains details such as `store_id`, `store_name`, `phone`, `email`.

The database design follows normalization principles and is ideal for SQL practice and business intelligence reporting.


## Objectives
The objective of this project is to develop and sharpen my sql skill by answering business questions to help make data driven decisions;
- Explore product distribution by brand and category
- Identify top-performing brands by product count or price range
- Detect understocked or overstocked categories
- Gain insights into pricing trends and inventory levels
- Demonstrate SQL proficiency for portfolio purposes


## Skills Used
I will be using the following set skills to achieve my objectives
- SQL Server (T-SQL)
- Joins (`INNER JOIN`)
- Aggregations (`COUNT`, `SUM`, `AVG`, `MIN`, `MAX`)
- Filtering (`WHERE`, `HAVING`)
- Sorting and ranking
- Subqueries and `TOP N` logic

---

## The following Key Business Questions Answered in order to achieve my objectives:

- Which brands have the most products listed?
- What is the average price of products in each category?
- Which categories are low on stock?
- What are the top 5 most expensive products and their brands/categories?
- What is the price range for each brand?
