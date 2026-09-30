# Credit Card Financial Analysis

## 1. Project Overview

This project focuses on analysing credit card customer and transaction data using Microsoft Power BI. The objective is to understand financial performance, customer behaviour, transaction patterns, credit card usage and demographic trends.The project converts raw customer and credit card data into meaningful business insights through data preparation, data modelling, DAX measures and interactive Power BI visualisations.

## 2. Business Problem

Financial institutions need a clear view of customer spending behaviour, transaction performance and credit card usage to monitor financial performance and understand customer segments.

Raw customer and transaction data can make it difficult to identify:

- Which customer segments contribute to financial performance
- How transaction activity varies across customer groups
- How different credit card categories perform
- How customers use their available credit
- How demographic factors relate to different usage patterns
- How revenue, fees and interest contribute to overall performance
- Where management should focus for better monitoring and decision-making

This project addresses these challenges by creating an interactive Power BI dashboard that brings key financial and customer metrics into one analytical view.

## 3. Business Questions

The analysis is designed to answer the following business questions:

1. What is the overall revenue and transaction performance?
2. What is the total transaction amount and transaction count?
3. How much interest is earned from credit card customers?
4. What is the contribution of annual fees?
5. Which customer segments show higher transaction activity?
6. How does spending behaviour vary across customer demographics?
7. How do different card categories perform?
8. What is the average credit limit?
9. How is the available credit being utilised?
10. What customer groups contribute significantly to financial performance?
11. How do activation and delinquency-related indicators vary across customers?
12. What trends can be identified from customer and transaction data?

## 4. Project Objectives

The main objectives are to:

- Analyse financial and transaction performance.
- Understand customer behaviour and spending patterns.
- Analyse credit card usage across customer segments.
- Monitor important financial KPIs.
- Compare customer and card-category performance.
- Identify meaningful patterns and trends.
- Present insights through an interactive dashboard.
- Support data-driven business decisions and performance monitoring.

## 5. Dataset

The project uses customer and credit card transaction data.

### Customer Table

The Customer table contains customer-level information such as:

- Customer ID
- Customer Age
- Age Group
- Gender
- Education Level
- Occupation
- Marital Status
- Income Group
- Car Ownership
- Dependent Count
- Customer Satisfaction Score

### Credit Card Table

The Credit Card table contains credit-card and transaction-related information such as:

- Client Number
- Card Category
- Credit Limit
- Annual Fees
- Total Transaction Amount
- Total Transaction Count
- Interest Earned
- Activation Status
- Average Utilisation Ratio
- Customer Acquisition Cost
- Delinquency Information

The two tables are connected using the common field `Client_Num`.

## 6. Data Preparation

The data was prepared before analysis to improve consistency, usability and modelling readiness.

### Data Preparation Steps

- Reviewed available fields and data types.
- Checked the data for data-quality issues.
- Handled relevant missing or invalid values where applicable.
- Standardised fields required for analysis.
- Prepared customer and credit card data for modelling.
- Reviewed relationships between the tables.
- Created required calculated fields and measures.
- Ensured fields were suitable for Power BI visualisation and KPI analysis.


## 7. Data Model

The Power BI data model consists of two main tables:

### 1. Customer Table

Contains customer demographic and customer-level information.

### 2. Credit Card Table

Contains credit card, transaction and financial information.

The tables are connected using the common field `Client_Num`, allowing customer information to be analysed together with credit card and transaction data.

## 8. Methodology

The project followed a structured data analytics workflow:

### Step 1: Understand the Business Requirement

Identified the business questions related to financial performance, customer behaviour and credit card usage.

### Step 2: Understand the Dataset

Reviewed the customer and credit card tables, available fields and data types.

### Step 3: Data Preparation

Checked data quality, standardised relevant fields and prepared the data for analysis.

### Step 4: Data Modelling

Connected the Customer and Credit Card tables using `Client_Num`.

### Step 5: KPI Development

Created relevant financial and customer measures using DAX.

### Step 6: Exploratory Analysis

Analysed revenue, transactions, customer segments, card categories, credit utilisation and other financial indicators.

### Step 7: Dashboard Development

Created interactive Power BI visuals, KPI cards, charts, filters and analytical views.

### Step 8: Insight Generation

Reviewed the dashboard to identify patterns, trends and areas that can support business decision-making.


## 9. Tools and Technologies

- **Microsoft Power BI** – Dashboard development and interactive visualisation
- **Power Query** – Data preparation and transformation
- **DAX** – Measures, calculations and KPI analysis
- **Data Modelling** – Connecting customer and credit card information
- **Interactive Visualisation** – Business-focused reporting and analysis

