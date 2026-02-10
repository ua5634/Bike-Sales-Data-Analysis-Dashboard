# 🚲 Bike Sales Data Analysis Dashboard

## 📌 Project Overview
This project focuses on analyzing bike rental sales data using **SQL** and visualizing key insights using **Power BI**.  
The goal is to understand revenue patterns, rider behavior, and time-based trends to support data-driven decision-making.

---

## 🛠️ Tools & Technologies
- **SQL** – Data cleaning, transformation, and analysis  
- **Power BI** – Interactive dashboards & visualizations  
- **CSV** – Data exchange between SQL and Power BI  

---

## 📂 Dataset Description
The dataset contains bike rental information with the following key attributes:
- `dteday` – Date of rental  
- `hr` – Hour of the day  
- `season` – Season of the year  
- `weekday` – Day of the week  
- `rider_type` – Casual or Registered  
- `price`, `revenue`, `profit` – Financial metrics  
- `riders` – Number of riders  

---

## 🔄 Data Processing (SQL)
- Cleaned raw data and handled data type conversions  
- Created calculated fields for revenue and profit  
- Filtered and aggregated data by hour, date, and rider type  
- Exported final dataset to CSV for visualization  

---

## 📊 Power BI Dashboard Features
- Interactive filters for **Hour, Date, Weekday, and Rider Type**
- Time-based analysis using **Year / Quarter / Month / Day hierarchy**
- Revenue and profit comparison across different time periods
- Identification of peak hours and high-performing days

---

## 📈 Key Insights
- Midday and evening hours generate higher revenue
- Weekdays such as Wednesday and Friday show stronger performance
- Registered riders contribute the majority of total revenue
- Seasonal trends significantly impact rider demand

---

## 📷 Dashboard Preview
*(Add screenshots of your Power BI dashboard here)*

---

## 📁 Repository Structure
```text
├── SQL/
│   └── bike_sales_analysis.sql
├── Data/
│   └── cleaned_bike_data.csv
├── PowerBI/
│   └── Bike_Sales_Dashboard.pbix
└── README.md


