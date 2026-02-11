# 📊 Customer Trends – Sales & Incentive Analytics

An end-to-end data analytics project analyzing retail customer behavior and simulating commission payouts using **Python, MySQL, and Power BI**.

This project demonstrates financial KPI reporting and rule-based incentive modeling to support data-driven operational decisions.

---

## 🚀 Project Overview

The objective of this project was to transform raw retail transaction data into structured customer-level financial insights and simulate a commission system to evaluate incentive payouts.

The workflow includes:

* Data cleaning & preprocessing (Python)
* Financial KPI modeling (SQL)
* Commission slab simulation (SQL)
* Interactive dashboard reporting (Power BI)

---

## 🛠 Tech Stack

* **Python (Pandas, Jupyter Notebook)** – Data cleaning & exploratory analysis
* **MySQL** – Data storage & KPI modeling
* **SQL (Views, CASE logic)** – Commission rule implementation
* **Power BI** – Visualization & executive dashboard
* **DAX** – KPI calculations

---

## 📂 Project Structure

```
customer-trends/
│
├── customer_shopping_behavior.csv
├── shopping_behavior_analysis.ipynb
├── customer_behavior.sql
├── customer_behavior_dashboard.pbix
└── README.md
```

---

## 📊 Data Modeling

### 1️⃣ Customer Summary Layer

Aggregates transaction-level data into customer-level metrics:

* Total Revenue
* Total Orders
* Average Order Value
* Previous Purchases
* Subscription Status
* Age Group

---

### 2️⃣ Incentive Modeling Layer

Commission rules implemented:

* Revenue < 5,000 → 2%
* 5,000–20,000 → 5%
* > 20,000 → 8%

Additional subscription bonus applied.

Derived metrics include:

* Customer Lifetime Value (CLV)
* Simulated Commission
* Total Incentive Payout

---

## 📈 Dashboard Overview

### 🔹 Executive Performance & Incentive Overview

* Total Revenue
* Total Incentive
* Incentive % of Revenue
* Avg CLV
* Repeat Purchase Rate
* Revenue vs Incentive scatter plot

### 🔹 Customer Revenue & Segmentation Analytics

* Revenue by Category
* Sales by Category
* CLV by Age Group
* Incentive by Subscription Status
* Interactive filters

---

## 🔎 Key Insights

* Incentive payouts scale proportionally with revenue tiers.
* Subscription customers demonstrate higher lifetime value.
* Repeat buyers contribute significantly to total revenue.
* Revenue concentration influences incentive cost exposure.
* Commission slabs can be optimized for improved payout efficiency.

