# 🕵️ Credit Card Fraud Risk Analysis

A Story-Driven Data Analytics Project

Data set - - -> https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset

# 📌 Project Background

Credit card fraud is often misunderstood.

While fraud transactions are rare, their financial impact is disproportionately high.
This project analyzes 1.29 million real-world credit card transactions to understand how fraud behaves, when it happens, and where businesses lose money — before applying any machine learning.

The goal is to answer one core question:

How can simple data-driven insights help reduce fraud-related losses?

# 📊 Dataset Overview

Total transactions analyzed: 1,296,675

Fraud transactions: 7,506

Fraud rate: ~0.57%

At first glance, fraud seems negligible — but the story changes when we look deeper.

# 💸 The Cost of Fraud

Although fraud accounts for less than 1% of transactions:

Total revenue (without fraud): ₹91.22M

Revenue after fraud: ₹87.23M

Revenue lost due to fraud: ~4.3%

# 📉 Conclusion:
Fraud is rare, but financially dangerous.

# 💳 Fraud vs Normal Transactions

A clear behavioral difference emerges:

Transaction Type	Average Amount
Normal	₹67
Fraud	₹531

Fraud transactions are ~8× larger than normal ones — making transaction amount a critical risk indicator.

# 📆 Day of Week

Saturday is the most fraud-active day

# 🕘 Time of Day

Fraud spikes after 8 PM

# 🧠 Insight:
Late-night, weekend transactions carry higher fraud risk.

# 🌍 Geographic & Merchant Concentration

Fraud tends to cluster, not spread evenly.

Highest fraud count by state: New York

Highest fraud count by city: Houston

Highest fraud count by merchant: Rau and Sons

Additionally:

Top 10 risky merchants contribute ~1.38% of total fraud

## 📌 This suggests merchant-level monitoring can be highly effective.

# 🚨 Transaction Velocity Analysis

Average normal transactions per hour: ~53,715

Average fraud transactions per hour: ~312

Sudden spikes in transaction frequency can indicate abnormal behavior.

# 🛑 Simple Rule-Based Fraud Detection

Even without machine learning, a basic rule can help:

Flag transactions where amount > X

Using this single rule:

~26% of fraud transactions can be caught

This highlights how simple thresholds can significantly reduce losses.

# 🧩 Business Takeaways

This analysis can help businesses:

Set amount-based fraud alerts

Increase monitoring during late hours & weekends

Maintain high-risk merchant watchlists

Estimate financial exposure due to fraud

Build a strong foundation before applying ML models

# 🚧 Scope & Limitations

This project focuses on exploratory risk analysis

No machine learning models were used

Emphasis is on interpretability & decision support

Intended as a pre-model fraud analysis step

# 🛠 Tools Used

Python

Pandas, NumPy

Matplotlib, 

Jupyter Notebook
