# Retail Sales and Profitability Performance Analysis

## Project Overview

This project was completed as part of a Capstone Project Internship
Program.

The objective is to analyze retail sales and profitability performance
across products, regions, customer segments, time periods, discounts,
and shipping modes. The project follows an end-to-end business analytics
workflow from data exploration and cleaning to analysis, visualization,
predictive modeling, business insights, and recommendations.

## Problem Statement

The retail business operates across multiple regions, product
categories, customer segments, and stores. The analysis focuses on
identifying: - Products and categories contributing most to sales and
profit - Strong-performing regions - Customer segments contributing most
to sales - The relationship between discounts and profitability -
Stronger-performing months - Shipping mode performance - Opportunities
to improve sales and profitability

## Tools Used

- **SQL** - Data exploration, cleaning, validation, and ETL
- **Python** - Exploratory Data Analysis, visualization, correlation
  analysis, and Linear Regression
- **Power BI** - Interactive dashboard and business performance
  visualization

## Dataset Overview

- **Analysis Period:** January-July 2025
- **Cleaned Records:** 47
- **Variables:** 13

The dataset includes Order Date, Region, State, Store, Product Category,
Product Name, Customer Segment, Sales, Quantity, Discount, Profit, and
Shipping Mode.

## Project Workflow

1.  Business Understanding
2.  Dataset Exploration
3.  Data Cleaning
4.  ETL Process
5.  Exploratory Data Analysis
6.  Data Visualization
7.  Correlation Analysis
8.  Linear Regression Modeling
9.  Power BI Dashboard Development
10. Business Insights and Recommendations

## Key Findings

### 1. Monthly Performance

May recorded the strongest monthly performance with approximately
**₹421K in sales** and **₹50.8K in profit**.

### 2. Regional Performance

The **West region** generated the highest sales, while the **East
region** recorded the highest profit margin.

### 3. Product and Category Performance

**Office Supplies** was the leading product category by sales, while
**Markers** were among the leading individual products by sales
contribution.

### 4. Customer Performance

The **Consumer segment** generated the highest sales and order volume,
while the **Home Office segment** recorded the highest profit margin.

### 5. Discount and Profitability

Higher discount levels were associated with lower profitability.
Discount and Profit showed a negative correlation of approximately
**-0.28**.

### 6. Shipping Performance

**Same Day shipping** generated the highest sales, while profit margins
remained relatively similar across shipping modes.

## Model Used

### Linear Regression

A Linear Regression model was developed to evaluate monthly sales trends
and estimate future sales.

### Model Evaluation

- **R² Score:** -2.827
- **MAE:** approximately ₹103.8K
- **RMSE:** approximately ₹125.9K

The negative R² score indicates weak predictive performance on the
available test data. Since the dataset contains only seven months of
monthly observations, the next-month prediction should be treated as
experimental rather than a reliable business forecast.

## Business Recommendations

- Monitor Sales, Profit, and Profit Margin together when evaluating
  discount strategies.
- Study the product, region, and customer mix that contributed to May’s
  strong performance.
- Evaluate regional performance using multiple KPIs rather than sales
  alone.
- Develop segment-specific strategies by considering both sales
  contribution and profitability.
- Continue monitoring high-contributing products while investigating
  underperforming products.
- Collect a longer period of historical data before using predictive
  models for business forecasting.

## Power BI Dashboard

The Power BI dashboard contains four analytical pages: 1. Executive
Overview 2. Sales & Profitability Analysis 3. Customer & Order Analysis
4. Business Insights & Recommendations

A public Power BI dashboard link is not included because public sharing
is not available for the account used for this project.

**Dashboard screenshots are included in the final project report**,
showing all four Power BI dashboard pages and their key visual findings.

## Project Files

- Python / Jupyter Notebook (`.ipynb`)
- Cleaned Dataset
- SQL Database / ETL Work
- Power BI Dashboard
- Dashboard Screenshots in the Final Project Report
- Final Project Report

## Author

**ASHIFA A.**

Capstone Project - Internship Program
