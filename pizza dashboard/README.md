# 🍕 Pizza Sales Analysis Dashboard (Power BI Project)

![Pizza Dashboard Preview](dashboard1.png)

## 📌 Overview

This Power BI project provides a detailed analysis of a pizza restaurant's sales between **Jan 2015 to Dec 2015**. Using transactional data, we built an interactive dashboard that helps identify key trends, sales drivers, and performance insights across time, category, and pizza types.

---

## 🧾 Dataset

- **File**: [`pizza_sales.csv`](pizza%20dataset/pizza_sales.csv)
- **Records**: 48,000+ rows
- **Attributes**:
  - `order_id`, `pizza_id`, `pizza_name_id`, `pizza_category`, `pizza_size`
  - `quantity`, `order_date`, `order_time`, `unit_price`, `total_price`

---

## 🛠️ Tools Used

| Tool       | Purpose                          |
|------------|----------------------------------|
| Power BI   | Dashboard & Visualizations       |
| SQL        | Data Preprocessing & Aggregation |
| Excel/CSV  | Data Format & Storage            |

---

## 🧮 KPIs & SQL Queries

All KPIs were derived using SQL and imported into Power BI for visualization. Refer to the [`PIZZA SALES SQL QUERIES.docx`](PIZZA%20SALES%20SQL%20QUERIES.docx) file for the full list of queries.

### ✔️ Key KPIs:
- **Total Orders**: `21,350`
- **Total Revenue**: `₹817.86K`
- **Average Order Value**: `₹38.31`
- **Average Pizzas per Order**: `2.32`
- **Total Pizzas Sold**: `49,574`

### 🔄 Trend Insights:
- **Peak Days**: Friday and Saturday evenings
- **Peak Months**: July and January
- **Daily Order Pattern**: Consistent weekday performance with higher weekend spikes

---

## 📊 Dashboard Highlights

### 1️⃣ Main Dashboard

![Pizza Dashboard Preview](dashboard1.png)

Includes:
- **Interactive Filters** for date and pizza category
- **Trends by Day and Month**
- **Revenue, Order, and Quantity KPIs**
- **Sales % by Category & Size**
- **Total Quantity Sold by Category**

---

### 2️⃣ Best & Worst Performers

![Best/Worst Sellers](dashboard2.png)

Includes:
- **Top 5 Pizzas by Revenue, Quantity, Orders**
- **Bottom 5 Pizzas by Revenue, Quantity, Orders**
- **Performance Commentary on Seller Insights**

---


---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Pizza Dashboard.pbix` in Power BI Desktop.
3. Load the CSV file if prompted.
4. Interact with the visuals and explore insights!

---

## 📬 Contact

For feedback, suggestions, or collaborations, feel free to connect via GitHub Issues.

---

## ⭐ Acknowledgements

Thanks to the open data and Power BI communities for inspiring this project.

---
