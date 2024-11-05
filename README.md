# Capstone-project-2

## Customers Data

[Project Overview](#project-overview)

[Column Descriptions](#column-descriptions)

[Data Source](#data-source)

[Tools Used](#tools-used)

 [Data Cleaning and Preparations](#data-cleaning-and-preparations)
 
[Exploratory Data Analysis](#exploratory-data-analysis)
 
 [Data Analysis](#data-analysis)
 
 [Data Visualization](#data-visualization)
 
 [My Result](#my-result)

### Project Overview
---
 
 This project involves analyzing customer data for a subscription service to identify 
segments and trends. My goal is to understand and showcase  customer behavior, track subscription types, 
and identify key trends in cancellations and renewals. My final deliverable is a Power BI 
dashboard that presents my analysis. 


### Column Descriptions
---
- CustomerID: Unique identifier for each customer.
- CustomerName: Name of the customer (anonymized if necessary).
- Region: Geographical area where the customer is located (e.g., North, South, East, West).
- SubscriptionType: Type of subscription plan the customer is enrolled in (e.g., Basic, Premium).
- SubscriptionStart: Start date of the customer's subscription.
- SubscriptionEnd: End date of the customer's subscription.
- Canceled: Indicates if the subscription was canceled (TRUE or FALSE).
- Revenue: Revenue generated from the customer's subscription.
- Subscription Duration: Duration (in days) of the subscription period


### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsft.com)
1. For data cleaning
2. summarizations
3. Visualization.

- SQL: used queries for data cleaning.

- Power BI:  both data cleaning, Summarization and visualization.

### Data cleaning and preparation 
---
 we perform the following action;

1. Data loading and Inspection
2. Handling missing variables
3. Data Cleaning and Formatting

### Exploratory Data Analysis:
---
This involved the exploratory of the Data to answer some questions about the data such as;
- Segmentation: Group customers by demographics,subscription type, and usage patterns,Identify high-value customer segments and factors influencing retention.
- Trend Analysis: Track trends in subscriptions, cancellations, and renewals over time
- Retrieve the total number of customers from each region.
- Find the most popular subscription type by the number of customers.
- Find customers who canceled their subscription within 6 months.
- Calculate the average subscription duration for all customers.
- Find customers with subscriptions longer than 12 months.
- Calculate total revenue by subscription type.
- Find the top 3 regions by subscription cancellations.
- Find the total number of active and canceled subscriptions.


### Data Analysis
---
This is where we include some basic lines of code or queries or even some of the DAX expressions used during the analysis

```SQL
SELECT * FROM CAPSTONE DATA 

````SELECT Product, SUM(Quantity * UnitPrice) AS TotalSale
FROM [LITA Capstone Dataset]
GROUP BY Products 
```


### Data Vitualization
---






### My Result
---

