# 🛒 E-Commerce Sales Analysis (Olist Dataset) — Power BI

An end-to-end analysis of a Brazilian e-commerce marketplace (Olist-style dataset) covering orders, payments, deliveries and customer reviews — from raw, messy CSVs to a connected data model and business insights.

## 📌 Business Problem
The marketplace wants to understand **sales performance, delivery timeliness and customer satisfaction**: where revenue comes from, how payment behaviour varies, and what drives review scores.

## 🛠️ Tools & Tech
- **Power BI** (Power Query for cleaning, data modeling, DAX)
- Multi-table relational modeling across 9 source tables

## 📊 Key Analysis
- Revenue by **location** and **product category**
- **Weekday vs. weekend** payment/order patterns
- Order purchase → delivery timestamp analysis (delivery performance)
- **Customer review** scores vs. delivery experience

## 🗂️ Repository Structure
```
├── data/
│   ├── sample/                              # ~300-row samples of each source table
│   └── product_category_name_translation.csv
├── data_model/                              # Table relationship (joins) diagram
└── presentations/                           # Project overview deck
```
> **Note on data & dashboard:** the full raw dataset (millions of rows) and the final Power BI `.pbix` exceed GitHub's file-size limits, so this repo includes **representative samples**, the **data model diagram**, and documentation. The dataset is the public Olist Brazilian e-commerce dataset.

## 🧱 Data Model
See `data_model/data_model_joins.png` for how Orders, Customers, Payments, Order Items (Price), Products, Sellers, Reviews and Geolocation relate.

## 🔑 Key Skills Demonstrated
Data cleaning (Power Query) · Relational data modeling · DAX · Delivery & satisfaction analysis · Power BI

---
*Project completed as part of a guided data analytics bootcamp / internship.*
