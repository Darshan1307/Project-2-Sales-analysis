# Project-2-Sales-analysis using PYTHON


# Sales Insights from Sales Data

## Overview

This repository contains the code and analysis for exploring sales data, aiming to extract insights about sales patterns, product performance, and customer behavior. The analysis covers key questions such as:

Best month for sales

Cities with highest sales

Optimal advertisement timings

Frequently co-purchased products

Top-selling products

Factors influencing product sales

## Data Source

The data was sourced from CSV files located in the Sales_Data directory, containing information about orders, products, quantities, prices, and customer addresses.

## Data Cleaning

The following cleaning steps were performed:

Removing rows with missing values

Filtering out non-numeric data from order dates

Converting data types to appropriate formats (e.g., numeric for quantities and prices)

Extracting month and hour information from order dates

Deriving city and state information from purchase addresses

## Data Exploration

The analysis addressed several key questions:

1. Best Month for Sales

December was the best month for sales, generating $4,613,443 in revenue.
Visual representation: Bar plot of sales by month: ./figures/sales_by_month.png

2. Cities with Highest Sales

San Francisco (CA) had the highest sales, totaling $8,262,204.
Visual representation: Bar plot of sales by city: ./figures/sales_by_city.png

3. Optimal Advertisement Timings

12:00 PM (noon) is the most opportune time to display advertisements, coinciding with peak order frequency.
Visual representation: Line plot of order frequency by hour: ./figures/order_frequency_by_hour.png

4. Frequently Co-Purchased Products

The most commonly co-purchased product pairs are:
iPhone and Lightning Charging Cable
MacBook Pro Laptop and Apple Magic Mouse
Google Phone and Wired Headphones

5. Top-Selling Products

The best-selling product is AAA Batteries (4-pack), with 30544 units sold.
Visual representation: Bar plot of quantity sold by product: ./figures/quantity_sold_by_product.png

6. Factors Influencing Product Sales

Price appears to play a significant role, as the top-selling product is also one of the least expensive.
