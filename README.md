# Adidas Sales Analysis Dashboard
## 📊 Project Overview

This project is an **Adidas Sales Analysis Dashboard** built using **Microsoft Power BI**. It transforms sales data into an interactive dashboard that provides insights into sales performance across **time, product categories, and locations**.

The dashboard uses KPIs and interactive visualizations to help analyze revenue, discounts, quantity sold, and sales distribution across different cities and product categories.

## 🎯 Objectives

* Analyze overall Adidas sales performance.
* Monitor **Net Sales** and **Gross Sales**.
* Track **Discount Values** and **Quantity Sold**.
* Analyze sales trends over time.
* Compare sales performance across cities.
* Analyze sales across different product categories.
* Provide interactive filtering for deeper analysis.

## 📈 Dashboard Features

### Key Performance Indicators

The dashboard provides four main KPIs:

* **Net Sales**
* **Gross Sales**
* **Discount Values**
* **Quantity Sold**

### 📅 Sales Trend Analysis

A time-series visualization shows **Net Sales by Month**, allowing users to identify changes and trends in sales performance over time.

### 🌍 Geographic Analysis

A map visualization displays **Net Sales by City**, providing a geographic view of sales distribution.

### 🛍️ Product Category Analysis

A funnel chart analyzes **Net Sales by Product Category**, allowing comparison between different categories.

### 🏙️ City Performance Analysis

A ribbon chart combines **City, Year, and Net Sales** to analyze how city-level sales performance changes over time.

### 🔎 Interactive Filters

Users can interact with the dashboard using:

* **Date / Year**
* **Product Category**

These filters dynamically update the dashboard visualizations.

## 🗂️ Data Model

The Power BI data model consists of three main tables:

| Table      | Description                                                         |
| ---------- | ------------------------------------------------------------------- |
| `SalesT`   | Main sales/fact table containing sales and transaction-related data |
| `Product`  | Contains product and category information                           |
| `Location` | Contains geographic information such as city                        |

The tables are used together to analyze sales performance across **time, products, categories, and locations**.

## 📐 Main Measures

The dashboard uses DAX measures including:

* `Net_Sales`
* `Gross_Sales`
* `Discount_values`
* `Quantity_`

## 📊 Main Analysis Dimensions

The dashboard analyzes sales across:

* **Date**
* **Year**
* **Month**
* **Product Category**
* **City**

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power BI Data Modeling**
* Data Visualization
* KPI Development
* Time-Series Analysis
* Geographic Analysis
* Business Intelligence
* Sales Analytics

## 📋 Dashboard Structure

```text
Adidas Sales Dashboard
│
├── KPI Cards
│   ├── Net Sales
│   ├── Gross Sales
│   ├── Discount Values
│   └── Quantity Sold
│
├── Geographic Analysis
│   └── Net Sales by City
│
├── Time Analysis
│   └── Net Sales by Month
│
├── Category Analysis
│   └── Net Sales by Category
│
├── City Performance
│   └── Net Sales by City and Year
│
└── Interactive Filters
    ├── Date / Year
    └── Product Category
```

## 🔍 Business Questions

This dashboard can be used to answer questions such as:

1. What is the overall Net Sales performance?
2. What are the Gross Sales and Discount Values?
3. How many products were sold?
4. How does Net Sales change over time?
5. How is sales performance distributed across cities?
6. How does sales performance vary between product categories?
7. How does city-level performance change across different years?
8. How do different categories contribute to overall sales?

## 💡 Key Skills Demonstrated

* Data Analysis
* Business Intelligence
* Power BI Dashboard Development
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Sales Analytics
* Time-Series Analysis
* Geographic Data Analysis
* Business Performance Analysis

## 👤 Author

**Omar Nouh**

Data Analyst / Junior Data Scientist

---

⭐ If you find this project useful, feel free to explore the dashboard and its data model.
