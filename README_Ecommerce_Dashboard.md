
# 📊 E-commerce Sales Dashboard – Power BI Project

## 🧾 Project Overview

This project showcases a **Power BI dashboard** built for an E-commerce dataset. It tracks **sales, profit, quantity, customer performance**, and other key business metrics using interactive visualizations.

---

## 🎯 Objectives

- Visualize total sales, profit, quantity, and AOV
- Analyze sales and profit by category, sub-category, and state
- Compare payment modes and customer-wise sales performance
- Enable interactivity using filters, tooltips, and drill-down

---

## 📁 Dataset Fields Used

### 🔸 Details Table
- `Amount` (Sales value)
- `Profit`
- `Quantity`
- `Category`, `Sub-Category`
- `Payment Mode`
- `Order ID`

### 🔸 Orders Table
- `CustomerName`
- `Order Date`
- `State`, `City`
- `Order ID` (used for relationships)

---

## 🧩 Dashboard Features

| Visual                     | Purpose                              |
|----------------------------|--------------------------------------|
| 💵 **Total Sales Card**       | Shows overall revenue               |
| 💰 **Total Profit Card**      | Displays net profit                 |
| 📦 **Total Quantity Card**    | Units sold                          |
| 🧾 **AOV Card**               | Average Order Value (Sales / Orders)|
| 📍 **Sales by State**        | Horizontal bar chart by region      |
| 📅 **Profit by Month**       | Trends across months                |
| 🛒 **Sales by Customer**     | Top performing customers            |
| 🧾 **Order by Payment Mode** | Donut chart showing payment method  |
| 📊 **Quantity by Category**  | Donut chart of product mix          |
| 📈 **Profit by Sub-Category**| Compare profit by item types        |

---

## 🛠️ Key Features Implemented

- ✅ **Drill-down** by Category and Sub-Category
- ✅ **Tooltips** showing extra info on hover
- ✅ **Filters & Slicers** for interactivity
- ✅ **Data validation** across Orders & Details tables
- ✅ **Responsive layout** with dark theme

---

## 📸 Dashboard Preview

![Dashboard](Screenshot%20dashboard.png)

---

## 💾 How to Use

1. Open Power BI Desktop
2. Load `Details` and `Orders` tables
3. Create relationships via `Order ID`
4. Add visuals and measures using DAX:
    - `Total Sales = SUM(Details[Amount])`
    - `Total Profit = SUM(Details[Profit])`
    - `Quantity Sold = SUM(Details[Quantity])`
    - `AOV = DIVIDE([Total Sales], DISTINCTCOUNT(Orders[Order ID]))`
5. Format visuals and publish to Power BI Service (optional)

---

## 🧠 Learnings

- DAX formulas for KPIs
- Using slicers, drill-through, tooltips
- Designing effective, clean dashboards
- Creating Top N filters and data validation

---

## 🙌 Author

**Suraj Singh**  
Connect on [LinkedIn](https://www.linkedin.com)

---

## 📂 License

This project is for educational and portfolio use only.
