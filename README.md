Fraud Detection – Suspicious Transaction Analysis

Description:
This project demonstrates a simple rule-based approach to identify potentially suspicious banking transactions using a publicly available dataset. The analysis focuses on detecting anomalies in transaction behavior that may indicate fraud, such as unusually high spending, transactions far from the customer’s home location, or abnormal frequency of transactions.

Features of the project:

Data Cleaning: Handles missing values in key columns like Previous_Fraud_Count, Unusual_Time_Transaction, Distance_From_Home, and Failed_Transaction_Count.

Derived Features: Creates additional features like transaction-to-balance ratio and daily-to-weekly transaction ratio to highlight anomalous behavior.

Suspicious Transaction Filtering: Uses rule-based thresholds to flag transactions that may be fraudulent, including:

Transactions far from the customer’s home.

High transaction amounts relative to account balance.

Large credit card transactions exceeding account balance.

Sudden spikes in daily transaction counts.

Output: Saves flagged transactions to a .parquet or .csv file for further analysis.

Goal:
This project is designed for educational purposes and to demonstrate how basic data analysis and rule-based filters can be used to detect potential fraud. It can also serve as a foundation for building more advanced fraud detection models using machine learning techniques.

Technologies:

Python 3

Pandas for data manipulation
