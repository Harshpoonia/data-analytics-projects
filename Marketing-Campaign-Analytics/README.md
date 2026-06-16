# Marketing Campaign Analytics

## Project Overview

Marketing campaigns are essential for customer engagement, retention, and revenue growth. This project analyzes customer demographics, purchasing behavior, campaign responses, and purchase channel preferences to evaluate marketing effectiveness and identify opportunities for business improvement.

The analysis focuses on understanding customer characteristics, spending patterns, campaign performance, and purchasing channels to generate actionable business recommendations.

## Objectives

* Analyze customer demographics and purchasing behavior.
* Evaluate marketing campaign effectiveness.
* Identify factors influencing customer spending.
* Measure customer engagement with marketing campaigns.
* Analyze purchase channel preferences.
* Develop data-driven business recommendations.

## Dataset Information

The dataset contains customer demographic information, purchasing behavior, and marketing campaign response data.

### Features

#### Customer Information

* Year_Birth
* Education
* Marital_Status
* Income
* Kidhome
* Teenhome

#### Customer Behavior

* Recency
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth

#### Product Spending

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

#### Marketing Campaigns

* AcceptedCmp1
* AcceptedCmp2
* AcceptedCmp3
* AcceptedCmp4
* AcceptedCmp5
* Response

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

* Dataset Structure
* Missing Value Analysis
* Duplicate Analysis
* Descriptive Statistics

### 2. Data Cleaning

* Missing Value Treatment
* Income Imputation
* Duplicate Verification
* Outlier Detection and Treatment

### 3. Feature Engineering

* Age
* Total Spending
* Total Purchases
* Accepted Campaigns
* Total Children
* Customer Tenure

### 4. Exploratory Data Analysis (EDA)

#### Customer Analysis

* Age Distribution
* Income Distribution
* Education Analysis
* Marital Status Analysis

#### Spending Analysis

* Total Spending Distribution
* Top Spending Customers
* Spending by Education
* Spending by Marital Status
* Spending by Age Group

#### Campaign Analysis

* Campaign Acceptance Analysis
* Customer Response Analysis
* Campaign Performance Comparison

#### Purchase Channel Analysis

* Web Purchases Analysis
* Catalog Purchases Analysis
* Store Purchases Analysis
* Purchase Channel Comparison

### 5. KPI Analysis

* Total Customers
* Average Customer Income
* Average Customer Spending
* Total Customer Spending
* Campaign Acceptance Rate
* Campaign Response Rate
* Average Purchases per Customer
* Preferred Purchase Channel

## Dataset Summary

| Metric                   |     Value |
| ------------------------ | --------: |
| Total Customers          |     2,236 |
| Average Income           | 51,952.61 |
| Average Spending         |    605.99 |
| Total Spending           | 1,354,986 |
| Campaign Acceptance Rate |     5.96% |
| Campaign Response Rate   |    14.94% |

## Key Findings

### Customer Insights

* The customer base is primarily composed of middle-aged and older individuals.
* Graduation is the most common education level among customers.
* Customers have moderate-to-high purchasing power with an average income of approximately 51,953.

### Spending Insights

* Total customer spending exceeded 1.35 million.
* Customer spending is concentrated among a relatively small group of high-value customers.
* Customers with PhD qualifications exhibit the highest average spending.
* Customers aged 70 and above demonstrate the highest spending levels.

### Campaign Insights

* Campaign 4 achieved the highest customer acceptance.
* Campaign 2 was the least successful campaign.
* The most recent campaign achieved a response rate of approximately 14.94%.
* Recent campaigns performed better than historical campaign averages.

### Purchase Channel Insights

* Physical stores remain the most preferred purchasing channel.
* Web purchases represent the second most popular channel.
* Catalog purchases contribute the least to customer purchasing activity.

## Business Recommendations

* Develop loyalty programs for high-value customers.
* Implement personalized marketing campaigns for premium customer segments.
* Optimize future campaigns using insights from successful campaigns.
* Improve customer segmentation and targeting strategies.
* Continue investing in both physical stores and digital sales channels.
* Leverage customer analytics to support marketing decision-making.

## Skills Developed

* Marketing Analytics
* Customer Analytics
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Customer Segmentation
* Campaign Performance Analysis
* KPI Analysis
* Business Insight Generation
* Data-Driven Decision Making

## Project Structure

```text
Project-4-Marketing-Campaign-Analytics/
│
├── data/
├── images/
├── notebooks/
│   └──Analysis.ipynb
├── requirements.txt
└── README.md
```

## Conclusion

This project demonstrates how customer analytics and marketing analytics can be used to evaluate customer behavior, campaign performance, and purchasing preferences. The insights generated can help businesses improve customer engagement, optimize marketing strategies, and support data-driven decision-making.
