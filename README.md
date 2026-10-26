# Credit Card Fraud Detection Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Dataset](https://img.shields.io/badge/Dataset-65K%20Transactions-blue)
![Data Model](https://img.shields.io/badge/Data%20Model-Star%20Schema-2FB67C)

## Project Overview

The Credit Card Fraud Detection Dashboard is a Power BI project that analyzes 65,000 credit card transactions to identify fraud patterns, understand transaction risks, and evaluate the performance of a rule-based fraud alert system.

The dashboard helps identify when and where fraud occurs, which transaction categories have higher fraud rates, and how effectively existing rules detect fraudulent transactions.

**Note:** This project uses synthetic data for demonstration and portfolio purposes. All business results are illustrative.

## Business Objectives

- Analyze fraud rates and estimated financial losses.
- Identify high-risk transaction amounts, times, and categories.
- Compare online and in-store fraud rates.
- Analyze fraud patterns across customer segments and merchants.
- Evaluate fraud detection performance using precision and recall.
- Provide data-driven recommendations to improve fraud monitoring.

## Dataset

The project contains 65,000 synthetic credit card transactions organized into six CSV files.

| File | Description |
|---|---|
| Fact_Transactions.csv | Transaction amounts, dates, times, fraud labels, and alert information |
| Dim_Customer.csv | Customer information and demographic attributes |
| Dim_Merchant.csv | Merchant information and categories |
| Dim_Location.csv | Transaction location information |
| Dim_Date.csv | Calendar dates and date attributes |
| Dim_Time.csv | Transaction hours and time buckets |

## Key Findings

| Metric | Result |
|---|---:|
| Total Transactions | 65,000 |
| Fraudulent Transactions | 672 |
| Fraud Rate | 1.03% |
| Total Transaction Value | $5.72M |
| Estimated Fraud Loss | $239,730 |
| Fraud Alerts Raised | 1,194 |
| Fraud Detection Rate (Recall) | 51.5% |
| Alert Precision | 29.0% |
| False Positives Among Alerts | 71.0% |

*All figures are calculated from the synthetic dataset and are illustrative.*

## Dashboard Pages

The Power BI dashboard contains six pages:

1. **Executive Overview:** Summarizes fraud KPIs, transaction volumes, and estimated financial losses.
2. **When and How:** Analyzes fraud by transaction time, weekday, and transaction amount.
3. **Where:** Explores transaction and fraud patterns across states and cities.
4. **Who and Merchants:** Examines customer segments, merchant categories, and merchant risk.
5. **Rule Engine Performance:** Evaluates fraud detection, missed fraud, false positives, and alert precision.
6. **Investigation:** Provides detailed transaction information for further investigation using drill-through.

## Tools and Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Star Schema Data Modeling
- CSV Datasets
- Data Visualization and KPI Analysis

## Business Recommendations

- Introduce additional verification for high-risk online transactions.
- Review merchants with elevated fraud rates regularly.
- Improve alert rules to reduce unnecessary investigations.
- Provide additional protection for customers in higher-risk segments.
- Monitor fraud detection rates, alert precision, and investigation costs to evaluate improvements.

## How to Use This Project

1. Download or clone this repository.
2. Download the Power BI `.pbix` file.
3. Open the file using Power BI Desktop.
4. If necessary, update the CSV data source paths.
5. Refresh the data and explore the dashboard.

## Limitations

- The dataset is synthetic and does not represent real customer transactions.
- Fraud patterns and alert outcomes are simulated.
- Geographic findings are illustrative and should not be interpreted as actual fraud hotspots.
- Results should be validated against real transaction data before operational decisions are made.

## Author

**Devkumar Patel**  
Data Analyst | Data Engineer

[LinkedIn Profile](https://www.linkedin.com/in/devkumar-patel-602920350/)

---

**License:** MIT
