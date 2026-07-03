# 💳 SpendDNA – Financial Transaction Analysis

## 📌 Project Overview

SpendDNA is a data analytics project developed using **Python, Pandas, and NumPy** to analyze six months of financial transaction data. The project cleans raw banking transaction records, extracts vendor information, categorizes expenses, detects unusual spending patterns, and generates a comprehensive financial report.

This project simulates how fintech companies analyze customer transactions to provide meaningful spending insights.

---

## 👨‍💻 Author

**Name:** Mohammad Dhilawala

**Course:** Data Analytics & Data Science

**Project:** SpendDNA – Week 2 Minor Project

---

## 🎯 Project Objectives

- Clean and preprocess raw transaction data.
- Handle multiple date and amount formats.
- Extract merchant/vendor names from transaction descriptions.
- Categorize transactions into spending categories.
- Analyze spending behavior and financial trends.
- Detect unusual transactions using Z-score analysis.
- Identify spending archetypes based on transaction patterns.
- Generate a professional financial summary report.

---

## 🛠️ Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy

---

## 📂 Dataset Information

- **Dataset:** Data set for DADS June.csv
- **Time Period:** January 2024 – June 2024
- **Original Records:** 1328 Transactions
- **Records After Cleaning:** 1310 Transactions

---

## ✨ Features Implemented

### ✅ Feature 1 – Transaction Parser
- Loaded CSV dataset
- Removed duplicate transactions
- Parsed mixed date formats
- Cleaned currency values
- Standardized transaction types
- Handled missing values

### ✅ Feature 2 – Vendor Extractor
- Extracted merchant names from transaction descriptions
- Standardized vendor names
- Reduced uncategorized transactions

### ✅ Feature 3 – Category Tagger
Transactions were classified into categories such as:
- Food Delivery
- Quick Commerce
- E-Commerce
- Transport
- Cafe
- Restaurants
- Utilities
- Groceries
- Investments
- Entertainment
- Fuel
- Personal Transfer
- Cash Withdrawal

### ✅ Feature 4 – Spending Overview
Calculated:
- Total Credits
- Total Debits
- Net Savings
- Savings Rate
- Top Categories
- Top Vendors

### ✅ Feature 5 – Monthly Trend Analysis
- Month-wise spending analysis
- Category-wise monthly expenditure
- Spending growth analysis

### ✅ Feature 6 – Time-of-Day Analysis
- Spending by hour
- Peak spending hour
- Late-night food delivery analysis

### ✅ Feature 7 – Anomaly Detection
- Implemented Z-score based anomaly detection
- Identified unusually large transactions

### ✅ Feature 8 – Spending Archetype Detection
Detected spending personalities based on financial behavior.

---

## 📊 Project Output

The final report includes:

- Executive Summary
- Spending Overview
- Top Spending Categories
- Top Vendors
- Monthly Spending Trends
- Time-of-Day Spending Patterns
- Anomaly Detection
- Spending Archetypes
- Key Insights

---

## 📈 Sample Insights

- E-Commerce was the highest spending category.
- Peak spending activity occurred around 10:00 AM.
- Approximately 20.5% of Food Delivery orders occurred between 9 PM and 2 AM.
- Multiple high-value transactions were detected using Z-score analysis.

---

## 📁 Project Structure

```
SpendDNA/
│
├── SpendDNA_MohammadDhilawala.ipynb
├── Data set for DADS June.csv
├── README.md
└── Output Screenshot.png
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Upload the dataset (`Data set for DADS June.csv`).
3. Run all notebook cells sequentially.
4. View the generated SpendDNA Report.

---

## 📚 Learning Outcomes

This project enhanced my understanding of:

- Data Cleaning
- Data Preprocessing
- Pandas Data Manipulation
- NumPy Operations
- Financial Data Analysis
- Time-Series Analysis
- Anomaly Detection
- Business Insight Generation
- Python Programming

---

## 📌 Conclusion

SpendDNA demonstrates how Python, Pandas, and NumPy can transform raw banking transaction data into meaningful financial insights. The project highlights practical data cleaning, exploratory data analysis, anomaly detection, and behavioral analytics techniques commonly used in the fintech industry.

---

⭐ If you found this project useful, consider giving this repository a star!
