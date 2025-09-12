# E-Commerce-Sales-Returns

# Project Overview

This project analyzes **E-Commerce sales data** to uncover key insights around revenue, customers, products, and returns.
The dashboard was built using **Google Colab, Power BI, Tableau, and Excel **.

The goal is not just to create dashboards, but to **drive business outcomes**, such as:

* Identifying **top revenue-generating products and customers**
* Detecting **revenue leakage from product returns**
* Understanding **geographic sales distribution**
* Reducing **reporting turnaround time** with automated pipelines

---

## 📊 Dataset

Sample dataset structure:

| InvoiceNo | StockCode | Description                        | Quantity | InvoiceDate      | UnitPrice | CustomerID | Country        |
| --------- | --------- | ---------------------------------- | -------- | ---------------- | --------- | ---------- | -------------- |
| 536365    | 85123A    | WHITE HANGING HEART T-LIGHT HOLDER | 6        | 2010-12-01 08:26 | 2.55      | 17850      | United Kingdom |
| 536365    | 71053     | WHITE METAL LANTERN                | 6        | 2010-12-01 08:26 | 3.39      | 17850      | United Kingdom |

---

## ⚙️ Tools & Technologies

* **Google Colab (Python, Pandas, Matplotlib)** → Data cleaning & preprocessing
* **Power BI** → Interactive dashboard & KPI analysis
* **Tableau** → Data visualization (alternative view)
* **Excel** → Initial data exploration

---

##  Data Cleaning (Google Colab)

* Removed missing `CustomerID` values
* Corrected date formats (`InvoiceDate`)
* Filtered out invalid transactions (e.g., negative quantities)
* Separated **Returns dataset** for analysis

---

## 📈 Dashboard Features

### 🔹 KPI Cards

* 💰 **Total Revenue**
* 🛒 **Total Orders**
* 👥 **Total Customers**
* 📊 **Average Order Value**

### 🔹 Visuals

* 📈 **Monthly Revenue Trend**
* 🏆 **Top 10 Products by Revenue**
* ⭐ **Top 10 Customers**
* 🌍 **Revenue by Country** (Map)
* 🔴 **Top 10 Returned Products**

### 🔹 Filters (Slicers)

* 📅 Date (Year/Month/Quarter)
* 🌍 Country
* 👥 Customer
* 📦 Product

---

## Business Impact

This dashboard helps leadership:

* Identify **revenue leakages** from product returns
* Optimize **customer targeting** with top customers analysis
* Track **geographic performance** for expansion strategies
* Shorten reporting time from **days → minutes**

---


## Dashboard Preview

<img width="1355" height="748" alt="E-Commerce Sales   Returns" src="https://github.com/user-attachments/assets/4da76f32-b742-470c-ac42-25b9432bc416" />

