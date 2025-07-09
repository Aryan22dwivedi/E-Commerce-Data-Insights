# E-Commerce-Data-Insights
This is a visual representation of a E commerce  platform 
# 🛒 E-Commerce Data Insights

## 📌 Project Overview

**E-Commerce platforms** generate large volumes of transactional data. This project aims to extract **actionable business insights** from customer and sales data to help identify:

- Top-selling products
- High-value customers
- Revenue by region
- Peak shopping hours
- User retention patterns

---

## 🎯 Problem Statement

E-commerce platforms need to know **what products and users drive revenue** to improve stocking, marketing, and customer loyalty strategies.

---

## 🎯 Objective

Explore sales and customer data to derive **insights** on:

- Product performance
- Customer behavior
- Time-based trends
- Regional sales distribution

---

## 📁 Dataset Description

The dataset used is a **CSV file** that simulates real e-commerce transactions. It contains the following attributes:

| Column       | Description                                 |
|--------------|---------------------------------------------|
| `InvoiceNo`  | Unique identifier for the transaction        |
| `StockCode`  | Unique code representing the product         |
| `Description`| Name of the product                          |
| `Quantity`   | Number of units purchased                    |
| `InvoiceDate`| Date and time of purchase                    |
| `UnitPrice`  | Price per unit of product                    |
| `CustomerID` | Unique identifier for the customer           |
| `Country`    | Customer’s country                           |
| `TotalPrice` | Total revenue for the transaction (Qty × Price) |
![image](https://github.com/user-attachments/assets/a35d0d9f-5c6d-4947-af6c-8ac05427084c)

---

## 🛠️ Tools & Technologies

- **Power BI**: For interactive data visualization
- **DAX**: For creating new measures an columns
- **CSV File Format**: For data storage and transfer

---

## 📊 Key Visualizations in Power BI

| Insight Area           | Visual Type       | Description                                      |
|------------------------|-------------------|--------------------------------------------------|
| Top Products           | Bar Chart         | Top 10 products by total revenue                 |
| Revenue by Hour        | Line Chart        | Peak purchase hours throughout the day           |
| User Retention         | Pie Chart         | Comparison of returning vs one-time users        |
| Revenue by Country     | Horizontal Bar    | Top countries contributing to revenue            |
| Top Customers          | Bar Chart         | Highest-spending customers                       |
| KPIs                   | Cards             | Total Revenue, Total Orders, Unique Customers    |

![Power BI Desktop 04_07_2025 20_20_48](https://github.com/user-attachments/assets/ea841359-5ad3-4578-aa78-fe7470ce40cf)

---

## 📈 Insights Generated

- Identify **which products to stock** based on total revenue
- Determine **when users shop most** to plan marketing campaigns
- Recognize **loyal users** for rewards and retention strategies
- Understand **geographic revenue patterns**

---

## 📂 How to Use

1. Clone the repository or download the CSV file
2. Open **Power BI Desktop**
3. Load `ecommerce_dataset.csv` file
4. Create visuals using fields described above
5. Optionally create custom columns like:
   - `OrderHour = HOUR([InvoiceDate])`
   - `UserType = IF([OrderCount] > 1, "Returning", "One-Time")`
6. Save and publish your report/dashboard.

---

## 👨‍💻 Author

**Aryan**  
E-Commerce Data Insights Project — Powered by Power BI.
