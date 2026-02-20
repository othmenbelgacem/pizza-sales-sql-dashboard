# 🍕 Pizza Sales Dashboard (SQL + Excel)

## 📌 Project Overview

This project presents an interactive Excel dashboard built using pizza sales data stored in Microsoft SQL Server.

The goal of this project is to demonstrate:

- Data cleaning and transformation
- SQL data validation and type conversion
- Excel dashboard design
- SQL-Excel integration
- Business KPI analysis

---

## 🗄 Database Information

Database Name: `pizza DB`  
Table Used: `pizza_sales`

The dataset contains:

- Order details
- Order date and time
- Pizza category and size
- Quantity sold
- Unit price and total price

---

## 🛠 Technologies Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Microsoft Excel
- SQL (Data Cleaning & Type Conversion)
- GitHub

---

## 🔄 Data Preparation Process

1. Imported raw CSV into SQL Server.
2. Converted all columns from VARCHAR to appropriate data types:
   - INT
   - DECIMAL(10,2)
   - DATE
   - TIME
3. Validated data using `TRY_CONVERT`.
4. Connected Excel directly to SQL Server.
5. Built interactive Pivot Tables and Dashboard visuals.

---

## 📊 Dashboard Features

The dashboard includes:

- Total Revenue
- Total Orders
- Total Pizzas Sold
- Revenue by Category
- Revenue by Pizza Size
- Sales by Day of Week
- Peak Order Time Analysis

---

## 🎯 Key Insights

- Identified best-selling pizza categories.
- Determined highest revenue days.
- Analyzed peak business hours.
- Compared sales performance by size and category.

---

## 📷 Preview

<img width="987" height="541" alt="image" src="https://github.com/user-attachments/assets/094993b9-41c3-436c-9be8-d8588ebded83" />


---

## 🚀 How to Use

1. Restore or create the database `pizza DB`.
2. Import the `pizza_sales` table.
3. Open the Excel file.
4. Refresh the data connection.
5. Explore the dashboard.

---

## 👨‍💻 Author

Othmen Belgacem  
Senior Data Consultant 
Passionate about SQL, Data Analysis & Dashboard Design
