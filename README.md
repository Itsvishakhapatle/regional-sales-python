# regional-sales-python
Regional Sales Analysis using Python (Pandas) with data cleaning, merging, and business insights generation.
# 📊 Regional Sales Analysis Project

## 🚀 Overview
This project focuses on analyzing regional sales data by combining multiple datasets such as sales orders, customers, products, and regions. The goal is to perform data cleaning, transformation, and extract meaningful business insights like revenue, profit, and performance by region.

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas
---

## 📁 Dataset Details
The project uses multiple sheets from an Excel file:
- Sales Orders
- Customers
- Products
- Regions
- State Regions
- 2017 Budgets

---

## 🔧 Process Workflow

### 1. Data Loading
- Loaded multiple sheets using Pandas
- Stored each sheet into separate DataFrames

### 2. Data Cleaning
- Checked missing values
- Fixed column headers
- Removed unnecessary columns
- Standardized column names (lowercase)

### 3. Data Merging
- Merged datasets using keys like:
  - Customer Index
  - Product Index
  - Region ID
  - State Code

### 4. Feature Engineering
Created new columns:
- `total_cost`
- `profit`
- `profit_margin_per`

### 5. Data Transformation
- Renamed columns for clarity
- Filtered 2017 data for budget comparison
- Exported cleaned datasets

---

## 📊 Key Insights
- Revenue and profit calculated per order
- Region-wise sales performance analyzed
- Budget vs actual comparison (2017)
- Profit margin insights

---

## 📁 Output Files
- `final.csv`
- `2017.csv`
- `final1.csv`

---

## 🎯 Learning Outcomes
- Real-world data merging techniques
- Data cleaning & preprocessing
- Feature engineering
- Business-oriented data analysis

---

## 🔗 Project Status
✅ Completed as part of 7 Days Data Analytics Challenge

---

## 💡 Future Improvements
- Add visual dashboards (Power BI / Tableau)
- Perform deeper EDA
- Build predictive models

---

⭐ If you found this helpful, feel free to star the repo!
