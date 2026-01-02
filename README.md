# 📊 Sales Data Analysis Dashboard (Excel)
<img src="https://raw.githubusercontent.com/Mazen-Alattar/excel-sales-dashboard/refs/heads/main/Excel-Sales-Dashboard/images/dashboard_preview.png" width="900">

## 📌 Project Overview
This project analyzes real-world sales data from work-related activities using Microsoft Excel.  
The objective is to transform raw data from multiple tables into a clean, analytical data model and present key insights through an interactive dashboard.

The project demonstrates practical experience with **Power Query, Power Pivot, and DAX**, and is designed for **Data Analyst Internship** applications.

---

## 🗂 Dataset Information
- **Type:** Real business data
- **Domain:** Sales
- **Number of records:** ~5,000 rows
- **Source:** Work-related data
- **Number of source tables:** 3

### Main Columns
- Price per Unit  
- Quantity
- Total Sales  
- Product Name  
- Region  
- Customer Name  
- Gender  
- Age  
- Date  

---

## 🔄 Data Preparation & Modeling

### Data Integration
- The dataset was originally stored in **three separate tables**.
- Tables were merged using **Power Query**.
- A relational data model was then created using **Power Pivot**.

---

### Data Cleaning & Transformation (Power Query)
- Removed duplicates and handled missing values.
- Standardized data types and column formats.
- Created new columns extracted from the Date field:
  - **Month**
  - **Day**
- Created a new **Age Segment** column by categorizing the original **Age** column into age groups.

---

## 🧮 Calculations & DAX

### Calculated Columns
- **Total Sales** was calculated using the following formula:  
         Total Sales = Quantity * Price per Unit
- The calculation was:
- Implemented once using **Power Query**
- Recreated using **DAX** after merging tables in **Power Pivot**

---

## 📈 Dashboard Analysis & Insights
The dashboard is fully interactive using **Slicers** and includes:

- Total Sales by Month (Line Chart)
- Total Sales by Region (Bar Chart)
- Gender Distribution (Pie Chart)
- Age Segment Analysis
- Top 10 Products by Total Sales
- Top 5 Customers by Revenue

### Key Insights
- Monthly sales trends reveal seasonal performance patterns.
- Certain regions consistently outperform others in total sales.
- A limited number of products contribute a significant share of total revenue.
- Top customers generate a large portion of overall sales.
- Customer demographics help identify high-value segments.

---

## 🛠 Tools & Technologies
- **Microsoft Excel**
- Power Query (ETL & data cleaning)
- Power Pivot (Data modeling)
- DAX (Calculated columns)
- Pivot Tables
- Interactive Charts & Slicers

---

## 🎯 Project Goal
This project was developed as part of my data analytics portfolio to demonstrate strong Excel-based data analysis and dashboarding skills for **Data Analyst Internship** roles.