## 10. Technical Highlights

The project demonstrates the following technical skills:
- Data preparation in Power Query
- Data modelling in Power BI
- Table relationships
- DAX measures and calculations
- KPI development
- Interactive dashboard design
- Customer segmentation
- Financial analysis
- Transaction analysis
- Use of filters and interactive visuals
- Business-focused data visualisation

---

## 11. Key KPIs

The dashboard includes important financial and customer KPIs such as:
- Total Revenue
- Total Transaction Amount
- Total Transaction Count
- Total Interest Earned
- Total Annual Fees
- Customer Count
- Average Credit Limit
- Average Utilisation Ratio

These KPIs provide a high-level view of financial performance and customer activity.


## 12. Analysis Performed

The analysis covers:

### Financial Performance

- Revenue performance
- Transaction amount
- Transaction count
- Interest earned
- Annual fee contribution

### Customer Analysis

- Customer demographics
- Age groups
- Gender
- Education
- Occupation
- Income groups
- Customer segments

### Credit Card Analysis

- Card category performance
- Credit limits
- Credit utilisation
- Activation status
- Delinquency-related information

### Behavioural Analysis

- Spending patterns
- Transaction activity
- Customer-level financial behaviour
- Differences between customer groups

---

## 13. Dashboard / Output

The final output is an interactive Power BI dashboard designed for business users.

The dashboard presents:
- KPI cards for important financial metrics
- Revenue and transaction analysis
- Customer segment analysis
- Credit card category analysis
- Customer demographic analysis
- Credit limit and utilisation analysis
- Interest and fee-related metrics
- Interactive filters
- Business-focused charts and visualisations
The interactive design allows users to explore financial and customer performance across different segments.


## 14. Key Findings

The dashboard enables identification of the following types of findings:

- Revenue and transaction performance can be monitored through consolidated KPIs.
- Customer behaviour can be compared across demographic and customer segments.
- Credit card categories can be evaluated based on financial and transaction metrics.
- Credit limits and utilisation provide visibility into customer credit usage.
- Interest earned and annual fees provide additional views of financial contribution.
- Transaction activity can be analysed to understand differences between customer groups.
- Interactive filtering makes it easier to investigate specific customer or card segments.


## 15. Business Recommendations

Based on the analytical framework and dashboard capabilities, the business can:

- Monitor key financial KPIs regularly.
- Identify and study high-value customer segments.
- Review customer spending and transaction behaviour.
- Compare performance across credit card categories.
- Monitor credit utilisation patterns.
- Use demographic analysis to understand customer segments.
- Review interest and fee contribution as part of financial performance monitoring.
- Investigate segments showing unusual transaction or utilisation patterns.
- Use the dashboard as a recurring management reporting tool.


## 16. Business Impact

The project provides a centralised and interactive view of customer and financial information.

Potential business impact includes:

- Faster access to key financial KPIs.
- Improved visibility into customer behaviour.
- Easier comparison of customer and card segments.
- Better monitoring of transaction performance.
- Improved understanding of credit utilisation.
- More efficient management reporting.
- Support for data-driven business discussions and decisions.



## 17. Project Outcome

The project demonstrates the ability to transform customer and credit card data into an interactive Power BI solution.

It showcases practical skills in:

- Data preparation
- Data modelling
- DAX calculations
- KPI development
- Financial analysis
- Customer analysis
- Dashboard development
- Interactive visualisation
- Business insight generation


## 18. Limitations

The analysis has some limitations:

- The quality of the insights depends on the quality and completeness of the available dataset.
- The dashboard is based on the fields available in the provided customer and credit card tables.
- The analysis is descriptive and focuses on understanding the available data.
- The dashboard does not by itself establish causal relationships between customer characteristics and financial outcomes.
- Specific business actions should be validated using additional business context and current operational data.
- Numerical findings should be reported only when supported by the actual dashboard or dataset.


## 19. Conclusion

- The Credit Card Financial Analysis project demonstrates how Power BI, Power Query and DAX can be used to prepare, model and analyse financial and customer data.

- The dashboard provides an interactive view of key financial KPIs, transaction behaviour, customer segments and credit card performance. It converts raw data into business-focused visual insights and supports financial performance monitoring and data-driven decision-making.

- This project demonstrates practical Data Analyst skills in data preparation, data modelling, DAX, KPI creation, dashboard development, financial analysis and business communication.


## 20. GitHub Repository  link:

https://github.com/Mahanand4/Credit_Card_Financial_Analysis_PowerBI



