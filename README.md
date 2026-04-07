# Card-Transactions-Analysis

## 💳 Card Transactions Analysis Dashboard
An interactive data visualization tool built to generate insights from card transaction data recorded in the U.S.A. with pages focusing on customer demographics, merchant performance, card usage and transaction patterns.

The card transactions analysis dashboard provides stakeholders with an interactive analytical solution that enables them to:
1. Track overall card transaction trends
2. Analyze category-wise merchant performance and transaction errors
3. Understand customer spending patterns and demographics
4. Identify potential credit risk customers
5. Provide data-driven insights for strategic decision making

This tool is intended for use by the risk management, marketing and payment processing teams as well as merchant relationship managers in card issuing companies by providing insights into customer behavior, card usage trends, merchant performance and overall transaction activity.

## Tech Stack
The dashboard was built using the following tools:
1. Power BI Desktop: Data Visualization tool used for report development
2. Python: Optimized large-scale transaction data through aggregation enabling efficient processing
3. MySQL: Used as source for PowerBI import improving data load performance 
4. Power Query: Used for data transformation and cleaning
5. DAX: Utilized to create calculated measures and conditional columns

## Data Source
Data on ~10 M card transactions recorded in the U.S.A from 2010 to 2019 from Kaggle with details on transactions, cards, users, merchants and merchant category codes.
[Dataset Link](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets)

## Highlights
* Financial Transactions lead to the generation of large amounts of transaction, user, merchant and card data. However, raw transactional datasets are often complex and difficult to interpret without proper analysis and visualization.
* This project aims to create an analytical solution which converts raw data into meaningful insights and helps to analyze card transactions.
* Transaction data was optimized and merchant category data was converted to csv format in Python
* All the data files were stored in a MySQL database and then integrated with Power BI for analysis.

## Conclusion
Key outcomes of this project are:
  1. Improved visibility into transaction growth and revenue performance.
  2. Identification of merchant categories which earned the highest revenues.
  3. Analysis of customer credit profiles.
  4. Detection of potential high-risk customers.

The dashboard helps card brand companies understand revenue and customer segments, supports risk teams in monitoring credit profiles, enables marketing teams to target high-value customers and helps operations identify transaction failures and inefficiencies.

## Screenshots

![Dashboard Page 1](https://github.com/SimonelleF/Card-Transactions-Analysis/blob/main/Page1_Transactions_Overview.png)
![Dashboard Page 2](https://github.com/SimonelleF/Card-Transactions-Analysis/blob/main/Page2_Merchant_Performance.png)
![Dashboard Page 3](https://github.com/SimonelleF/Card-Transactions-Analysis/blob/main/Page3_Customer_Demographics.png)
![Dashboard Page 4](https://github.com/SimonelleF/Card-Transactions-Analysis/blob/main/Page4_Card_Insights.png)

