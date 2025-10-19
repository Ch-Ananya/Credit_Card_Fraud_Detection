# Credit Card Fraud Detection Dashboard
📊 Project Overview

This project demonstrates end-to-end financial fraud detection, combining data analytics, machine learning, and business intelligence.
Starting from raw transaction data, the project identifies fraudulent activity using Python’s ML models and visualizes key insights in an interactive Power BI dashboard.


🧠 Objective : 

To analyze and detect potentially fraudulent credit card transactions by:
- Building a predictive model using Isolation Forest in Python
- Exploring transaction patterns through EDA (Exploratory Data Analysis)
- Designing a Power BI dashboard that highlights key KPIs and trends


🧰 Tools & Technologies : 

- Python (Jupyter Notebook) :	Data cleaning, EDA, and ML model (Isolation Forest)
- Pandas, NumPy, Matplotlib, Seaborn :	Data analysis and visualization
- Scikit-learn :	ML model training and evaluation
- Power BI	Dashboard : Design and KPI visualization
- GitHub / Google Drive :	Version control and project sharing

  
📂 Project Files : 

- creditcard.csv	Original Kaggle dataset (raw data)
- fraud_results.csv	Cleaned and labeled fraud data created in Python
- Credit_Card_Fraud_Dashboard.pbix	Interactive Power BI dashboard
- fraud_detection.ipynb	Python notebook with full EDA + Isolation Forest implementation

# 🔗 All project files available here:  [Google Drive Folder](https://drive.google.com/drive/folders/1EeXWoUPtKaw3LbwpvFPRccEYOTUoQHPQ?usp=drive_link)

# Dashboard Preview
<img width="1274" height="714" alt="Screenshot 2025-10-19 182158" src="https://github.com/user-attachments/assets/d6dbaf5b-d87e-4011-8905-7a625df100b3" />

# Key Insights
📈 Transaction Overview
- Total Transactions: 285K
- Fraud Transactions: 485
- Fraud Rate: 0.17%
- Total Transaction Amount: ₹25.16M
- Total Fraud Amount: ₹0.92M
- % Loss Due to Fraud: 3.65%

💸 Fraud Distribution
- High-value transactions (> ₹500) show 2.6% higher fraud likelihood.
- Fraudulent activities are more frequent during specific time windows (peak hours).

⏰ Time-Based Analysis
- Peak fraud hours: Detected between 12 AM – 6 AM, suggesting non-business-hour activity.
- Normal transactions remain consistent throughout the day, while fraud spikes irregularly.

💡 Model Insights
- Algorithm Used: Isolation Forest (Unsupervised Anomaly Detection)
- Fraud points detected based on outliers in amount and transaction time.
- Model outputs exported as fraud_results.csv for visualization in Power BI.

🌍 Insights Summary
- Low-frequency but high-impact fraud patterns detected.
- Fraud is not evenly distributed — concentrated in certain transaction ranges and hours.
- Preventive action: Strengthen monitoring for high-value transactions during off-hours.


Happy Analyzing !! 🚀🚀
