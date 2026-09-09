# Standard Bank Retail Banking Analytics

## 📊 Project Overview

This project is an end-to-end Power BI retail banking analytics solution designed to analyse customer behaviour, deposits, lending, credit risk, and transaction performance.

The report consists of four interactive dashboards that provide both executive-level KPIs and detailed analytical insights.

> **Disclaimer:** This is an independent portfolio project created for educational and demonstration purposes. It is not affiliated with or endorsed by Standard Bank. The data used is synthetic and does not represent actual Standard Bank customer or financial information.

---

## 📈 Dashboard 1 — Executive Summary

Provides a high-level overview of retail banking performance, including customers, deposits, lending, transaction activity, and credit risk.

![Executive Summary](screenshots/Executive%20Summary.png)

### Key Metrics
- Total Customers
- Total Deposits
- Total Loan Book
- Transaction Value
- New Customers
- Default Rate

---

## 👥 Dashboard 2 — Customer & Deposit Analysis

Analyses customer acquisition, segmentation, geographic distribution, account composition, and deposit contribution.

![Customer and Deposit Analysis](screenshots/02-customer-deposit-analysis.png)

### Key Analysis
- Monthly customer acquisition
- Customers by segment
- Customers by province
- Account type distribution
- Deposits by customer segment
- Average deposit per customer

---

## 💳 Dashboard 3 — Credit Risk Analysis

Examines lending exposure and credit risk across loan products, customer segments, and geographic regions.

![Credit Risk Analysis](screenshots/03-credit-risk-analysis.png)

### Key Analysis
- Loan book trend
- Loan book by loan type
- Loans by credit status
- Default rate by loan type
- Loan book by province
- Loan book by customer segment

---

## 💸 Dashboard 4 — Transaction & Channel Analysis

Analyses transaction activity, monetary value, customer transaction behaviour, channel usage, and geographic performance.

![Transaction and Channel Analysis](screenshots/04-transaction-channel-analysis.png)

### Key Analysis
- Monthly transaction value
- Transactions by channel
- Transactions by transaction type
- Transaction value by transaction type
- Transaction value by province
- Transaction value by channel

---

## 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modelling
- Microsoft Excel
- Data Visualisation
- Business Intelligence

---

## 🧮 Example DAX Measures

### Average Deposit per Customer

    Avg Deposit per Customer =
    DIVIDE(
        [Total Deposits],
        [Total Customers],
        0
    )

### Average Loan Value

    Average Loan Value =
    DIVIDE(
        [Total Loan Book],
        [Total Loans],
        0
    )

### Average Transaction Value

    Avg Transaction Value =
    DIVIDE(
        [Transaction Value],
        [Total Transactions],
        0
    )

### Transactions per Customer

    Transactions per Customer =
    DIVIDE(
        [Total Transactions],
        [Transacting Customers],
        0
    )

---

## 💡 Key Business Insights

- Customer and deposit performance varies significantly across customer segments.
- Lending exposure is concentrated across specific loan products and customer segments.
- Default rates vary considerably between lending products.
- Transaction volume and transaction value differ across banking channels.
- Geographic analysis highlights differences in customer, lending, and transaction activity across provinces.

---

## 🎯 Skills Demonstrated

- Dashboard design and UI/UX
- KPI development
- DAX measure development
- Data modelling and relationships
- Customer segmentation analysis
- Credit risk analysis
- Transaction and channel analysis
- Interactive filtering and slicing
- Business insight generation
- Executive-level data storytelling

---

## 📁 Repository Structure

    Standard-Bank-Retail-Banking-Analytics/
    ├── README.md
    ├── Standard-Bank-Retail-Banking-Analytics.pbix
    ├── screenshots/
    │   ├── 01-executive-summary.png
    │   ├── 02-customer-deposit-analysis.png
    │   ├── 03-credit-risk-analysis.png
    │   └── 04-transaction-channel-analysis.png
    └── data/

---

## 👤 Author

**Ushir Goolab**

Business Intelligence | Data Analytics | Power BI | SQL
