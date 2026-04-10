# Data Analysis Project

## Overview

This project demonstrates the **end-to-end data analysis process**, from data exploration to visualization and reporting.
The goal is to extract meaningful insights from raw data using **Python, SQL, and Power BI**, and communicate the findings through an **interactive dashboard and presentation report**.

---

## Dataset

* The dataset used in this project contains records related to customer behavior, sales, and transactions.
* Format: `.csv` file
* Key features include:

  * **Customer ID, Age, Gender**
  * **Product Category, Purchase Amount**
  * **Date, Location, Payment Method**
---

## Tools & Technologies

* **Python** (for data cleaning and EDA)

  * Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
* **MySQL** (for running SQL queries and data extraction)
* **Power BI** (for dashboard creation and visualization)
* **Gamma App** (for generating presentation slides)
* **Jupyter Notebook / VS Code** (for coding and documentation)

---

## Steps & Workflow

1. **Data Loading & Inspection**

   * Import dataset using Pandas
   * Check structure, null values, and data types

2. **Data Cleaning**

   * Handle missing values and duplicates
   * Format dates, normalize categories, and remove inconsistencies

3. **Exploratory Data Analysis (EDA)**

   * Perform descriptive statistics
   * Visualize data trends and relationships using Matplotlib & Seaborn

4. **SQL Queries (MySQL)**

   * Import the cleaned dataset into MySQL
   * Run analytical queries such as:

     * Total sales per category
     * Top customers by revenue
     * Monthly trends

5. **Power BI Dashboard**

   * Connect Power BI to the MySQL database
   * Create interactive visuals:

     * Sales by region
     * Product performance
     * Customer segmentation

6. **Report & Presentation**

   * Summarize findings in a structured report
   * Use **Gamma App** to create a visual, AI-generated PPT presentation highlighting insights

---

## Dashboard Overview

The Power BI dashboard includes:

* **KPIs:** Total Sales, Average Purchase Value, Customer Count
* **Visuals:** Bar charts, Line charts, and Donut charts
* **Filters:** Date range, Product category, Region

*(You can attach a dashboard screenshot here)*

---

## Results & Insights

* Identified key customer segments driving majority of revenue
* Discovered seasonal patterns affecting sales
* Recommended marketing focus areas for underperforming regions

---

## How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/data-analysis-project.git
   cd data-analysis-project
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Python scripts or Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   Open the `.ipynb` file and execute cells step-by-step.

4. **Import data to MySQL**

   * Create a database (e.g., `data_analysis_db`)
   * Import the cleaned CSV file
   * Run SQL queries provided in `sql_queries.sql`

5. **Open Power BI dashboard**

   * Load the `.pbix` file
   * Refresh data connection

6. **View presentation**

   * Open the Gamma presentation link (included in the report folder)

---



