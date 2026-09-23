# Sales-Data-Analysis
Power BI Sales Data Analysis project by Anju Das M. — data cleaning, DAX, interactive dashboards, profitability analysis, and actionable business insights.
# 📊 Sales Data Analysis | Power BI




\

## 📌 Project Overview

This project analyzes **1,000+ sales transactions** using **Power Query and Microsoft Power BI** to understand sales performance, product performance, profitability, regional contribution, and sales target achievement.

The project follows an end-to-end analytics workflow:

**Raw CSV Data → Data Cleaning → Data Transformation → DAX Measures → Interactive Dashboard → Business Insights & Recommendations**

The primary objective is to transform raw sales data into an interactive business intelligence dashboard that helps identify **sales trends, profitable products, regional performance, and opportunities for improvement**.

---

## 🎯 Business Objectives

The analysis focuses on answering key business questions:

* What is the overall sales and profit performance?
* Which products generate the highest sales and profit?
* Which regions contribute the most to profit?
* How is profit changing over time?
* Which categories contribute to overall profitability?
* How much quantity is being sold across products?
* How does actual sales performance compare with the sales target?
* What actionable recommendations can be derived from the analysis?

---

## 📂 Dataset

The dataset contains **1,000+ rows** in CSV format.

### Key Fields

| Field         | Description                           |
| ------------- | ------------------------------------- |
| Order ID      | Unique identifier for each order      |
| Order Date    | Date on which the order was placed    |
| Customer Name | Customer information                  |
| Region        | Geographical sales region             |
| Product       | Product purchased                     |
| Category      | Product category                      |
| Quantity      | Quantity sold                         |
| Unit Price    | Price per unit                        |
| Sales         | Revenue generated                     |
| Profit        | Profit generated from the transaction |

---

# 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query** before loading the data into Power BI.

### Cleaning Steps

* Removed duplicate records.
* Handled missing **Customer Name** values.
* Handled missing **Region** values.
* Replaced missing **Unit Price** values with `"Unknown"` where applicable.
* Handled missing **Order Date** values using the **Fill Up** method.
* Converted Order Date into the appropriate **Date** data type.
* Created a cleaned **Sales** column.
* Created a cleaned **Profit** column.
* Replaced null values in Sales and Profit using calculated values where applicable.
* Replaced invalid/null values where required.
* Corrected relevant column data types.
* Applied appropriate formatting to cleaned Sales and Profit fields.
* Loaded the transformed dataset into Power BI.

### Data Preparation Workflow

```text
Raw CSV Dataset
       ↓
Power Query
       ↓
Remove Duplicates
       ↓
Handle Missing Values
       ↓
Correct Data Types
       ↓
Create Cleaned Sales & Profit
       ↓
Validate Data
       ↓
Load into Power BI
```

---

# 📐 DAX Measures

A dedicated **Measures Table** was created to organize the analytical calculations.

### Key Measures

* **Total Sales**
* **Total Profit**
* **Target Sales**
* **Average Unit Price**
* **Profit Margin %**

These measures were used across the dashboard to provide dynamic KPIs and support interactive analysis.

---

# 📊 Power BI Dashboard

The report contains **four analytical pages**, designed to move from overall performance to detailed product/profit analysis and finally to business recommendations.

---

## 1️⃣ Sales Overview

The Sales Overview page provides a high-level view of business performance.

### KPIs

* Total Sales
* Total Customers
* Total Cost
* Total Profit

### Visuals & Filters

* Region slicer
* Product slicer
* Order Distribution chart
* Top 5 Products column chart

### Purpose

This page provides an executive-level summary of sales performance and allows users to explore the results by **region and product**.

---

## 2️⃣ Product Analysis

The Product Analysis page focuses on understanding product-level performance.

### KPIs

* Total Products

### Analysis

* Sales by Product
* Profit by Product
* Top 5 Products
* Quantity Sold by Product

### Interactive Elements

* Product slicer
* Product-level visual analysis

### Purpose

This page helps identify products contributing to sales, profit, and quantity sold.

