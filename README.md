# CLTV and RFM Analysis Project

## Project Overview

The goal of this project is to enhance customer retention and optimize marketing strategies by performing Customer Lifetime Value (CLTV) and Recency, Frequency, Monetary (RFM) analysis. The dataset contains transactional data from a retail company, providing insights into customer behavior and helping to identify high-value customers. This analysis allows for effective customer segmentation and the development of targeted marketing strategies to increase customer loyalty and profitability.

## Dataset Information

The dataset contains the following columns:

- **InvoiceNo:** Unique identifier for each transaction.
- **StockCode:** Unique code for each product.
- **Description:** Description of the product.
- **Quantity:** Number of products purchased.
- **InvoiceDate:** Date and time of the transaction.
- **UnitPrice:** Price of a single product.
- **CustomerID:** Unique identifier for each customer.
- **Country:** Country where the transaction took place.

## Business Problem

The company faces several challenges in maximizing customer lifetime value and improving customer retention rates. The current marketing strategies are not tailored to different customer segments, resulting in potential revenue loss and inefficient use of marketing budgets. Key issues include:

### 1. Customer Churn
The company is experiencing customer churn, especially among first-time buyers, which leads to a loss of potential long-term revenue. Strategies need to be developed to engage and retain these customers.

### 2. Inefficient Marketing
The lack of targeted marketing strategies results in overspending on promotions for low-value customers while missing opportunities to engage high-value customers. Tailoring promotions and offers based on customer value can optimize marketing spend and improve ROI.

### 3. Segmentation and Retention
Proper customer segmentation is crucial to identify distinct groups within the customer base. By understanding the characteristics of different clusters, the company can implement strategies such as discounts, cashback offers, and loyalty programs to retain customers and increase their lifetime value.

## Cluster Strategies

- **Cluster 0: First-Time Buyers**
  - This cluster consists mostly of first-time buyers. To keep them engaged, the company should offer discounts or cashback to encourage repeat purchases. Although this requires investment, retaining these customers is more beneficial than acquiring new ones.

- **Cluster 1: Mid-Spender Customers**
  - Similar to Cluster 0, discounts and promotions should be offered to encourage repeat purchases. The focus is on increasing the buying frequency in both Cluster 0 and Cluster 1. Since Cluster 1 customers are not first-time buyers, the budget for these promotions can be slightly lower.

- **Cluster 2: Best Customers**
  - Cluster 2 consists of the best customers, who are frequent and high spenders. To build their loyalty, the company should focus on creating and promoting a loyalty program, which can further increase their spending and retention.


