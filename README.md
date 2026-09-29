# Credit Card Financial Analysis

## Project Overview

This project focuses on analysing credit card customer and transaction data using Microsoft Power BI. The objective is to understand revenue performance, customer behaviour, transaction patterns, credit card usage and demographic trends.The analysis converts raw credit card data into meaningful business insights through data preparation, data modelling, DAX measures and interactive Power BI visualisations.

---

## Business Objective

The objective of this analysis is to help the business understand:

- Overall revenue and transaction performance
- Customer and credit card usage patterns
- High-value customer segments
- Transaction behaviour across different customer groups
- Revenue contribution by customer and card segments
- Demographic patterns affecting financial performance
- Spending and transaction trends

The analysis is designed to support data-driven business decisions and performance monitoring.

---

## Dataset

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

---

## Data Preparation

The data was prepared before analysis to improve consistency and usability.

### Data preparation steps performed:

- Reviewed the available fields and data types.
- Checked the data for data-quality issues.
- Handled relevant missing or invalid values where applicable.
- Standardised fields required for analysis.
- Prepared customer and credit card data for modelling.
- Created the required calculated fields and measures for analysis.

---

## Data Model

The Power BI data model consists of two main tables:

### 1. Customer Table

Contains customer demographic and customer-level information.

### 2. Credit Card Table

Contains credit card, transaction and financial information.

The tables are connected using the common field `Client_Num`, allowing customer information to be analysed together with credit card and transaction data.

---

## Tools and Technologies

- Microsoft Power BI – Dashboard development and interactive visualisation
- Power Query – Data preparation and transformation
- DAX – Measures, calculations and KPI analysis

---

## Key KPIs

The analysis includes key financial and customer KPIs such as:

- Total Revenue
- Total Transaction Amount
- Total Transaction Count
- Total Interest Earned
- Total Annual Fees
- Customer Count
- Average Credit Limit
- Average Utilisation Ratio

# GitHub Repository Link:
https://github.com/Mahanand4/Credit_Card_Financial_Analysis_PowerBI/edit/main/README.md

## Submitted By

Mahanand B Shetty
