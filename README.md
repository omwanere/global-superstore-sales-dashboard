# 📊 Global Superstore Sales Dashboard | Power BI & Python

## 📌 Project Overview

This project presents an interactive Power BI dashboard developed using the Global Superstore dataset. The objective was to analyze sales performance, profitability, regional contributions, customer returns, and shipping efficiency to generate actionable business insights.

The dashboard converts raw transactional data into meaningful visualizations, enabling stakeholders to monitor key KPIs and make data-driven decisions.

---

## 🎯 Objectives

* Analyze overall sales and profit performance.
* Identify high-performing product categories.
* Evaluate regional and manager-level performance.
* Analyze product return behavior.
* Assess shipping efficiency and delivery delays.
* Generate business insights for decision-making.

---

## 🛠️ Tools & Technologies

* Power BI
* Python (Pandas, NumPy)
* Jupyter Notebook
* DAX
* Power Query
* CSV Data Sources

---

## 📂 Dataset

The project uses four datasets:

* Orders
* People
* Returns
* Target

Dataset contains:

* 10,000 sales transactions
* Customer information
* Product categories and sub-categories
* Regional sales data
* Shipping information
* Return records
* Sales targets

---

# 📈 Dashboard Pages

## 1. Executive Summary

### KPIs

* Total Sales: **$2.94M**
* Total Profit: **$372.83K**
* Total Orders: **4,596**

### Visualization

* Sales Trend (2015–2018)

### Key Insight

Sales increased from **$478K in 2015** to **$1.04M in 2018**, demonstrating strong business growth.

---

## 2. Category Performance Analysis

### Visualizations

* Sales by Category
* Profit Margin by Category

### Results

| Category        |  Sales | Profit Margin |
| --------------- | -----: | ------------: |
| Technology      | $1.11M |        12.97% |
| Office Supplies | $1.05M |        15.26% |
| Furniture       | $0.78M |         8.84% |

### Key Insights

* Technology generated the highest revenue.
* Office Supplies achieved the highest profit margin.
* Furniture consistently underperformed in profitability.

---

## 3. Regional & Manager Performance

### Visualizations

* Sales by Region
* Sales by Manager
* Profit by Manager

### Regional Performance

| Region  |  Sales |
| ------- | -----: |
| Central | $1.72M |
| North   | $0.63M |
| South   | $0.59M |

### Manager Performance

| Manager          |  Sales | Profit |
| ---------------- | -----: | -----: |
| Emily Burns      | $1.72M |  $216K |
| Ross DeVincentis | $0.63M |   $92K |
| Damala Kotsonis  | $0.59M |   $66K |

### Key Insights

* Central region contributed **58.56%** of total sales.
* Emily Burns was the highest-performing manager in both sales and profit.

---

## 4. Customer Experience & Operational Risk

### Visualizations

* Return Rate by Category
* Average Delivery Days by Ship Mode

### Return Rate

| Category        | Return Rate |
| --------------- | ----------: |
| Technology      |       7.07% |
| Furniture       |       6.60% |
| Office Supplies |       6.12% |

### Average Delivery Time

| Ship Mode      | Days |
| -------------- | ---: |
| Same Day       | 0.04 |
| First Class    | 2.20 |
| Second Class   | 3.24 |
| Standard Class | 5.03 |

### Key Insights

* Technology recorded the highest return rate.
* Approximately **19.34%** of orders experienced delivery delays.
* Standard Class shipping required the longest delivery time.

---

# 🧹 Data Cleaning & Preparation

Performed using Python and Power Query:

* Converted Excel serial dates into standard date format.
* Cleaned inconsistent Quantity values.
* Handled mixed data types.
* Created calculated columns and DAX measures.
* Built relationships between multiple datasets.
* Performed aggregations and KPI calculations.

---

# 💡 Business Insights

* Sales grew by over **118%** between 2015 and 2018.
* Technology was the highest revenue-generating category.
* Office Supplies achieved the best profit margin.
* Central region dominated overall sales performance.
* Emily Burns was the top-performing manager.
* Technology products showed the highest return risk.
* Nearly one-fifth of orders experienced delivery delays.

---

---

# 🚀 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Business Intelligence Reporting
* Dashboard Design
* KPI Development
* DAX Calculations
* Power BI Visualization
* Python Data Analysis

---

# 📁 Repository Structure

```text
global-superstore-sales-dashboard/
│
├── README.md
├── Global_Superstore_Dashboard.pbix
├── Data_Analysis.ipynb
├── Dataset/
  ├── Orders.csv
  ├── People.csv
  ├── Returns.csv
  └── Target.csv

```

---

**Om Wanere**

### Connect With Me

* LinkedIn: linkedin.com/in/omwanere
* GitHub: github.com/omwanere

---

⭐ If you found this project helpful, consider giving it a star.
