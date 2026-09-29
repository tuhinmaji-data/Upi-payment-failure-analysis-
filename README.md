# UPI Payment Failure Analysis

## 📌 Project Overview

This project analyzes UPI transaction data to understand payment performance,
identify common transaction failure patterns, and compare failure rates across
different sender banks and months.

The objective of the project is to convert transaction-level data into
business insights that can help identify potential areas for investigation
and improve payment transaction performance.

---

## 🎯 Business Problem

UPI payment failures can affect customer experience, transaction completion,
and overall payment performance.

The key business questions addressed in this project are:

- What percentage of UPI transactions are failing?
- What are the major reasons for transaction failures?
- Which sender banks have higher failure rates?
- How do transaction failures change month by month?
- Which banks process higher transaction values?
- Which failure categories require further investigation?

---

## 📊 Key Metrics

| Metric | Value |
|---|---:|
| Total Transactions | 500 |
| Successful Transactions | 412 |
| Failed Transactions | 88 |
| Failure Rate | 17.60% |
| Total Transaction Amount | ₹2.36M |

---

## 🔍 Analysis Performed

### 1. Failure Reason Analysis
Analyzed failed transactions based on reasons such as:

- Bank Server Down
- Network Timeout
- Invalid UPI ID
- Insufficient Funds
- Beneficiary Bank Unavailable
- Daily Limit Exceeded
- Incorrect PIN
- Transaction Declined by Bank

### 2. Bank-wise Failure Rate
Compared transaction failure rates across sender banks to identify
differences in payment performance.

### 3. Monthly Failure Trend
Analyzed failed transactions across months to identify changes in
failure volume over time.

### 4. Transaction Amount Analysis
Compared transaction amounts processed by different sender banks to
understand transaction-value distribution.

---

## 📈 Dashboard

The Power BI dashboard contains:

- Total Transactions KPI
- Successful Transactions KPI
- Failed Transactions KPI
- Failure Rate KPI
- Total Transaction Amount KPI
- Failed Transactions by Reason
- Bank-wise Failure Rate
- Monthly Failed Transaction Trend
- Transaction Amount by Sender Bank

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power BI
- Power Query
- Pivot Tables
- Data Cleaning
- Data Analysis
- Data Visualization
- Business Analysis

---

## 💡 Business Insights

The analysis provides visibility into:

- Overall UPI transaction failure performance
- Major categories contributing to failed transactions
- Differences in failure rates across sender banks
- Monthly changes in failed transaction volume
- Transaction-value distribution across banks

These insights can be used as a starting point for further investigation
into payment reliability and transaction performance.

---

## 📁 Project Structure

UPI-Payment-Failure-Analysis/
│
├── Dataset/
│   └── UPI_Transaction_Data.xlsx
│
├── PowerBI/
│   └── UPI_Payment_Failure_Analysis.pbix
│
├── Dashboard/
│   └── UPI_Dashboard.png
│
└── README.md

---

## 👤 Role

Business Analyst / Data Analyst

### Responsibilities

- Defined business questions for transaction failure analysis
- Cleaned and prepared transaction data
- Performed exploratory analysis
- Created KPIs and analytical measures
- Built an interactive Power BI dashboard
- Analyzed failure patterns across banks, months, and failure reasons
- Translated data findings into business-focused insights
