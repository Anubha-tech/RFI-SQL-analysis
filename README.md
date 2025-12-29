# RFI-SQL-analysis
# RFI Analysis – FinCrime Operations (SQL)

## Overview
This project analyses Requests for Information (RFIs) received from partner banks
to identify operational and compliance trends.

The analysis focuses on:
- RFI volumes by partner bank
- Category-level trends (KYC, AML, Fraud, Sanctions)
- Response time and SLA adherence
- High-risk RFI prioritisation

## Tools Used
- MySQL
- SQL
- Basic data quality checks and aggregations

## Dataset
The dataset contains RFIs with the following fields:
- RFI ID
- Partner Bank
- Date Received
- Category
- Priority
- Response Time (Days)
- Risk Level

(Data is simulated for portfolio purposes.)

## Key Insights
- A small number of banks generate the majority of RFIs
- KYC-related RFIs represent the largest workload
- High-risk RFIs are generally handled within SLA
- Low-priority RFIs show higher delay rates

## Files in this Repository
- `rfi_analysis.sql` – SQL queries used for analysis
- `rfi_analysis_report.pdf` – Summary of insights and recommendations
- `rfi_data_sample.csv` – Sample dataset (simulated)

## Author
Anubha Singh
