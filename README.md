# 🏦 FraudShield Banking - Fraud Detection Analysis

## 📌 Project Overview
This project analyzes 48,604 banking transactions from the FraudShield Banking Dataset to identify patterns associated with fraudulent financial activities. The project was completed as part of a Data Analytics Mini Project using Excel for data preprocessing and Power BI for interactive dashboard visualization.

---

## 📂 Dataset
- **Source:** [FraudShield Banking Data - Kaggle](https://www.kaggle.com/datasets/algozee/financial-transaction-fraud-dataset)
- **Original Records:** 50,000 rows | 25 columns
- **Cleaned Records:** 48,604 rows | 28 columns
- **Domain:** Finance — Banking Fraud Detection
- **License:** CC0 Public Domain

---

## 🛠️ Tools Used
| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and transformation |
| Power BI Desktop | Data visualization and dashboard |

---

## 🧹 Data Preprocessing (Excel)
- Removed 1,361 duplicate Transaction IDs
- Deleted irrelevant column (Merchant_ID)
- Renamed Pakistani city names to international cities
- Deleted rows with missing ID/Date/Time values
- Filled categorical blanks with "Unknown"
- Filled numerical blanks with column averages
- Added **Is_Repeated_Device** column (COUNTIF formula)
- Added **Is_Repeated_IP_Address** column (COUNTIF formula)
- Added **Transaction_Amount_Category** column (Low/Medium/High)
- Added **Is_High_Distance** column (High Risk/Normal)
- Created 3 Pivot Tables for fraud analysis

---

## 📊 Power BI Dashboard

### Page 1 — Overview
- 4 KPI Cards (Total Transactions, Fraud Cases, Fraud Rate, Normal Transactions)
- Fraud vs Normal Donut Chart
- Fraud by Transaction Type Donut Chart

### Page 2 — Fraud Analysis
- Fraud by Merchant Category (Bar Chart)
- Fraud by Card Type (Pie Chart)
- Fraud by Transaction Amount Category (Column Chart)
- Fraud Trend by Month (Line Chart)

### Page 3 — Geographic Analysis
- Fraud by Transaction Location (Map Chart)
- Interactive Slicers (Location, Card Type, Transaction Type)

---

## 🔍 Key Insights
- **4.87%** overall fraud rate across 48,604 transactions
- **Restaurant** category has the highest fraud count
- **Online** transactions lead fraud by channel at 34.87%
- **Credit and Debit** card fraud is nearly equal (50/50)
- **High value** transactions (7M-9M) have slightly more fraud
- Fraud is spread across **11 global cities**

---

## 📁 Repository Contents
| File | Description |
|---|---|
| `FraudShield_Banking_Data.xlsx` | Cleaned dataset with pivot tables |
| `Data_Visualization.pbix` | Power BI dashboard file |
| `data preprocessing.docx` | Data preprocessing documentation |

---

## 👤 Author
**Juan** — Data Analytics Student
