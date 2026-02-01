# 🛒 Amazon Sales Dashboard – Power BI

## 👋 About This Project
This project is a **Power BI dashboard inspired by Amazon-style sales analytics**, built to understand **sales performance, product behavior, and customer interaction** across multiple levels — from a high-level overview to individual product insights.

The idea behind this dashboard was simple:  
👉 *If I were a business or category manager, what questions would I want answered quickly and visually?*

---

## 🎯 What This Dashboard Helps Answer
- How are **overall sales, units, and sellers** performing?
- Which **states and cities** contribute the most to sales?
- How do different **products** perform over time?
- What happens when a user drills down from **overview → product → product view**?
- How do **returns, reviews, and units sold** change month over month?

---

## 📊 Dashboard Pages Explained

### 1️⃣ Overview Page
**Purpose:** Quick executive-level snapshot  

**Key Insights:**
- Total Sales, Units Sold, Seller Count  
- Sales by State & City  
- Time-based sales trend  
- Order status tracking (Cancelled, Shipped, Delivered, Returned, etc.)  
- Toggle between **Sales** and **Units** for flexible analysis  

📷 **Overview Page Screenshot:**  
![Overview Preview](https://github.com/100rya-py/Amazon-Dashboard/blob/main/Overview%20Page.png)

---

### 2️⃣ Product Page
**Purpose:** Category & product-level comparison  

**What You Can Explore:**
- Product listings with images
- Category-wise browsing experience
- Sales performance by individual products
- Visual comparison across multiple items at once  

This page is designed to **feel like an actual product catalog**, while still delivering analytics underneath.

📷 **Product Page Screenshot:**  
![Product Preview](https://github.com/100rya-py/Amazon-Dashboard/blob/main/Product%20Page.png)

---

### 3️⃣ Product View Page
**Purpose:** Deep-dive into a single product  

**Key Metrics Tracked:**
- Sale Amount  
- Sale Units  
- Returns (Loss)  
- Reviews  
- Monthly sales trend  

This view simulates how a business user might **analyze the full lifecycle of a product** — performance, customer response, and stability over time.

📷 **Product View Page Screenshot:**  
![Product View Preview](https://github.com/100rya-py/Amazon-Dashboard/blob/main/Product%20View%20Page.png)

---

## ⏱️ Time Intelligence & DAX Logic
This dashboard uses **Power BI DAX Time Intelligence** to handle real-world reporting needs, including:

- Month-over-Month (MoM) trends  
- Dynamic date range filtering  
- Cumulative sales logic  
- Custom measures for:
  - Sales vs Units comparison
  - Return impact analysis
  - Performance tracking over time  

These calculations help move beyond static charts into **decision-ready insights**.

---

## 🧠 Skills Demonstrated
- Power BI Data Modeling  
- DAX Measures & Time Intelligence  
- Interactive Navigation (Overview → Product → Product View)  
- Business-Focused KPI Design  
- UX/UI Dashboard Design (Amazon-inspired layout)  
- Drill-down & Cross-filtering  

---

## 🗂️ Data Source
This project uses an e-commerce style dataset containing:
- Orders
- Products
- Categories
- Locations
- Dates
- Sales, units, returns, and reviews  

🔗 **Data Source Link:**  
👉https://github.com/100rya-py/Amazon-Dashboard/blob/main/Amazon%20Sales%20Data.zip
