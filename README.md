# 📊 Bank Loan Power BI Dashboard

This repository contains a **Power BI dashboard** designed to analyze and visualize key metrics related to bank loan applications, funding, repayments, and loan performance. It provides decision-makers with insights into loan quality, borrower profiles, and financial health trends.

---

## 📌 Dashboard Overview

The dashboard is divided into **three main sections**:

### 1. **Summary**
- **Total Loan Applications:** 38.6K  
- **Total Funded Amount:** $435.8M  
- **Total Amount Received:** $473.1M  
- **Avg. Interest Rate:** 12.0%  
- **Avg. DTI (Debt-to-Income):** 13.3%  
- **Good vs Bad Loan Performance**  
  - Good Loan Applications: 33K ($370.2M funded, $435.8M received)  
  - Bad Loan Applications: 5K ($65.5M funded, $37.3M received)  

---

### 2. **Overview**
- **Good vs Bad Loan Distribution**  
- **Amount Received by Month** – seasonal repayment trends.  
- **Amount Received by State & Loan Term (36 vs 60 months).**  
- **Amount Received by Borrower Profile**  
  - Employee length  
  - Loan purpose (debt consolidation, credit card, home improvement, etc.)  
  - Home ownership (mortgage, rent, own).  

---

### 3. **Details**
- Transaction-level loan dataset.  
- Fields include:  
  - Loan ID, Purpose, Home Ownership, Grade/Sub-grade  
  - Funded Amount, Interest Rate, Installments  
  - Amount Received, Issue Date  

This section allows **deep drill-down analysis** on borrower segments and loan performance.

---

## 🎯 Key Insights
- **High proportion of good loans (85%)**, indicating strong lending quality.  
- **Debt consolidation** is the largest loan purpose (~$0.25B received).  
- **Borrowers with mortgages contribute the highest repayments** ($238M+).  
- **Repayments trend upward mid-year** (peaks in May & September).  

---

## 🚀 Usage
- Open the `.pbix` file in **Power BI Desktop**.  
- Use slicers for **State, Loan Grade, Purpose, and Home Ownership** to filter insights.  
- Navigate through **Summary → Overview → Details** for progressive drill-down.  

---

## 📂 Files
- `Bankloan Dashboard.pdf` – Exported version of the Power BI dashboard.  
- `README.md` – Documentation of dashboard features and usage.  

---

## 🛠️ Tech Stack
- **Power BI Desktop**  
- Data visualization: KPIs, bar charts, line charts, pie/donut charts, and tables.  

---

## 📈 Business Value
This dashboard helps:  
- **Credit Risk Teams** → Identify risky loan segments.  
- **Management** → Monitor loan portfolio performance.  
- **Finance Teams** → Track repayment inflows & funding distribution.  
