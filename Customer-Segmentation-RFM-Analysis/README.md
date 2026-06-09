# Customer Segmentation & RFM Analysis

## Project Overview

Customer segmentation is a business analytics technique used to group customers based on their purchasing behavior and overall value to the business. This project analyzes online retail transaction data using RFM (Recency, Frequency, Monetary) Analysis to identify customer segments and generate actionable business insights.

The objective is to understand customer purchasing patterns, identify high-value customers, and support data-driven customer retention and marketing strategies.

## Objectives

* Analyze customer purchasing behavior.
* Identify key revenue-generating markets and products.
* Understand customer engagement and spending patterns.
* Perform RFM Analysis to measure customer value.
* Segment customers into meaningful business groups.
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

### 4. RFM Analysis

* Recency Analysis
* Frequency Analysis
* Monetary Analysis
* RFM Scoring

### 5. Customer Segmentation

* Champions
* Loyal Customers
* Potential Loyalists
* At-Risk Customers
* Lost Customers

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
* Revenue is heavily concentrated within the domestic market.

### Product Insights

* PAPER CRAFT, LITTLE BIRDIE was the highest revenue-generating product.
* PAPER CRAFT, LITTLE BIRDIE was also the most purchased product by quantity.
* Product revenue is concentrated among a relatively small number of products.

### Sales Trend Insights

* Revenue increased significantly throughout 2011.
* November 2011 recorded the highest monthly revenue.
* Strong seasonal demand was observed during the final quarter of the year.

### Customer Insights

* Revenue is concentrated among a small group of high-value customers.
* Customer 14646 generated the highest total revenue.
* Most customers placed only a few orders, while a small number of customers were highly active purchasers.

### Segmentation Insights

| Segment             | Customers |
| ------------------- | --------: |
| Lost Customers      |     1,504 |
| Champions           |     1,317 |
| Potential Loyalists |       665 |
| At Risk             |       646 |
| Loyal Customers     |       206 |

* Lost Customers formed the largest customer segment.
* Champions represented a substantial portion of the customer base.
* Potential Loyalists present opportunities for future growth.
* At-Risk Customers require proactive retention efforts.

## Business Recommendations

### Customer Retention

* Re-engage Lost Customers through targeted campaigns and promotional offers.
* Monitor At-Risk Customers and provide personalized incentives to encourage repeat purchases.

### Customer Loyalty

* Reward Champions with exclusive benefits and loyalty programs.
* Strengthen relationships with Loyal Customers through personalized marketing initiatives.

### Revenue Growth

* Focus marketing efforts on Potential Loyalists to increase customer lifetime value.
* Promote high-performing products through cross-selling and bundled offers.

### Market Expansion

* Continue strengthening operations within the United Kingdom.
* Expand marketing activities in high-performing international markets such as the Netherlands, Germany, France, and EIRE.

### Seasonal Planning

* Increase inventory and operational readiness before peak sales periods, particularly during the final quarter of the year.

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

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Customer Analytics
* Revenue Analysis
* RFM Analysis
* Customer Segmentation
* Data Visualization
* Business Insight Generation
* Strategic Business Recommendations

## Conclusion

This project demonstrates how transaction-level retail data can be transformed into actionable customer insights using RFM Analysis and customer segmentation techniques. The results provide a structured framework for identifying valuable customers, improving retention strategies, and supporting data-driven business decisions.
## Author
Harsh Poonia

MCA Student | Aspiring Data Analyst | Data Science Enthusiast
