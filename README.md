# Sales_Data_Project

### Project Overview
---
This project generates sales performance of a retail store by different regions. By analysing the various parameters in the data received, we seek to gather enough insight such as top selling products, regional performance and monthly sales trend. The goal is to enable us tell compelling stories that highlights all of the insights gathered.

### Data Collected
---
The dataset includes the following columns:

- Order Id:  The identification number for a particular order.
- Customer Id: The identification number for a customer.
- Product: The name of product being sold.
- Region: The geographical area where the store is located.
- Order Date: The exact date the product was ordered.
- Quantity: The quantity of product sold.
- Unit Price: The exact price for each unit of products.

### Data Cleaning and Preparation
---
In the initial stage of Cleaning this data and preparations, we performed the following actions
1. Data Loading and Inspection
2. Removing Duplicates in the dataset
3. Data Cleaning and formatting

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. For Visualization
     
- SQL - Structured Query Language
- Power BI for Visualization
- GitHub for Portfolio Building

### Project Objective
---
This project aims to address the following analysis goals;
- Exploration of the sales data
- Summarize the Total sales by product,region and month
- Average sales per product: Calculate the average sales per product
- Total Revenue by Region: Calculate the total revenue of each sales in each region
- Total Sales per Product: Retrieve the total sales for each product category in each region
- Sales transaction by Region: Find the number of sales transactions in each regions
- Find the highest selling product by total sales value
- Calculate total revenue per product
- Find the top 5 customers by total purchase amount
- Calculate the percentage of total sales contributed by each region
- Identify Products with no sales in the last quarter
   
### Exploratory Data Analysis [EDA]
---
EDA involves the exploring of the Data to answer some questions about the Data such as;

- What are the top selling products
- What are the regional performances
- What are the monthly sales trend

### Data Analysis
---
At this point was where we included some basic lines of function in Excel, some queries in SQL and even some DAX [Data Analysis Expression] functions were used in the analysis

### Insights
---
- Total sales per product: Sum of the Unit_Price column, grouped by product
- Sales transactions by region: Count of Order Id column,grouped by Region
- Highest selling product by total sales value: selected the top 1 from product summing Unit_Price as Total Sales grouped by product,order by Total Sales in Descending order
- Total Revenue per product: Sum of Unit_Price as Total Revenue, grouped by Product
- Monthly Sales Total by current year: Selected the month from OrderDate column as Month, Sum of Unit_Price as MonthlySales where year equals current yea, grouped by Month, Order by Month
- Top 5 customers by total purchase amount: Selected the top 5 from CustomerId column, sum of Unit_Price column as TotalPurchase, grouped by CustomerId, order by TotalPurchase in Descending order
- Total Sales Percentage by Region: Selected sum of Unit_Price column as TotalSalesAmount, selected Region then sum of Unit_Price column as RegionSales, grouped by Region
- Products without sales in last Quarter: Selected Product column from the dataset, grouped by Product column having maximum in OrderDate column lessthan Dateadd and Quarter
  
 



   

