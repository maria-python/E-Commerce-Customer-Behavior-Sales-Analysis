# E-Commerce Sales Analysis

Author: Maria Ilnitska


## Project Overview

This project analyzes customer behavior and sales performance for an e-commerce platform operating in Turkey. Using transaction data from 5,000 orders, the analysis explores patterns in purchasing behavior, product category performance, customer segmentation, and operational factors such as delivery performance.

The goal of the project is to **transform raw transactional data into actionable business insights** that support strategic decision-making.


## Business Problem

An e-commerce company wants to better understand its customers and sales performance in order to:

- increase overall revenue

- improve operational efficiency in delivery
  
- improve customer retention

- optimize marketing strategies

Management requires data-driven insights to guide future business decisions.


## Project Objectives

- The main objectives of this analysis are:

- Identify sales trends and seasonal patterns

- Evaluate product category performance

- Analyze customer purchasing behavior

- Segment customers using RFM analysis and K-Means clustering

- Examine device usage patterns

- Explore the relationship between delivery performance and customer satisfaction

- Provide business recommendations based on data insights


## Dataset Overview

The dataset contains 5,000 e-commerce transactions from January 2023 to March 2024 and includes information about:

- customer demographics

- product categories

- transaction details

- website behavior

- delivery performance

- customer ratings

**Key variables include:**

- Product category

- Order amount

- Payment method

- Device type

- Delivery time

- Customer rating

- Returning vs new customer

**Key observations:**

- The dataset contains 5,000 transactions

- There are 18 columns

- Data types were consistent and suitable for analysis

- No missing values were found


## Project Structure

```
ecom-analysis
│
├── Data
│   └── ecommerce_customer_behavior_dataset.csv
│
├── Notebooks
│   └── analysis.ipynb
│
├── Visualization
│   └── delivery_and_ratings.png
│   └── monthly_revenue_trend.png
|   └── returning_vs_new_costumers.png
|   └── revenue_by_product_category.png
|   └── spending_by_device_rype.png
│
├── requirments.txt
|
├── README.md
|
└── DATASET_README.md

```

## Tools & Technologies

The analysis was conducted using the following tools:

- Python 3.11.14

- Pandas – data manipulation and analysis

- NumPy – numerical operations

- Matplotlib – data visualization

- Seaborn – statistical data visualization

- VS Code & Jupyter Notebook


## Data Preparation

Several preprocessing steps were performed to prepare the dataset for analysis. The Date column was converted to datetime format, allowing time-based analysis. **Additional features** were created:

Year – transaction year

Month – transaction month

Year_Month – monthly period used for trend analysis

Revenue_Check column was created to validate the consistency of the Total_Amount column.

Revenue_Check = Unit_Price × Quantity − Discount_Amount

**This step helped verify the accuracy of the revenue values in the dataset.**


## Sales Trend Analysis

Monthly revenue was analyzed to identify trends in sales performance over time.

The visualization shows how revenue fluctuates across different months, helping identify potential changes in customer purchasing activity.

Trend analysis provides useful insights for:

- forecasting demand

- planning marketing campaigns

- managing inventory


## Product Category Performance

Revenue performance was compared across product categories.

The analysis shows that Electronics generates the highest total revenue among all categories, indicating strong demand in this segment.

Understanding category performance helps businesses prioritize:

- inventory management

- promotional strategies

- product assortment planning


## Customer Analysis

Customer behavior was analyzed by comparing returning customers and new customers.

**Results show:**

Returning customers: 59.8%

New customers: 40.2%

Returning customers represent the majority of transactions and tend to generate higher average order values, highlighting the importance of customer retention strategies.


## Customer Segmentation (RFM + K-Means)

Customers were segmented using the RFM model, which measures:

**Recency** – how recently a customer made a purchase

**Frequency** – number of purchases

**Monetary** – total spending

The features were normalized using StandardScaler, and K-Means clustering was applied to identify customer segments.

The clustering results reveal groups of customers with significantly higher total spending. These segments represent high-value customers that could benefit from targeted loyalty programs and personalized marketing campaigns.


## Device Behavior Analysis

Customer purchasing behavior was analyzed across different device types.

**Results show:**

Mobile devices generate the highest average transaction value

Desktop and tablet purchases show slightly lower average order values

Session duration is relatively similar across all device types

This indicates that mobile users play an important role in overall sales performance, highlighting the importance of a strong mobile shopping experience.


## Delivery Time & Customer Satisfaction

A scatterplot was used to examine the relationship between delivery time and customer ratings.

The results show a mixed distribution of ratings across delivery times. While some lower ratings appear at longer delivery times, high ratings are also present in the same range.

This suggests that delivery time alone may not fully explain customer satisfaction, and other factors may also influence customer feedback.


## Key Insights

Several important insights were discovered during the analysis:

**1. Electronics dominate revenue**

The Electronics category generates the highest total revenue among all product categories. This suggests strong customer demand for electronic products and indicates that this category plays a major role in overall sales performance.

**2. Returning customers drive a large portion of transactions**

Approximately **59.8% of purchases come from returning customers**, compared to **40.2% from new customers**. This indicates that customer retention is an important driver of revenue.

**3. Mobile devices play a key role in purchasing**

Mobile users show the **highest average transaction value** compared to desktop and tablet users. This highlights the importance of optimizing the mobile shopping experience.

**4. High-value customer segments exist**

Customer segmentation using **RFM analysis and K-Means clustering** identified groups of customers with significantly higher total spending. These segments represent potential high-value customers that could benefit from targeted loyalty programs.


## Conclusion

This project demonstrates how transaction data can be used to analyze customer behavior, evaluate product performance, and generate actionable business insights.

The analysis highlights opportunities to improve customer retention, mobile commerce performance, and high-value customer engagement, providing valuable guidance for business decision-making.


## Contacts

Gmail: maria.ilnitska11@gmail.com

LinkedIn: [www.linkedin.com/in/maria-ilnitska](http://www.linkedin.com/in/maria-ilnitska)

Telegram: @mariailnitska
