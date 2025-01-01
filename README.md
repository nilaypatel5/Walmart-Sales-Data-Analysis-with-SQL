# Walmart Sales Data Analysis with SQL

## Overview

This project involves performing an in-depth analysis of the **Walmart Sales Data** using SQL. The analysis focuses on various metrics, such as total sales, revenue by product line, customer demographics, and sales trends across cities and branches. Using SQL queries, I explored key insights from the dataset, which includes sales transactions, product performance, and customer behavior.

## Dataset

The project uses the **WalmartSalesData.csv** dataset, which contains transactional data from Walmart.

### Columns in the Dataset:
1. **Invoice_ID**: Unique identifier for each sale transaction
2. **Branch**: The branch of Walmart where the transaction took place
3. **City**: The city where the transaction occurred
4. **Customer_type**: Type of the customer (e.g., Member or Non-Member)
5. **Gender**: Gender of the customer
6. **Product_line**: The product line purchased (e.g., Electronics, Groceries)
7. **Unit_price**: Price per unit of the product
8. **Quantity**: The quantity of the product purchased
9. **Tax_5%**: The tax (5%) applied to the transaction
10. **Total**: The total cost (including tax) of the transaction
11. **Date**: The date of the transaction
12. **Time**: The time of the transaction
13. **Payment**: Payment method used (e.g., Credit, Debit)
14. **COGS**: Cost of goods sold for the product
15. **Gross_margin_percentage**: Gross margin percentage of the sale
16. **Gross_income**: Gross income from the sale
17. **Rating**: Customer's rating for the product purchased

## Analysis Overview

In this analysis, I explored and derived several insights from the Walmart sales data using SQL queries. The analysis includes:

1. **Total Sales per Product Line:**  
   I calculated the total sales for each product line by summing up the total cost of each transaction. This helped in understanding which product lines generated the most revenue.

2. **Sales Transactions by Payment Method:**  
   I counted the number of transactions for each payment method to see which methods were most popular among customers. This provided insight into customer payment preferences.

3. **Customer Count by Gender:**  
   I analyzed how many customers of each gender made purchases to determine gender-based purchasing patterns. This was useful for understanding gender demographics in relation to product sales.

4. **Revenue and Gross Margin by Product Line:**  
   I calculated the total revenue and average gross margin percentage for each product line. This helped in understanding the performance of various product lines, especially in terms of profitability.

5. **Highest Gross Income by Branch:**  
   I identified which branch generated the highest gross income during a specific date range. This allowed for branch-specific performance analysis, helping to identify high-performing branches.

6. **Branches with High Sales Quantities:**  
   I found branches that had sold more than the average quantity of products. This analysis helped to highlight which branches were performing better in terms of product sales volume.

7. **Top Products by Revenue and Rating:**  
   I retrieved the top 5 products based on total revenue and average ratings. This analysis provided insights into the most successful product lines, considering both revenue and customer satisfaction.

8. **Sales by City and Gender:**  
   I calculated total sales and average ratings by city and gender. This allowed me to compare how sales and customer satisfaction varied by city and gender, revealing possible geographic and demographic trends.

9. **Sales and Gross Income by Product Line and City with Rating Filter:**  
   I filtered cities with average ratings above 4 and calculated total sales and gross income by product line and city. This helped identify the best-performing cities and products, based on both sales figures and customer ratings.

10. **Revenue and COGS Breakdown by Gender, Payment Method, and Product Line:**  
   I broke down total revenue, Cost of Goods Sold (COGS), and gross income by gender, payment method, and product line. This provided a more detailed view of the sales dynamics and helped in understanding the relationship between sales, costs, and profit across different customer groups and product lines.



