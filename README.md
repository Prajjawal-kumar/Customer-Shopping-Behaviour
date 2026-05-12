# Customer Shopping Behaviour Analysis

> End-to-end data analysis project — from raw transactions to a stakeholder-ready Power BI dashboard — uncovering revenue drivers, customer segments, and category performance across 3,900+ records.

---

## Dashboard Preview

<img width="1295" height="696" alt="Customer_shppoing_behavoiur_dashboard" src="https://github.com/user-attachments/assets/f5891ca3-7f78-48e6-8bdd-437e8c6fba14" />


**Key Metrics at a Glance:**
- 3.9K customers analysed
- $59.76 average purchase amount
- 3.75 average review rating
- Clothing dominates both revenue (~$100K) and sales volume (~1,700 units)
- Young Adults are the highest-revenue age group, followed closely by Middle-aged customers
- 73% of customers are non-subscribers — a significant untapped retention opportunity

---

## Problem Statement

Retail businesses often struggle to identify *which* customer segments and product categories drive the most value. This project analyses customer transaction data to answer:
- Which product categories generate the most revenue?
- Which age groups spend the most?
- What is the impact of subscription status on purchasing behaviour?

---

## Dataset

- **Records:** 3,900+ customer transactions
- **Format:** `.csv`
- **Key fields:** Customer ID, Age, Gender, Product Category, Purchase Amount, Review Rating, Subscription Status, Shipping Type, Payment Method

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy, Matplotlib) | Data cleaning, EDA |
| MySQL | SQL queries and data extraction |
| Power BI | Interactive dashboard |
| VS Code | Development environment |

---

## Key Findings

- **Clothing** is the top-performing category — highest in both revenue (~$100K) and sales volume (~1,700 units)
- **Young Adults** generate the most revenue across all age groups, with Middle-aged customers a close second
- **73% of customers are non-subscribers**, representing a major retention and loyalty programme opportunity
- Wrote **15+ SQL queries** to break down revenue by category, age group, and demographics
- Built an **8-KPI Power BI dashboard** with cross-filter slicers for subscription status, gender, category, and shipping type

---

## Dashboard Features

- **KPIs:** Total customers, average purchase amount, average review rating
- **Visuals:** Donut chart (subscription split), bar charts (revenue & sales by category), horizontal bars (revenue & sales by age group)
- **Filters:** Subscription status, gender, product category, shipping type

---

## Project Structure

```
customer-shopping-behaviour/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── customer_behaviour.pbix
│
└── README.md
```

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Prajjawal-kumar/Customer-Shopping-Behaviour.git
   cd Customer-Shopping-Behaviour
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook notebooks/eda_analysis.ipynb
   ```

4. **SQL Analysis**
   - Import `customer_data.csv` into MySQL
   - Run queries from `sql/queries.sql`

5. **Power BI Dashboard**
   - Open `dashboard/customer_behaviour.pbix` in Power BI Desktop
   - Refresh data connection if needed
