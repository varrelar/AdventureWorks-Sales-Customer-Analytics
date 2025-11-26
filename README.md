# AdventureWorks Sales & Customer Analytics

This project provides an end-to-end analysis of the AdventureWorks retail dataset, focusing on sales trends, customer demographics, product performance, and regional insights. The notebook demonstrates core data analytics skills including data cleaning, exploratory analysis, feature engineering, and insight synthesis.

---

## 📌 Project Objectives

- Build a unified analytical dataset from multiple fact and dimension tables  
- Assess data quality and perform necessary cleaning  
- Conduct exploratory data analysis (EDA) across customers, products, time, and geography  
- Evaluate sales trends and category performance  
- Generate actionable business insights and recommendations  

---

## 🗂️ Dataset Description

Seven relational tables are used:

| Table | Description |
|-------|-------------|
| **InternetSales** | Transaction-level sales data |
| **Customer** | Demographics and personal information |
| **Product** | Product-level metadata |
| **ProductCategory** | Category hierarchy and attributes |
| **Geography** | City, state, and country information |
| **SalesTerritory** | Regional territory groupings |
| **Employee** | Sales personnel details |

The tables follow a **star schema**, where the InternetSales fact table connects to key dimensions.

---

## 🔧 Key Steps Performed

### **1. Data Quality Assessment**
- Missing values detected on Product and Customer attributes  
- No missing values in InternetSales  
- Minor imputations applied where appropriate  

### **2. Cleaning & Feature Engineering**
- Standardized column names and data types  
- Derived features:
  - `total_ordervalue`
  - `customer_age`
- Imputed subcategory and color fields  
- Merged all tables into one analytical dataset  

### **3. Exploratory Data Analysis (EDA)**
- **Univariate:** sales distribution, customer age, profit, delivery metrics  
- **Categorical:** product categories, territories, colors  
- **Time-series:** yearly and quarterly performance trends  
- **Bivariate:** sales vs age, category vs profit, region vs sales  

---

## 📊 Key Insights

### **1. Sales peaked sharply in 2020**
A significant performance spike appears in 2020 before declining in 2021.

### **2. Revenue is highly concentrated**
A small number of high-value transactions dominate total revenue.

### **3. Middle-aged customers drive the business**
Consumers aged **35–55** consistently generate the highest sales.

### **4. Product performance is uneven**
Some categories show strong sales but low margins, revealing optimization opportunities.

### **5. Operational consistency**
DeliveryDays is fixed at 7 for all records—indicating stable SLA compliance.

---

## 🧭 Recommendations

### **Customer Strategy**
- Focus acquisition and retention on high-value age groups (35–55)  
- Develop loyalty programs and targeted segmentation campaigns  

### **Product Strategy**
- Reassess pricing on low-margin categories  
- Introduce bundling or promotional strategies for weak products  

### **Sales & Operational Strategy**
- Investigate root causes of the 2021 decline  
- Strengthen presence in high-performing territories  
- Explore opportunities to optimize delivery consistency further  

---

## 🧩 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib  
- Jupyter Notebook  
- Data Cleaning / EDA / Feature Engineering  

---

## 🔗 Notebook Link
**https://github.com/varrelar/AdventureWorks-Analysis**

---

## 📬 Contact  
Feel free to reach out for feedback or collaboration opportunities!

