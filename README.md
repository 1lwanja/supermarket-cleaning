# supermarket-cleaning
Supermarket Sales Analysis
Introduction

This project aims to perform an analysis of supermarket sales data using SQL. The dataset contains information about various sales transactions, including invoice details, branch information, customer demographics, product details, pricing, taxes, payment information, and customer ratings. The project will focus on data cleaning and preprocessing, as well as data filtering and aggregation techniques to derive meaningful insights from the dataset.

Dataset Overview

The dataset consists of the following columns

Invoice_ID: Unique identifier for each sales transaction.
Branch: Branch code where the sale occurred.
City: City where the sale occurred.
Customer_type: Type of customer (e.g., Member, Normal).
Gender: Gender of the customer.
Product_line: Category of the product sold.
Unit_price: Price of a single unit of the product.
Quantity: Number of units sold.
Tax: Tax amount applied to the sale.
Total: Total amount of the sale including tax.
Date: Date of the sale.
Time: Time of the sale.
Payment: Payment method used (e.g., Cash, Credit Card).
cogs: Cost of goods sold.
gross_margin_percentage: Gross margin percentage.
gross_income: Gross income generated from the sale.
Rating: Customer satisfaction rating for the sale.
Data Cleaning and Preprocessing

Data cleaning and preprocessing are essential steps to ensure the quality and consistency of the dataset. In this project, the following data cleaning and preprocessing techniques were applied.

Handling missing values: Missing values in any of the columns were identified and appropriate actions, such as imputation or removal, were taken.
Removing duplicates: Duplicate records, if any, were identified and removed to avoid redundant data.
Data type conversion: The data types of certain columns were adjusted to match the nature of the data they represent, such as converting date and time columns into the appropriate data types.
Data normalization: Certain columns were normalized to ensure consistency and standardization across the dataset, such as converting the city names to a standardized format.
Handling outliers: Outliers in numeric columns were identified and treated using suitable techniques, such as capping or excluding them from analysis.
Data Filtering and Aggregation

Data filtering and aggregation techniques are used to extract specific subsets of data and derive meaningful insights from them. In this project, the following techniques were applied.

Filtering by date: The dataset was filtered based on a specific date range or specific days of the week to focus on sales patterns during certain periods.
Filtering by branch or city: The dataset was filtered to analyze sales performance at specific branches or cities.
Aggregating sales data: Various aggregation functions, such as SUM, COUNT, AVERAGE, and MAX, were applied to calculate key metrics like total sales, average unit price, total tax, and gross income.
Grouping and sorting: The dataset was grouped by specific columns (e.g., product line, customer type) and sorted based on certain criteria (e.g., sales volume, gross income) to identify trends and patterns.
