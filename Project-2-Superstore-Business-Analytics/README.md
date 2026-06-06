# Superstore Business Analytics

## Project Overview

This project analyzes retail sales data from a Superstore dataset to uncover insights related to sales performance, profitability, customer behavior, and regional trends.

Using Python and data analytics techniques, the project transforms raw transactional data into actionable business insights and strategic recommendations.

## Dataset Information

* Total Records: 9,994
* Total Features: 21
* Business Domain: Retail Sales Analytics

The dataset contains information related to:

* Orders
* Customers
* Products
* Sales
* Profit
* Discounts
* Regions
* Shipping Details

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

## Project Workflow

### 1. Dataset Overview

* Examined dataset dimensions and structure
* Reviewed data types and feature composition
* Generated descriptive statistics

### 2. Data Cleaning

* Checked for missing values
* Checked for duplicate records
* Converted date columns to datetime format

### 3. Feature Engineering

Created additional features:

* Year
* Month
* Month Number
* Quarter
* Shipping Days
* Profit Margin (%)

### 4. Exploratory Data Analysis

Performed analysis on:

* Sales by Region
* Profit by Region
* Sales by Category
* Profit by Category
* Monthly Sales Trends
* Monthly Profit Trends
* Top 10 Products
* Top 10 Customers
* Discount vs Profit
* Correlation Analysis

### 5. KPI Analysis

Calculated key business metrics including:

* Total Sales
* Total Profit
* Total Orders
* Total Customers
* Average Order Value
* Average Shipping Days
* Best Performing Region
* Best Performing Category

### 6. Business Insights & Recommendations

Generated actionable recommendations based on analytical findings.

## Key Findings

### Regional Performance

* West region generated the highest sales revenue ($725,457.82).
* West region also produced the highest profit ($108,418.45).

### Category Performance

* Technology generated the highest sales ($836,154.03).
* Technology produced the highest profit ($145,454.95).
* Furniture generated strong sales but comparatively low profit.

### Seasonal Trends

* November recorded the highest sales revenue.
* December generated the highest profit.
* Sales and profit increased significantly during the final months of the year.

### Customer & Product Analysis

* Revenue was concentrated among a relatively small number of high-performing products and customers.
* Canon imageCLASS 2200 Advanced Copier was the highest revenue-generating product.
* Sean Miller was the highest-value customer.

### Profitability Insights

* Higher discount levels were associated with lower profitability.
* Discount and Profit Margin (%) exhibited a strong negative correlation (-0.86).
* Aggressive discounting significantly reduced profit margins.

## Key Performance Indicators (KPIs)

| KPI                   | Value         |
| --------------------- | ------------- |
| Total Sales           | $2,297,200.86 |
| Total Profit          | $286,397.02   |
| Total Orders          | 5,009         |
| Total Customers       | 793           |
| Average Order Value   | $458.61       |
| Average Shipping Days | 3.96          |
| Top Region            | West          |
| Top Category          | Technology    |
| Best Month            | November      |

## Business Recommendations

* Expand successful strategies from the West region.
* Increase investment in Technology products.
* Investigate low profitability within the Furniture category.
* Optimize discount policies to protect profit margins.
* Strengthen customer retention initiatives for high-value customers.
* Prepare inventory and operations for year-end demand spikes.

## Project Structure

```text
Project-2-Superstore-Business-Analytics
│
├── data
│   └── superstore.csv
│
├── images
│
├── notebooks
│   └── analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

## Future Improvements

* Interactive Dashboard Development
* Customer Segmentation
* Sales Forecasting
* Predictive Analytics
* Business Intelligence Dashboard

## Author

**Harsh Poonia**

MCA Student | Aspiring Data Analyst | Data Science Enthusiast
