# Retail-Store-Data-Analysis
## Project Overview
#### This project analyses the detail of the customers and companies that have purchased from a retail store, giving the monthly revenue of the store between a number of given years.
---
## Table of Contents
+ [Project Overview](#project-overview)
+ [Dataset Description](#dataset-description)
+ [Objectives](#objectives)
+ [Tools Used](#tools-used)
+ [Data Cleaning and Preparation](#data-cleaning-and-preparation)
+ [Analysis and Insights](#analysis-and-insights)
  1. [Excel Analysis](#excel-analysis)
  2. [SQL Queries](#sql-queries)
  3. [Power BI Dashboard](#power-bi-dashboard)
+ [Key Findings](#key-findings)
+ [Screenshots/Dashboard Previews](#screenshots/dashboard-previews)
+ [Conclusion](#conclusion)
---
## Dataset Description
#### This dataset contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011. The dataset was gotten from kaggle and it contains 1,067,371 rows and 8 columns namely; invoice number, stock code, quantity, invoice date, unit price, customer ID and country.
---
## Objectives
1. Clean missing values and remove duplicates.
2. Create calculated columns: e.g., TotalPrice = Quantity * UnitPrice.
3. Observe the store's Monthly Revenue
4. Highlight the store's top customers by sales and by number of orders
5. Track repeat customers VS one-time customers
6. Observe top countries by number of customers
7. Identify top countries by revenue
8. Detect any cancellations (negative quantity)
---
## Tools Used
1. Excel (Pivot and dashboard)
2. SQL
3. Power Query and Power BI
---
## Data Cleaning and Preparation
#### The dataset contained a lot of missing values, and the dataset being a sales data means a carefully done data preprocessing.
#### I created a column first to calculate the total price for each record, then I dropped every record whose total price returned zero.
#### Then, I filtered and checked for other missing values and I replaced them with either zero or "null" for numbered fields and text fields respectively.
---
### Analysis and Isights
#### After cleaning the dataset, I went ahead to analyze using the following tools, keeping in mind the objectives of this project. While cleaning, I realized that dropping the fields that contained the null values would be detrimental to the analysis, so the result still shows the outcome of the null values.
## Excel Analysis
[Pivotting](https://ibb.co/Q3zFNYP8)
### Insights
+ There were more sales made in the united kingdom
+ More sales were made in November across all years considered
## SQL Queries
[Queries](https://ibb.co/Wvj1smts)
### Insights
+ [Top 5 countries bym sales- United KIngdom being the first](https://ibb.co/v6qj86yf)
+ [Detecting negative quantities](https://ibb.co/Tqb00Zv5)
## Power BI Dashboard
[Total Revenue by Month and Sum of Quantity](https://ibb.co/svXLCmrW)
### Insights
+ More sales were made in November across all years considered
---
## Key Findings
+ The store's monthly revenue shows that the store sold more in November [See it here](https://ibb.co/6JrDMyGn)
+ The store's top customers by sales and number of orders can be seen [here](https://ibb.co/ZRbKXKtR) and [here](https://ibb.co/YmtXGPj)
+ Repeat Customers vs one-time customers respectively. [Click for repeat](https://ibb.co/Q7KWbbXF) [Here for one-time](https://ibb.co/zVqkK4kQ)
+ Top countries by total revenue [Click to see](https://ibb.co/1GkZy7q4)
+ Top countries by number of customer [here](https://ibb.co/DfxX1xph)
---
## Dashboard Previews
1. [Excel Dashboard](https://ibb.co/YY5PBMb)
2. [Power BI Dashboard](https://ibb.co/kVzVd4SC)
---

