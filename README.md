# Telco Customer Churn Analysis & Dashboard | Power BI

## Project Overview

This project analyzes customer churn behavior for a fictional telecommunications company using Microsoft Power BI.

The goal of this project is to identify the main factors influencing customer churn, analyze customer segments, understand service usage patterns, and provide business insights that can help reduce customer loss and improve customer retention strategies.

## Business Problem

Customer churn is one of the biggest challenges for telecommunication companies. Understanding why customers leave and identifying high-risk customer segments can help businesses take proactive actions to improve retention.

This dashboard provides insights into customer behavior, churn patterns, service usage, contract types, demographics, and revenue impact.

## About Dataset

**Telco Customer Churn Dataset** is a sample dataset provided by IBM. It tracks customer churn based on various factors such as demographics, location, subscribed services, contract information, monthly charges, and customer status.

The dataset contains information about whether customers have left the company within the last month and the possible reasons behind their churn.

**Dataset Source:** IBM

### Dataset Tables:

The Telco Customer Churn dataset consists of 5 main tables:

- Demographics
- Location
- Population
- Services
- Status

### Dataset Files:

- `Telco_customer_churn_demographics.xlsx`
- `Telco_customer_churn_location.xlsx`
- `Telco_customer_churn_population.xlsx`
- `Telco_customer_churn_services.xlsx`
- `Telco_customer_churn_status.xlsx`

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Excel

## Data Modeling

A Star Schema data model was created to improve performance and provide efficient analysis.

The model contains:

### Fact Table:

- `Telco_Churn_Fact`

### Dimension Tables:

- `Services_Dim`
- `Demographics_Dim`
- `Location_Dim`
- `Population_Dim`
- `Status_Dim`

## Business Questions

This dashboard answers important business questions such as:

- What is the overall customer churn rate?
- Which customer segments have the highest churn?
- What demographic factors influence churn?
- Which services are associated with higher churn rates?
- Does contract type affect customer retention?
- What are the main reasons customers leave?
- How does churn impact company revenue?

## Dashboard Pages

The dashboard consists of multiple interactive pages, each focusing on a specific analysis area.

### Home Page

Provides:

- Project overview
- Main KPIs
- Dashboard navigation
- General summary of customer data

### General Insights Page

Analyzes:

- Overall customer behavior
- Customer distribution
- Churn rate
- Main churn reasons
- General business insights

### Customer Demographics Page

Analyzes customer characteristics including:

- Gender
- Age groups
- Dependents
- Customer segments

### Service and Contract Page

Analyzes:

- Subscribed services
- Internet service types
- Contract types
- Payment methods
- Service impact on churn

### Churn and Revenue Page

Analyzes:

- Revenue impact of churn
- Churned customers
- Customer status
- Reasons behind customer loss

## Key Insights

Some important findings from the analysis:

- Customers with month-to-month contracts have higher churn rates compared to long-term contracts.
- Customers with shorter tenure are more likely to leave the company.
- Certain service types show higher churn probability.
- Churned customers have a significant impact on overall revenue.
- Understanding customer behavior can help improve retention strategies.

## Project Structure
Telco-Customer-Churn-PowerBI
│
├── README.md
├── Telco Customer Churn Dashboard.pbix
│
├── Dataset
│ ├── demographics.xlsx
│ ├── location.xlsx
│ ├── population.xlsx
│ ├── services.xlsx
│ └── status.xlsx

## About Author

**Abdallah Nasser**

Data Analyst | Power BI Developer

Email: abdallahnassre@gmail.com
 
phone : 01123117882
