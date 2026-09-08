# Banking Data Analysis Project

An end-to-end data analytics project analyzing a retail bank dataset (PrimeBank) across customers, accounts, loans, card transactions, and customer support to uncover insights on branch performance, credit risk, and fraud.

---

## 🛠️ Tools Used
- **SQL (PostgreSQL)**: Database schema design, data loading, and querying business insights.
- **Power BI**: Interactive 8-page dashboard for visual analytics.
- **Excel**: Data exploration and quick pivot dashboard.

---

## 📊 Project Workflow

1. **Database Setup**: Designed relational schema with 10 tables and primary/foreign keys.
2. **SQL Analysis**: Wrote SQL queries answering 40+ questions across customer trends, branch deposits, loan defaults, and risk.
3. **Dashboards**: Built interactive Power BI and Excel reports with filters for branches, loans, and time periods.
4. **Insights & Recommendations**: Summarized key business findings to improve risk management and customer satisfaction.

---

## 🗄️ Database Schema
The dataset consists of 10 related tables: `branches`, `employees`, `customers`, `accounts`, `loans`, `loan_payments`, `cards`, `card_transactions`, `transactions`, and `support_tickets`.

---

## 💡 Key Insights

- **Scale**: Analyzed 60,000 customers across 150 branches with ₹3B+ in deposits and ₹9B+ in loans.
- **Branch Performance**: Top deposit branches include Kochi Branch 2, Bhopal Branch 8, and Chennai Branch 3. Maharashtra accounts for over 16% of total deposits.
- **Loans & Default Risk**: About 14,000 active loans with an average interest rate of 11.5%. Default rates are highest in Education and Gold loan categories.
- **Card Fraud**: Fraudulent card transactions stand at around 0.50% of total card transactions.
- **Customer Support**: 25,000 support tickets logged with an average customer satisfaction score of 3.0 / 5.

---

## 📌 Business Recommendations

1. **Tighten Credit Checks**: Implement stricter credit scoring and verification for loan categories with higher default rates.
2. **Proactive EMI Follow-ups**: Set up automated reminders for borrowers with repeated late payments before accounts turn delinquent.
3. **Targeted Fraud Alerts**: Enhance fraud detection rules on high-risk merchant categories.
4. **Improve Support Quality**: Focus on faster resolution times for high-volume complaint categories to boost satisfaction scores.

---

## 📁 Repository Structure

```
Banking_data_analysis/
├── Data/              # Raw CSV datasets
├── Sechma/            # Database schema diagrams
├── Sql/               # SQL schema and analysis scripts (01 to 10)
├── Power bi/          # Power BI report (.pbix) and dashboard images
├── Excel/             # Excel analysis and pivot charts
├── Project Report.docx# Detailed report
└── README.md
```

