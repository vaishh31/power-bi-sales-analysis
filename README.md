

# 📊 Sales Analysis Dashboard – Power BI

## 📌 Project Overview
This project is an end-to-end **Sales Analysis Dashboard** built using **Power BI Desktop**.  
The goal of this dashboard is to help stakeholders understand overall sales performance, identify top and underperforming products, analyze category and regional trends, and track sales over time.

The project covers the complete Power BI workflow — from data cleaning and modeling to DAX calculations and dashboard design.

---

## 🧰 Tools & Technologies Used
- Power BI Desktop  
- Power Query  
- DAX (Data Analysis Expressions)  
- GitHub  

---

## 📂 Data Description
The dataset contains aggregated sales information at the product level along with category, city, and year details.

> Note: The dataset does not include unit-level or cost data. Therefore, the analysis focuses on **sales performance and trends** rather than profit-based metrics.

---

## ⚙️ Data Cleaning & Preparation (Power Query)
The following steps were performed using **Power Query**:
- Removed unnecessary columns
- Renamed columns for clarity
- Corrected data types (numeric, text, date)
- Handled missing and inconsistent values
- Ensured data was clean and analysis-ready before loading into the model

---

## 🧠 Data Modeling
- Used a **star schema approach**
- Created a dedicated **Date table** using DAX
- Established proper **one-to-many relationships**
- Ensured correct filter direction for accurate analysis
- Marked the Date table to enable time intelligence

---

## 🧮 DAX Measures Created
Key DAX measures used in the report include:
- **Total Sales**
- **Year-over-Year Sales**
- **Sales Contribution %**
- **Top 5 Selling Products (using RANKX)**
- **Top 5 Underperforming Products**
- **Sales Trend over Time**

These measures allow dynamic analysis based on slicers and filters.

---

## 📊 Dashboard Visuals & Insights
The dashboard includes:
- **KPI Cards** for high-level sales overview
- **Line Chart** for yearly sales trends
- **Bar Charts** for top and underperforming products
- **Stacked Column Chart** for category and region comparison
- **City-level sales analysis**
- **Slicers** for Year and Category to enable interactivity

The report is designed to be clean, readable, and business-focused.

---

## 🎯 Key Business Insights
- Identifies the highest and lowest performing products
- Highlights sales trends across different years
- Shows which categories and cities contribute most to sales
- Enables quick decision-making through interactive visuals

---

## 🖼 Dashboard Preview
Screenshots of the dashboard are included in the `screenshots` folder.

---

## 🔒 Power BI Service Note
This report has not been published to Power BI Service due to the absence of a work or school account.  
The project is shared via GitHub with the PBIX file and documentation for portfolio and interview purposes.

---

## 🚀 Conclusion
This project demonstrates my ability to:
- Clean and prepare data using Power Query
- Build efficient data models
- Write meaningful DAX measures
- Design intuitive and insightful dashboards
- Apply business thinking to data analysis

---

📬 Feel free to explore the PBIX file or reach out for feedback and discussion.

