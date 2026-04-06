# 🏦 Bank Loan Analysis — FY 2023

A complete data analytics project on bank loan applications covering data cleaning, SQL analysis, Excel reporting and an interactive Power BI dashboard.

---

## 📌 Project Overview

Analyzed 614 bank loan applications to uncover key patterns in loan approval rates and the impact of education, credit history, property area and income on loan decisions.

---

## 📊 Dashboard Preview

![Bank Loan Dashboard](Bank_loan_dashboar_SS.png)


---

## 📁 Project Structure

bank-loan-analysis/
│
├── README.md
├── loan_cleaned.xlsx
├── bank_loan_dashboard.pbix
├── bank_loan_analysis_ipynb.ipynb
├── query1_approval_rate.xlsx
├── query2_education.xlsx
├── query3_property.xlsx
├── query4_income_loan.xlsx
├── query5_credit_history.xlsx
│
└── images/
    ├── Bank_loan_dashboar_SS.png
    ├── loan_approval_rate.png
    ├── education_vs_approval.png
    ├── credit_history_impact.png
    ├── property_area_approval.png
    └── income_vs_loan.png

---

## 🗂️ Data Stack

Raw Data → Python (Clean) → Excel (Store) → SQL (Query) → Power BI (Visualize)

| Layer      | Tool                          | Purpose                          |
|------------|-------------------------------|----------------------------------|
| Ingestion  | Python · Pandas               | Data loading and cleaning        |
| Storage    | Excel (.xlsx)                 | Cleaned dataset and query results|
| Analysis   | SQL · PostgreSQL              | Business queries and insights    |
| EDA        | Python · Matplotlib · Seaborn | Statistical and visual exploration|
| Reporting  | Power BI                      | Interactive dashboard            |

---

## 📈 Visualizations

### 1️⃣ Loan Approval Rate
![Loan Approval Rate](images/loan_approval_rate.png)
> 68.7% of all applications were approved — 422 out of 614 total applications

---

### 2️⃣ Education vs Loan Approval
![Education vs Approval](images/education_vs_approval.png)
> Graduate applicants dominate approvals with 340 approved vs only 82 non-graduates approved

---

### 3️⃣ Credit History Impact on Loan Approval
![Credit History Impact](images/credit_history_impact.png)
> Applicants with good credit history — 378 approved vs 97 rejected
> Applicants without credit history — only 44 approved vs 95 rejected

---

### 4️⃣ Property Area vs Loan Approval
![Property Area Approval](images/property_area_approval.png)
> Semiurban areas have the highest approvals at 179
> Urban and Rural areas show similar rejection counts around 69 each

---

### 5️⃣ Applicant Income vs Loan Amount
![Income vs Loan](images/income_vs_loan.png)
> Higher income applicants tend to get larger loan amounts
> Most applicants are clustered in the lower income range below 20,000

---

## 🔍 Key Findings

✅ 68.7% approval rate — 422 out of 614 applications approved

🎓 Graduates have significantly higher approval — 340 approved vs 82 non-graduates

🏘️ Semiurban areas lead with 179 approvals across all property areas

💳 Credit history is the strongest factor — 378 approved with good credit vs only 44 without

💰 Large loan applicants earn avg ₹12,039 vs ₹3,788 for small loan applicants

---

## 📈 SQL Queries Covered

Query 1 — Overall loan approval rate
Query 2 — Approval rate by education level
Query 3 — Approval breakdown by property area
Query 4 — Income vs loan amount category
Query 5 — Credit history impact on approval

---

## 📋 Dataset Summary

Total Records     →  614
Total Features    →  14
Target Variable   →  Loan_Status (Y / N)
Approval Rate     →  68.73%
Avg Loan Amount   →  141.17K
Avg Income        →  5,403

---

## 🛠️ Tools Used

Python        →  Pandas · Matplotlib · Seaborn · Jupyter Notebook
SQL           →  PostgreSQL
Excel         →  Query Results · Summary Reports
Power BI      →  Interactive Dashboard · KPI Cards · Slicers

---

## 🚀 How to Use

Step 1  →  Clone this repository
Step 2  →  Open bank_loan_analysis_ipynb.ipynb in Jupyter Notebook
Step 3  →  Open bank_loan_dashboard.pbix in Power BI Desktop
Step 4  →  Open any query file in Excel to view SQL results

---

## 👤 Author

Your Name-: Shivani Sharma
Data Analyst · Python · SQL · Power BI · Excel
