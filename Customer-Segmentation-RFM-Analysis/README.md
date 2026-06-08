# Customer Segmentation & RFM Analysis

## Project Overview

Customer segmentation is a business analytics technique used to group customers based on their purchasing behavior and value to the business. This project uses the Online Retail dataset to analyze customer purchasing patterns and prepare for RFM (Recency, Frequency, Monetary) Analysis.

The goal is to identify high-value customers, understand purchasing behavior, and generate actionable business insights that can support customer retention and marketing strategies.

## Objectives

* Analyze customer purchasing behavior.
* Identify key revenue-generating markets and products.
* Understand customer purchasing frequency and spending patterns.
* Prepare customer-level data for RFM Analysis.
* Generate actionable business recommendations.

## Dataset Information

The dataset contains online retail transaction records including customer purchases, product details, quantities, prices, and transaction dates.

### Features

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

## Project Workflow

### 1. Data Understanding

* Dataset dimensions
* Dataset structure
* Missing value analysis
* Duplicate analysis
* Descriptive statistics

### 2. Data Cleaning

* Removed missing CustomerID records
* Removed duplicate transactions
* Removed cancelled orders and returns
* Removed invalid pricing records
* Created TotalPrice feature

### 3. Exploratory Data Analysis (EDA)

#### Geographic Analysis

* Revenue by Country
* Top Revenue-Generating Countries

#### Product Analysis

* Top Products by Revenue
* Top Products by Quantity Sold

#### Sales Trend Analysis

* Monthly Revenue Trend

#### Customer Analysis

* Top Customers by Revenue
* Customer Purchase Frequency Analysis

## Dataset Transformation Summary

| Stage                                | Records |
| ------------------------------------ | ------: |
| Original Dataset                     | 541,909 |
| After Removing Missing Customer IDs  | 406,829 |
| After Removing Duplicates            | 401,604 |
| After Removing Returns/Cancellations | 392,732 |
| Final Clean Dataset                  | 392,692 |

## Key Findings

### Geographic Insights

* The United Kingdom generated the highest revenue by a substantial margin.
* The Netherlands, EIRE, Germany, and France were the strongest international markets.
* Revenue is heavily concentrated in the domestic market.

### Product Insights

* PAPER CRAFT, LITTLE BIRDIE was the highest revenue-generating product.
* PAPER CRAFT, LITTLE BIRDIE was also the most purchased product by quantity.
* Product revenue is concentrated among a relatively small number of items.

### Sales Trend Insights

* Revenue increased significantly throughout 2011.
* November 2011 recorded the highest monthly revenue.
* Strong seasonal demand was observed during the final quarter of the year.

### Customer Insights

* Revenue is concentrated among a small group of high-value customers.
* Customer 14646 generated the highest total revenue.
* Most customers placed only a few orders, while a small number of customers were highly active.

## Business Recommendations

* Strengthen customer retention efforts in the United Kingdom.
* Expand marketing activities in high-performing international markets.
* Maintain inventory availability for top-performing products.
* Develop loyalty programs for high-value customers.
* Prepare inventory and logistics resources for peak seasonal demand.

## Project Structure

```text
Project-3-Customer-Segmentation-RFM-Analysis/
│
├── data/
├── images/
├── notebooks/
│   └── Customer_Segmentation_RFM_Analysis.ipynb
├── requirements.txt
└── README.md
```

## Current Status

✅ Data Understanding Completed

✅ Data Cleaning Completed

✅ Exploratory Data Analysis Completed

🔄 RFM Analysis In Progress

## Future Work

* Recency Analysis
* Frequency Analysis
* Monetary Analysis
* RFM Scoring
* Customer Segmentation
* Segment-Level Insights
* Final Business Recommendations
