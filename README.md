# 🍽️ Swiggy Data Analytics Dashboard

An end-to-end Data Analytics project built using **Microsoft Fabric, SQL, and Power BI** to analyze Swiggy's business performance through interactive dashboards and KPI-driven insights.

---

## 📌 Project Overview

Swiggy is one of India's largest online food delivery platforms, generating massive amounts of operational data from customers, restaurants, orders, and deliveries.

This project demonstrates how raw business data can be transformed into meaningful insights using a modern analytics pipeline.

The solution follows an end-to-end analytics workflow beginning with raw data ingestion and ending with an interactive Power BI dashboard for business decision-makers.

---

## 🎯 Business Objective

The primary objective of this project is to:

- Store raw datasets in a Lakehouse
- Clean and validate data using SQL
- Model data using a Star Schema in a Data Warehouse
- Build a Power BI Semantic Model
- Create interactive dashboards
- Publish business-ready reports for stakeholders

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Fabric | Data Platform |
| Lakehouse | Raw Data Storage |
| SQL | Data Cleaning & Validation |
| Data Warehouse | Data Modeling |
| Power BI | Dashboard Development |
| DAX | KPI & Measure Creation |

---

# 📂 Project Architecture

```
                Raw CSV Files
                      │
                      ▼
               Microsoft Fabric
                  Lakehouse
                      │
                      ▼
             SQL Data Cleaning
                      │
                      ▼
            Data Warehouse
             (Star Schema)
                      │
                      ▼
          Power BI Semantic Model
                      │
                      ▼
         Interactive Power BI Dashboard
```

---

# 📁 Dataset

The project uses multiple datasets representing Swiggy operations:

- Customers
- Restaurants
- Orders
- Delivery Partners
- Deliveries

---

# ⭐ Data Modeling

A **Star Schema** has been implemented.

## Fact Table

- Fact Orders

## Dimension Tables

- Date
- Restaurant
- Dish
- Location

---

# 📊 Dashboard Overview

The dashboard provides an executive overview of Swiggy's business performance.

## KPI Cards

- Total Sales
- Average Order Value
- Total Orders
- Average Rating
- Rating Count

---

## Dashboard Visualizations

### 📈 Sales Trend

- Monthly Sales Trend

### 📅 Daily Performance

- Sales by Day of Week

### 🍕 Food Category Analysis

- Veg vs Non-Veg Sales Distribution

### 🍔 Restaurant Performance

Top 5 Restaurants based on Sales

### 🌍 State-wise Sales

Top Performing States

### 📆 Weekly Sales Analysis

Sales by Week Number

### 🎛 Interactive Filters

- City
- Food Type
- Quarter
- Restaurant

---

# 📌 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Sales | Overall Revenue |
| Total Orders | Number of Orders |
| Average Order Value | Revenue per Order |
| Average Rating | Customer Satisfaction |
| Rating Count | Total Ratings |

---

# 📈 Business Insights

The dashboard helps business users answer questions such as:

- Which cities generate the highest revenue?
- Which restaurants contribute the most sales?
- What is the monthly sales trend?
- Which food category performs better?
- Which states generate maximum revenue?
- How do sales vary throughout the week?
- What is the average order value?
- What are the customer rating trends?

---

# 🧮 Power BI Features Used

- Data Modeling
- Star Schema
- Relationships
- DAX Measures
- KPI Cards
- Line Charts
- Bar Charts
- Donut Chart
- Slicers
- Interactive Filtering


---

# 📷 Dashboard Preview

```
images/dashboard.png
```

Example:

```markdown
![Dashboard](https://github.com/s-balamurali/Swiggy-Data-Analysis-PowerBI-Visualization-Fabric/blob/main/Swiggy_Data_Analysis_DashBoard.png)
```

---



# 🚀 Project Workflow

1. Sample Data Collection
2. Data Ingestion into Lakehouse
3. SQL Data Cleaning
4. Data Validation
5. Star Schema Creation
6. Power BI Semantic Model
7. DAX Measure Development
8. Dashboard Design
9. Business Insight Generation

---

# 🎯 Business Value

This dashboard enables stakeholders to:

- Monitor business performance
- Identify top-performing restaurants
- Track revenue trends
- Analyze customer preferences
- Compare regional sales
- Support strategic decision-making using data-driven insights

---

