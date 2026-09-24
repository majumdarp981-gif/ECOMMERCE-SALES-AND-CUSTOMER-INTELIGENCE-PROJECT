# ECOMMERCE-SALES-AND-CUSTOMER-INTELIGENCE-PROJECT
An Excel-based data analytics project focused on understanding sales performance, customer purchasing behavior, product revenue, and marketing channel performance.
The analysis uses the Maven Fuzzy Factory e-commerce dataset and was built using Microsoft Excel, Power Query, Power Pivot, DAX, PivotTables, and Charts.

## Business Objective

The main goal of this project was to understand how the e-commerce business was performing across sales, customers, products, and marketing channels.
I wanted to find out where the revenue was coming from, how customers were purchasing, which products were contributing the most, and how different marketing sources were performing in terms of conversions.
The analysis was also used to identify areas where the business could improve customer retention, product performance, and marketing effectiveness.

## Dataset & Tools

### Dataset

This project uses the **Maven Fuzzy Factory** e-commerce dataset. It contains data related to orders, order items, products, website sessions, website pageviews, and refunds.
I used these tables to analyze sales performance, customer purchasing behavior, product revenue, and marketing channel performance.

### Tools & Technologies
- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- Excel Charts
## Data Preparation & Analysis

I first reviewed the available tables and prepared the data using Power Query. This included checking for duplicate records, correcting data types, transforming columns, and preparing the data for analysis.
Relevant tables were grouped and merged to connect orders, customers, products, and website sessions. This helped create the datasets required for customer, product, sales, and marketing analysis.

### Analysis Performed

- Sales and order performance
- Customer purchasing behavior
- Product revenue contribution
- Marketing channel revenue
- Conversion rate by UTM source
- Customer order frequency
## Dashboard

I created an Excel dashboard to bring the main findings together in one place.
The dashboard includes KPI cards and visualizations covering:

- Total Revenue
- Total Orders
- Unique Customers
- Conversion Rate
- Repeat Purchase Rate
- Revenue by UTM Source
- Revenue Contribution by UTM Source
- Conversion Rate by UTM Source
- Revenue by Product
- Revenue Contribution by Product
- Customers by Order Frequency
## Key Insights

### 1. Most customers made only one purchase

Out of 31,696 customers, 31,105 customers made only one purchase, while 565 customers made two purchases and 26 customers made three purchases.
This shows that repeat purchasing was limited, creating an opportunity to improve customer retention and encourage additional purchases.

### 2. Revenue was highly concentrated in one product

The Original Mr. Fuzzy generated approximately $1.21M, contributing around 62.5% of total revenue.
The remaining three products contributed a much smaller share of overall revenue, indicating a strong concentration of sales around the leading product.

### 3. Marketing channels performed differently

gsearch generated the highest revenue at approximately $1.28M and also recorded the highest number of conversions.
At the same time, socialbook had the lowest conversion rate at 3.21%, compared with the overall conversion rate of 6.83%.
This highlights the importance of evaluating marketing channels using both revenue and conversion performance rather than looking at a single metric.
## Business Recommendations

Based on the analysis, the following areas could be considered for further business action:

- Improve customer retention: Use post-purchase communication, personalized product recommendations, and targeted offers to encourage one-time customers to make another purchase.

- Build around the leading product: Since The Original Mr. Fuzzy contributes a large share of revenue, its availability should be monitored while also exploring cross-selling opportunities with other products.

- Evaluate marketing channels together: Marketing sources should be compared using both revenue and conversion rate. The lower conversion rate observed for socialbook could be investigated further to understand whether targeting, traffic quality, or campaign performance is contributing to the difference.

- Reduce revenue concentration: Increasing the contribution of other products could help create a more balanced product revenue mix over time.


### Main File

ECommerce_Sales_Customer_Intelligence.xlsx contains the Excel analysis, including Power Query transformations, Power Pivot/DAX calculations, PivotTables, and the final dashboard.
