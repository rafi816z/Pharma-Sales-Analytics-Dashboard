# 💊 Pharma Sales Analytics Dashboard (Power BI + SQL + Python)

## 🧩 Business Problem

Pharmaceutical companies operate in a highly competitive and regulated environment where **sales performance varies significantly across regions, products, channels, and sales teams**. Despite having access to large volumes of transactional data, leadership often lacks a **centralized, analytics-driven view** to understand revenue concentration, growth drivers, seasonality, and performance risks.

Sales reporting is typically static and backward-looking, making it difficult to identify **which markets, products, and teams truly drive growth** and where the business is overly dependent on a few contributors.

This project addresses these challenges by building an **end-to-end pharma sales analytics solution** using SQL, Python, and Power BI to deliver **actionable, visual-driven insights** for strategic sales planning and decision-making.

---

## 🎯 Business Objective

The objective of this project is to:
- Provide a **360° view of pharma sales performance**  
- Identify **top-contributing products, cities, and sales teams**  
- Analyze **month-over-month growth and seasonality patterns**  
- Highlight **revenue concentration and scalability risks**  
- Enable **forecast-driven planning and proactive decision-making**  

This allows stakeholders to move from descriptive reporting to **diagnostic and forward-looking sales analytics**.

---

## ⭐ Project Overview

This project delivers an **interactive Power BI dashboard** built on a star-schema data model and advanced DAX measures, analyzing **250K+ pharma sales transactions** across multiple years.

The dashboard provides:
- Executive sales performance monitoring  
- Product and pricing insights  
- Sales growth and forecasting analysis  
- Regional and channel-level performance  
- Sales team and representative contribution analysis  

---

## 📂 Dataset

- **Source:** [Github – pharma-data](https://github.com/sssingh/pharmaceutical-sales-analysis-powerbi?tab=readme-ov-file#dataset)    
- **Transactions:** 250,000+ sales records  
- **Time Range:** Multi-year monthly data  
- **Geographies:** Germany, Poland (multiple cities)  

**Key Dimensions:**
- Product Class  
- Channel & Sub-channel  
- Distributor  
- Sales Team  
- Sales Representative  

**Data Modeling:**
- Fact Table: Sales Transactions  
- Dimension Tables: Date, Product, Country, City, Channel, Distributor, Sales Team, Sales Representative  
- Optimized for time intelligence and scalable DAX calculations  

---

## 🔧 Tech Stack

- **Data Processing & Analysis:** Python, MySQL  
- **Dashboard & Visualization:** Power BI  
- **Analytics:** Advanced DAX  
- **Forecasting:** Power BI time-series forecasting  

---

## 📊 Dashboard Breakdown

### 🟦 Page 1 — Executive Sales Performance Dashboard

**Key Metrics:**
- Total Sales: $12.09B  
- Total Units Sold: 29.39M  
- Total Transactions: 254K  
- Active Products: 240  

**Visual Highlights:**
- **Top 10 Cities by Revenue (Map):** Revenue heavily concentrated in a few German cities  
- **Revenue Contribution by Product Class (Bar Chart):** Analgesics and Antiseptics dominate total sales  
- **Sales Trend Over Time (Line Chart):** Clear seasonality with mid-year peaks and early-year dips  
- **Global Slicers (Year, Country, Channel, Product Class):** Enable fast executive drilldowns  

---

### 🟦 Page 2 — Product & Pricing Performance Analysis

**Visual Highlights:**

- **Sales Share by Product Class (Treemap):** Analgesics and Mood Stabilizers account for the largest share of total revenue  
- **Top 10 Selling Products by Revenue (Bar Chart):** Ioclontide and Tetratanyl are the highest revenue-generating products  
- **Detailed Product-Level Sales Table:** Shows revenue, units sold, average price, and MoM growth for granular product analysis  
- **Price, Volume, and Revenue Relationship by Product Class (Bubble Chart):** Analgesics combine high volume and strong pricing, while Antimalarials remain volume- and price-constrained  

---

### 🟦 Page 3 — Sales Growth & Forecast Insights

**Visual Highlights:**

- **Avg. MoM Growth KPI:** Overall average month-over-month growth of 2.70%  
- **Highest Sales Month Card:** August records the highest sales at $1,227.11M  
- **Lowest Sales Month Card:** January records the lowest sales at $685.02M  
- **Sales Trend Comparison Across Drug Names (Small Multiples Line Charts):** Reveals varying growth stability across individual products  
- **Month-on-Month Sales Growth Breakdown (Waterfall Chart):** Highlights periods of sharp growth and contraction across months  
- **Historical Sales Trend with Forecast Projection (Line + Forecast):** Shows stable future sales with increasing uncertainty over time   

---

### 🟦 Page 4 — Regional & Channel Performance

**Visual Highlights:**
- **Sales by Channel (Bar Chart):** Hospital channel dominates overall revenue  
- **City-Level Revenue Distribution (Map/Bar):** Butzbach alone contributes nearly $100M  
- **Regional Sales Comparison (Country/City View):** Average city sales hide extreme regional concentration  

---

### 🟦 Page 5 — Sales Team & Representative Performance

**Visual Highlights:**
- **Sales Contribution by Team (Bar Chart):** Team *Delta* contributes ~30.8% of total revenue  
- **Sales Contribution by Representative (Ranked Bar Chart):** 13 sales reps generate the entire $12.09B  
- **Deal Size vs Deal Volume (Scatter Plot):** Teams succeed via large deals or high deal velocity  

---

## 💼 Business Impact

- **Improved Sales Visibility:** Unified view across products, regions, channels, and teams  
- **Risk Identification:** Clear exposure of geographic, product, city, and personnel concentration risks  
- **Growth Enablement:** Forecast-driven planning aligned with seasonal demand patterns  
- **Performance Optimization:** Identification of best-performing products and sales teams  

---

## 🔍 Overall Insights

- **Sales are heavily concentrated in Germany**, creating strong market dominance but high geographic risk.  
- **A small subset of products and cities drives the majority of revenue**, following a clear Pareto distribution.  
- **Seasonality plays a significant role**, with mid-year peaks and early-year slowdowns.  
- **Top sales teams and representatives contribute disproportionately**, indicating key-person dependency.  
- **Forecasting shows stable but non-linear growth**, reinforcing the need for scenario-based planning.  
