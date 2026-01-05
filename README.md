💳 Payments Risk Transaction Monitoring System
📌 Project Overview

This project simulates a real-world payments risk and transaction monitoring system used by banks and fintechs to detect suspicious or fraudulent behaviour in digital payment systems.

Using the PaySim synthetic mobile money dataset, the project analyses transaction flows, account behaviour, and fraud indicators to demonstrate how modern financial institutions monitor payment risk at scale.

🎯 Objectives

Analyse large-scale payment transaction data

Identify high-risk and anomalous transactions

Understand fraud patterns in digital payments

Demonstrate end-to-end data handling used in fintech risk teams

🧠 Key Features

Transaction-level risk analysis

Fraud vs non-fraud behaviour comparison

Feature exploration (amounts, balances, transaction types)

Notebook-based exploratory data analysis

Scalable structure aligned with real banking workflows

🗂️ Project Structure
Payments-Risk-Transaction-Monitoring-System/
├── data/
│   ├── README.md              # Dataset instructions (PaySim)
│   └── paysim_raw.csv         # Local only (ignored)
├── notebooks/
│   └── analysis.ipynb         # EDA and risk exploration
├── src/
│   └── risk_engine.py         # Core risk logic (WIP)
├── README.md
└── requirements.txt

📊 Dataset

Dataset: PaySim (Synthetic Mobile Money Transactions)

Source: Kaggle
https://www.kaggle.com/datasets/ealaxi/paysim1

Size: ~470MB (excluded from repo due to GitHub limits)

📄 Full download and usage instructions are provided in
👉 data/README.md

🧪 Technologies Used

Python

Pandas / NumPy

Jupyter Notebook

Git & GitHub

(Planned) Scikit-learn for risk scoring models

🏦 Real-World Relevance

This project mirrors how:

Banks monitor transaction risk

Fintechs flag suspicious payments

Compliance teams support AML & fraud detection

Data teams work with large transaction datasets

It aligns with roles such as:

FinTech Analyst

Risk & Fraud Analyst

Data Analyst (Financial Services)

Payments / AML Analyst

🚀 Future Enhancements

Rule-based fraud detection engine

Risk scoring per account

Time-series anomaly detection

Dashboard (Power BI / Python visualization)

Machine learning fraud classifier

👤 Author

Bhavani Priya
MSc Financial Technology
University of Stirling

📌 GitHub: https://github.com/Priya8998

⚠️ Disclaimer

This project uses synthetic data for academic and demonstration purposes only.
No real customer or financial data is involved.
