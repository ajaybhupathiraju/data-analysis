# data-analysis
This repository contains all my data explorations and anaysis

# Table of Contents
- Project Overview
- Data Sources
- Recommendations

## Project Overview
  
  This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we     seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.
  
## Data Sources

Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each sale made by the company.

## Tools
- CSV
- PostgreSQL - Data Analysis
- PowerBI    - Visuvalization reports

## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:

    1. Data loading and inspection.
    2. Handling missing values.
    3. Data cleaning and formatting.

## Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:

    1. What is the overall sales trend?
    2. Which products are top sellers?
    3. What are the peak sales periods?

## Data Analysis
Include some interesting code/features worked with
```sql 
SELECT * FROM table1
WHERE cond = 2;
```
## Results/Findings

The analysis results are summarized as follows:

    1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
    2. Product Category A is the best-performing category in terms of sales and revenue.
    3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

## Recommendations

Based on the analysis, we recommend the following actions:

    Invest in marketing and promotions during peak sales seasons to maximize revenue.
    Focus on expanding and promoting products in Category A.
    Implement a customer segmentation strategy to target high-LTV customers effectively.

## Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.
