
# 📊 blinkit-PowerBI-das

## 📌 Project Overview
This project is a Power BI dashboard created to analyze Blinkit's (formerly Grofers) sales performance, customer behavior, and delivery efficiency.  
The goal is to provide insights that help track business growth, improve delivery operations, and understand purchasing patterns.

This dashboard is ideal for:
- Data Analytics Portfolio
- Power BI Practice
- Business Insights Case Studies

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** for data cleaning
- **DAX** for calculated measures
- **Excel / CSV** for dataset


Blinkit-PowerBI-Dashboard/
│
├── report/
│ └── Blinkit_Dashboard.pbix
│
├── data/
│ └── dataset.csv (or multiple CSV files)
│
├── images/
│ ├── overview.png
│ ├── sales_analysis.png
│ └── delivery_performance.png
│
└── README.md

## 📈 Dashboard Insights
### 👉 **1. Sales Overview**
- Total Sales  
- Total Orders  
- Average Order Value  
- Category-wise revenue  
- Daily/Monthly trends  

### 👉 **2. Customer Analytics**
- New vs Returning customers  
- Customer retention  
- Customer segmentation  
- Purchase frequency  

### 👉 **3. Delivery Performance**
- Average delivery time  
- On-time delivery percentage  
- City/Area-wise delivery analysis  
- Delivery partner performance  

---

## 🖼 Dashboard Preview
(Add screenshots in the images folder and then reference here)

![Overview](images/overview.png)
![Sales Analysis](images/sales_analysis.png)
![Delivery Performance](images/delivery_performance.png)

---

## 📂 How to Use
1. Download the `.pbix` file from the `/report` folder  
2. Open in **Power BI Desktop**  
3. Load/Refresh data (if dataset provided)  
4. Explore the report pages and insights  

---

## 🧮 DAX Measures Used (Examples)
```DAX
Total Sales = SUM(Orders[Revenue])

Total Orders = COUNTROWS(Orders)

Average Delivery Time = AVERAGE(Orders[Delivery_Time_Minutes])

AOV = [Total Sales] / [Total Orders]

🎯 Key Learnings

Data modeling and relationship building in Power BI

Cleaning and transforming data using Power Query

Creating KPI cards, visuals, and reports

Using DAX for measures and calculations

Designing interactive dashboards
