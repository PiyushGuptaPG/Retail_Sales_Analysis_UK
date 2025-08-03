# 🛍️ Retail Sales Analysis (John Lewis UK Case Study)

## 📌 Project Overview
This project focuses on analyzing **retail sales data** to uncover insights into sales performance, profitability, customer trends, and product-level performance. It replicates a real-world business scenario using Python and data analytics techniques to generate actionable insights that can support strategic decisions in the retail industry.

---

## 🎯 Objectives
- Perform **data cleaning and preparation** for accurate analysis.
- Analyze **sales trends** across time (monthly & quarterly).
- Identify **top-performing regions, product categories, and sales representatives**.
- Calculate and visualize **key KPIs (Total Sales, Profit %, Average Order Value)**.
- Provide **data-driven business recommendations**.

---

## 🛠️ Tools & Libraries
- **Python**: Pandas, NumPy (Data Analysis & Manipulation)
- **Visualization**: Matplotlib, Seaborn, Plotly (Interactive Plots)
- **Jupyter Notebook** (Exploratory Analysis & storytelling)
- **Excel/CSV** (Initial data storage)
- **GitHub**: For portfolio and version control

---

## 📂 Project Workflow

### 1️⃣ Data Import & Cleaning
- Imported data using **Pandas**.
- Handled missing values using `.fillna()` and `.dropna()`.
- Removed duplicates using `.drop_duplicates()`.
- Standardized column names and corrected data types with `.astype()` and `pd.to_datetime()`.

### 2️⃣ Exploratory Data Analysis (EDA)
- Used `groupby()` and `pivot_table()` to summarize data.
- Conducted multi-level analysis by **Region → Category → Profit**.
- Derived KPIs: Total Sales, Profit %, and Avg Order Value (AOV).

### 3️⃣ Visualization
- **Line charts**: Sales and profit trends (monthly & quarterly).
- **Bar charts**: Profit by category and sales reps.
- **Pie charts**: Regional sales distribution.
- **KPI cards**: Total Sales, Profit %, AOV displayed in Python.

### 4️⃣ Insights & Business Recommendations
- **Seasonality detected**: Higher sales during Q4 (holiday season).
- **Electronics**: Highest revenue contributor, but lower margins.
- **Furniture**: Lower sales volume but better profit margins.
- **North Region**: Highest sales, but South performed better in profitability.

### 5️⃣ Future Improvements
- Integrate **forecasting models (ARIMA/Exponential Smoothing)** to predict future sales.
- Build **interactive dashboards** using Plotly/Dash or Power BI.
- Segment customers to design targeted marketing campaigns.

---

## 📊 Key Analysis & Visual Outputs
### ✅ Sample Visuals:
1. **Sales Trend (2023):** Clear upward trend with Q4 spikes.
<img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/77874291-29fd-4dee-9924-9a73e2ada520" />

3. **Profit by Category:** Furniture leads in profitability despite lower volume.
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/7ecfd260-20a3-48ae-a87e-fe872c3a6e82" />


5. **Regional Analysis:** North dominates sales volume, South excels in profit margin.
<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/ab67d684-59b2-47f8-9875-cefacd0d7016" />


7. **KPI Dashboard:** 
   - Total Sales: **£5.02 Million**
   
     <img width="390" height="190" alt="image" src="https://github.com/user-attachments/assets/4f16283c-f8d1-44c4-b97a-ed3c2b819ef7" />

   - Total Profit: **£507.10k**
     
     <img width="390" height="190" alt="image" src="https://github.com/user-attachments/assets/770a15f7-9d6b-47ab-8868-5e0460de3711" />

   - Total Qantity Sold: **25.36k**
     
     <img width="371" height="190" alt="image" src="https://github.com/user-attachments/assets/fa3b32e4-b2e7-43d6-a02e-2a8f0cfa5aa4" />

   



---

## 📂 Repository Structure
