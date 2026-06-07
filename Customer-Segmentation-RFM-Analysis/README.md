# Project 3: Customer Segmentation & RFM Analysis

## Project Overview

Customer segmentation is a business analytics technique used to group customers based on their purchasing behavior and value to the business. This project uses RFM (Recency, Frequency, Monetary) Analysis to identify valuable customer segments and generate actionable business insights.

## Objectives

* Analyze customer purchasing behavior.
* Measure customer value using RFM metrics.
* Segment customers into meaningful groups.
* Generate business insights and recommendations.
* Support customer retention and marketing strategies.

## Dataset

The project uses the Online Retail dataset containing transaction-level retail purchase records.

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

## Progress Completed

### Data Understanding

* Dataset dimensions
* Dataset structure
* Missing value analysis
* Duplicate record analysis
* Descriptive statistics

### Data Cleaning

* Removed missing CustomerID records
* Removed duplicate transactions
* Removed cancelled orders and returns
* Removed invalid pricing records
* Created TotalPrice column

### Final Dataset

* Original Records: 541,909
* Final Records: 392,692
* Features: 9

## Next Steps

* Revenue Analysis
* Country-wise Sales Analysis
* Product Performance Analysis
* Customer Purchase Behavior Analysis
* RFM Analysis
* Customer Segmentation
* Business Recommendations
