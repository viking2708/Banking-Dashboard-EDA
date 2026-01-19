# 🏦 Banking Analytics Dashboard – Risk & Lending Insights

## 📌 Overview
This project focuses on **risk analytics in the banking and financial services domain**, demonstrating how data-driven dashboards can help banks **minimize credit risk and make informed lending decisions**.

The dashboard is built using **Power BI**, with backend data preparation done in **SQL**. It enables stakeholders to evaluate customer profiles, loan exposure, deposits, and engagement behavior to decide whether a loan should be approved or rejected.

---

## 🎯 Problem Statement
To develop a foundational understanding of **risk analytics in banking** and analyze how data can be used to **reduce the risk of financial loss while lending to customers**.

---

## ✅ Solution
An interactive Power BI dashboard that analyzes customer financial behavior and engagement metrics.  
Based on applicant profiles, the dashboard helps banks decide whether a customer is likely to repay a loan, supporting smarter approval or rejection decisions.

---

## ✨ Key Features

- **Client Risk Profiling**  
  Evaluate repayment capability using income band, deposits, engagement length, and liabilities.

- **Loan Exposure Analysis**  
  Track total exposure across bank loans, business lending, and credit card balances.

- **Deposit Analysis**  
  Visualize deposits across savings, checking, bank deposits, and foreign currency accounts.

- **Fee Revenue Tracking**  
  Calculate total processing fees based on loan amount and fee structure.

- **Customer Engagement Analytics**  
  Measure engagement duration to understand customer lifetime value.

- **Interactive Filters**  
  Slice data dynamically by gender, investment advisor, bank type, income band, and time period.

---

## 🗂 Dataset Description
The dataset consists of **multiple interlinked tables** connected via primary and foreign keys:

- Clients – Banking  
- Banking Relationship  
- Gender  
- Investment Advisor  
- Period  

Together, these tables form a **360-degree customer financial profile**.

---

## 🧹 Data Cleaning & Feature Engineering

- Created **Engagement Timeframe** to classify client lifecycle stage  
- Calculated **Engagement Days** using join date and current date  
- Built **Income Bands** (Low / Mid) from estimated income  
- Derived **Processing Fees** based on fee structure  

---

## 📊 KPIs & Metrics

- Total Clients  
- Total Loan Exposure  
- Bank Loans  
- Business Lending  
- Total Deposits  
- Processing Fees Revenue  
- Savings Account Balance  
- Checking Account Balance  
- Foreign Currency Account Balance  
- Credit Card Balance  
- Client Engagement Length  

Implemented using optimized **DAX functions**:
`SUM`, `SUMX`, `DISTINCTCOUNT`, `DATEDIFF`, `SWITCH`

---

## 🛠 Tools & Technologies

- **Data Wrangling:** SQL  
- **Visualization & Modeling:** Power BI  
- **Measures & Logic:** DAX  
- **Dashboard Design:** Interactive multi-page reports  

---

## 📸 Dashboard Screenshots

### 🏠 Home Dashboard
![Home Dashboard](Screenshot%202026-01-20%20011401.png)

---

### 💳 Loan Analysis Dashboard
![Loan Analysis](Screenshot%202026-01-20%20011447.png)

---

### 💰 Deposit Analysis Dashboard
![Deposit Analysis](Screenshot%202026-01-20%20011511.png)

---

### 📊 Summary Dashboard
![Summary Dashboard](Screenshot%202026-01-20%20011535.png)

---

## 💡 Business Value

This dashboard helps banks:

1. Reduce loan default risk  
2. Make data-backed lending decisions  
3. Identify high-risk and high-value customers  
4. Optimize deposit and lending strategies  
5. Improve overall financial planning and profitability  

---

## 📌 Conclusion
The Banking Analytics Dashboard showcases how modern BI tools can transform raw financial data into **actionable, risk-aware insights**. It empowers banks to balance profitability with risk management while maintaining a customer-centric approach.

---

## 🔮 Future Enhancements

- Predictive risk scoring using machine learning  
- Early warning system for potential defaulters  
- Deeper segmentation by geography and nationality  
- Integration with real-time banking data  

---

## 👤 Author
**Aryan Saxena**  
_Data Analytics | Business Intelligence | Risk Analytics_

---

⭐ If you found this project insightful, feel free to star the repository!