---

## 3️⃣ Profit Analysis

The Profit Analysis page focuses specifically on profitability.

### Analysis

* Profit over Year
* Profit by Product
* Profit by Region
* Profit by Category

### Interactive Elements

* Profit-related slicer
* Region slicer

### KPI / Performance Visual

* Sales Target Gauge

### Purpose

This page helps understand **where profit is generated, how profitability changes over time, and how different products, regions, and categories contribute to profit**.

---

# 💡 4️⃣ Insights & Recommendations

The final page converts the dashboard findings into actionable business insights.

### Key Insight Areas

#### 📦 Product Performance

Product-level sales and profit analysis helps identify products that contribute strongly to overall business performance and products that may require further optimization.

#### 🌍 Regional Performance

Regional profit analysis provides visibility into differences in profitability across geographical markets.

---

## 🚀 Business Recommendations

### 1. Improve Profitability

Monitor products with lower profit contribution and review their pricing, cost structure, and sales performance to identify opportunities for improving margins.

### 2. Strengthen Regional Sales

Analyze regional performance to identify high-performing markets and investigate opportunities to improve sales and profitability in weaker regions.

### 3. Optimize Product Performance

Use product-level sales, profit, and quantity analysis to focus resources on products with stronger business contribution while reviewing underperforming products.

---

# 📈 Key Dashboard Metrics

| KPI                | Purpose                                   |
| ------------------ | ----------------------------------------- |
| Total Sales        | Measures overall revenue generated        |
| Total Profit       | Measures overall profitability            |
| Profit Margin %    | Evaluates profitability relative to sales |
| Total Customers    | Measures customer reach                   |
| Total Quantity     | Measures sales volume                     |
| Average Unit Price | Tracks average product pricing            |
| Target Sales       | Enables target performance comparison     |

---

# 🛠️ Tools & Technologies

| Tool                 | Usage                                   |
| -------------------- | --------------------------------------- |
| **Microsoft Excel**  | Data inspection and preparation         |
| **Power Query**      | Data cleaning and transformation        |
| **Power BI Desktop** | Dashboard development and visualization |
| **DAX**              | KPI and business measure calculations   |
| **GitHub**           | Project documentation and portfolio     |

---

# 🔍 Skills Demonstrated

### Data Preparation

* Data cleaning
* Missing-value handling
* Duplicate removal
* Data type transformation
* Data validation
* Feature/column creation

### Power BI

* KPI cards
* Slicers
* Column charts
* Bar charts
* Line charts
* Donut charts
* Pie charts
* Gauge charts
* Interactive dashboard design

### DAX

* Measure creation
* Aggregations
* Profit calculations
* Profit margin calculation
* Target calculations

### Business Analytics

* Sales performance analysis
* Product performance analysis
* Regional analysis
* Profitability analysis
* Target performance analysis
* Insight generation
* Actionable recommendations

---

---

# 📁 Project Structure

```text
Sales-Data-Analysis/
│
├── Dataset/
│   └── sales_data.csv
│
├── PowerBI/
│   └── Sales_Data_Analysis.pbix
│
├── Screenshots/
│   ├── sales-overview.png
│   ├── product-analysis.png
│   ├── profit-analysis.png
│   └── insights-recommendations.png
│
└── README.md
```

---

# 🎯 Project Outcome

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw transactional data and progressing through data cleaning, transformation, analytical calculations, visualization, and business recommendations.

The final Power BI report provides an interactive view of **sales, customers, products, quantity, profitability, regional performance, and target achievement**, allowing business users to explore performance and identify areas for improvement.

---

## 👩‍💻 Skills Highlighted for Recruiters

**Power BI | Power Query | DAX | Data Cleaning | Data Transformation | Data Visualization | Business Intelligence | Sales Analytics | Profitability Analysis | KPI Development | Business Insights**

---

### ⭐ Portfolio Project

**Sales Data Analysis Dashboard**

*An end-to-end Power BI project demonstrating the ability to transform raw sales data into meaningful business insights and actionable recommendations.*
