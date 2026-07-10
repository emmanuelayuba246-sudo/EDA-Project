# Exploratory Data Analysis (EDA) Report

## Introduction

The Exploratory Data Analysis (EDA) was to explore an e-commerce sales dataset, understand its structure, identify trends, detect outliers, and gain insights into customer purchasing behavior. The analysis focused on examining the dataset, checking its quality, and visualizing important patterns in the data.

## Data Overview

The dataset contains 1,200 records and 14 columns, including customer information, product details, payment methods, order status, and sales information. The data types were appropriate for analysis, and the Date column was stored as a datetime variable while TotalPrice was stored as a numeric variable.

## Data Quality

The dataset was checked for missing values and duplicate records. Missing values were found and cleaned, indicating that the dataset is complete and ready for analysis.

## Outlier Analysis

Outlier analysis was performed on the TotalPrice column using a histogram, boxplot, and the Interquartile Range (IQR) method. The analysis revealed several high-value outliers with TotalPrice values above the upper limit (approximately 3,300–3,450). These outliers represent unusually expensive orders compared to the majority of transactions and may indicate bulk purchases or premium product sales.

## Trend Analysis

- The daily sales trend showed that sales fluctuate over time with several peaks and low periods. There was no consistent upward or downward trend throughout the observed period.
- The product sales analysis revealed that Chair was the best-selling product, while Phone had the lowest quantity sold among all products.
- The payment method analysis showed that Online payments were the most frequently used payment method, while Gift Card payments were the least common.
- The order status analysis indicated that Cancelled orders occurred most frequently, while Delivered orders had the lowest count. Overall, the distribution of order statuses was relatively balanced.

## Conclusion

The exploratory data analysis provided valuable insights into the e-commerce dataset. The data was clean and required minimal preprocessing. Several high-value outliers were identified in the TotalPrice column. Sales varied over time without a clear long-term trend. Chairs were the most popular product, online payments were the preferred payment method, and cancelled orders occurred most frequently. These findings provide a better understanding of customer purchasing behavior and overall sales performance, forming a solid foundation for further analysis or predictive modeling.

## Recommendations

Based on the findings from the exploratory data analysis, the following recommendations are suggested:
- **Investigate High-Value Orders:** The outliers identified in the TotalPrice column should be reviewed to determine whether they represent legitimate bulk purchases or potential data entry errors.
- **Improve Order Fulfillment:** Since Cancelled orders were the most frequent order status, the company should investigate the reasons for cancellations and implement strategies to reduce them, such as improving inventory management, delivery times, or customer communication.
- **Promote Low-Selling Products:** Products such as Phones, which had the lowest sales quantity, could benefit from promotions, discounts, or targeted marketing campaigns to increase customer demand.
- **Enhance Online Payment Services:** As Online payments were the most commonly used payment method, maintaining a secure, fast, and reliable online payment system will help improve customer satisfaction.
- **Monitor Sales Trends:** Since daily sales fluctuated throughout the observed period, the business should continue monitoring sales patterns to identify seasonal trends and better plan inventory and marketing activities.
