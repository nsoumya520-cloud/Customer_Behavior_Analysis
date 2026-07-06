# 📊 Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI — from raw transaction data to a business report and presentation.

---

## 🔍 Overview

This project analyzes customer shopping behavior to extract meaningful business insights from retail transaction data. It covers the complete analytics workflow: data cleaning, exploratory data analysis (EDA), SQL-based analysis on a MySQL server, dashboard creation, and business reporting/presentation.

**Goal:** Demonstrate practical, job-ready data analyst skills — from raw data to data-driven business recommendations.

---

## 📁 Dataset

The dataset (`customer_shopping_behavior.csv`) contains customer shopping and transaction information, including:

- Customer demographics (age, gender, location)
- Product categories and items purchased
- Purchase amounts
- Payment methods
- Discount and promo code usage
- Seasonal purchase patterns
- Review ratings
- Shopping preferences (e.g., subscription status, shipping type)

This data is used to understand customer behavior, purchasing trends, and the factors that influence sales performance.

---

## 🛠️ Tools & Technologies

| Category | Tools Used |
|---|---|
| Programming & Analysis | Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook |
| Database | MySQL, SQL |
| Visualization | Power BI |
| Reporting & Presentation | Microsoft PowerPoint, Gamma AI |
| Version Control | Git & GitHub |

---

## 🧭 Project Workflow

### 1. Data Loading
Imported the dataset into Python using Pandas and performed an initial inspection of data structure and quality.

### 2. Data Cleaning
- Checked for missing values
- Removed duplicate records
- Standardized categorical variables
- Corrected inconsistent data entries
- Prepared the dataset for analysis

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics
- Examined purchasing behavior
- Identified top-selling categories and products
- Evaluated discount and promo code effectiveness
- Studied seasonal shopping trends
- Generated visualizations to support findings

### 4. SQL Analysis
The cleaned dataset was loaded into MySQL for advanced analysis. Sample business questions addressed:

- Which product categories generate the highest sales?
- What are the most purchased products?
- How do discounts affect purchasing behavior?
- Which customer segments contribute the most revenue?
- What seasonal trends can be observed?
- Which products rank highest within each category?

**Advanced SQL concepts used:** Aggregate Functions, GROUP BY, CASE Statements, Common Table Expressions (CTEs), Window Functions, Ranking Functions

### 5. Dashboard Development
A Power BI dashboard was created to provide interactive insights and visual summaries.

### 6. Reporting & Presentation
- Created a detailed project report summarizing methodology and findings
- Developed a professional presentation using Gamma AI and PowerPoint
- Presented business insights and recommendations

---

## 📈 Dashboard

The Power BI dashboard (`Customer_behaviour_analysis.pbix`) includes:

- **Sales Overview** — total sales, average purchase amount
- **Customer Demographics** — age, gender, and location distribution
- **Product Performance** — top categories and best-selling items
- **Discount Analysis** — discount and promo code utilization rate
- **Seasonal Trends** — sales patterns across seasons
- **Interactive Filters & Slicers** — for stakeholder-driven exploration

The dashboard enables stakeholders to quickly identify patterns and make data-driven decisions.

---

## ✅ Results & Key Insights

- Certain product categories consistently outperform others in sales.
- Discounts and promotional campaigns influence purchasing behavior.
- Customer demographics impact buying preferences.
- Seasonal trends affect transaction volume and revenue.
- Product popularity varies significantly across categories.

These insights can help businesses optimize marketing strategies, inventory planning, and customer engagement.

---

## ▶️ How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/nsoumya520-cloud/Customer_Behavior_Analysis.git
cd your-repo-name
```

### 2. Install required Python packages
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Set up MySQL
- Import `customer_shopping_behavior.csv` into your local MySQL server
- Run the queries in `customer_behaviour.sql` to reproduce the SQL-based analysis

### 4. Run the analysis
- Open `Customer_behaviour_analysis_python.ipynb` in Jupyter Notebook
- Run all cells to reproduce the data cleaning, EDA, and visualizations

### 5. View the dashboard
- Open `Customer_behaviour_analysis.pbix` in Power BI Desktop

### 6. View the report & presentation
- `Customer Shopping Behavior Analysis report.pdf` — full written report
- `Customer-Shopping-Behavior-Analysis.pptx` — presentation (built with Gamma AI)

---

## 📂 Project Structure

```
├── customer_shopping_behavior.csv                     # Raw dataset
├── Customer_behaviour_analysis_python.ipynb           # Python: cleaning & EDA
├── customer_behaviour.sql                             # SQL analysis queries
├── Customer_behaviour_analysis.pbix                   # Power BI dashboard
├── Customer Shopping Behavior Analysis report.pdf     # Final written report
├── Customer-Shopping-Behavior-Analysis.pptx           # Presentation (Gamma AI)
├── Business Problem Document.pdf                      # Problem statement
└── README.md                                          # Project documentation
```

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- SQL Querying & Database Management
- Data Visualization
- Dashboard Development
- Business Reporting & Presentation

These skills are directly relevant to **Data Analyst** and **Business Analyst** roles.

---

## 🙋 About

**Author:** * Soumya Ranjan Nayak
Aspiring Data Analyst | SQL | Python | Power BI

Feel free to explore the repository and reach out with any questions or feedback!
