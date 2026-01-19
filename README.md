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

### 🟦 Page 4 — Regional & Channel Performance Analysis

**Visual Highlights:**

- **Country-Level Sales Performance (Map):** Germany dominates regional sales, significantly outperforming Poland across all selected periods  
- **Avg Sales per City KPI:** Average city-level sales stand at **$16.14M**, indicating strong geographic concentration  
- **Top Performing City Card:** Butzbach emerges as the highest revenue-generating city with **$96.37M** in sales  
- **Top Performing Country Card:** Germany leads overall sales with **$11,410.70M**, contributing the majority share  
- **Sales by Country and Channel (Stacked Bar Chart):** Pharmacy channel drives higher revenue than Hospital channel, particularly in Germany  
- **City-Level Sales by Channel (Matrix Table):** Provides granular visibility into Hospital vs Pharmacy performance at the city level  
- **Sales by Channel and Sub-Channel (Stacked Bar Chart):** Retail and Private sub-channels contribute the largest share, while Government and Institutional channels show moderate penetration  

---

### 🟦 Page 5 — Sales Team & Representative Performance

**Visual Highlights:**

- **Active Sales Representatives KPI:** 13 active sales representatives contributing to total revenue  
- **Highest Contributing Sales Rep Card:** Jimmy Grey leads individual contribution with **8.30%** of total sales  
- **Top Contributing Sales Team Card:** Delta team contributes the highest share at **30.78%**  
- **Revenue Contribution by Sales Representative (Bar Chart):** Highlights revenue distribution and identifies top and mid-tier performers  
- **Deal Size vs Contribution by Sales Team (Bubble Chart):** Delta team combines high contribution with strong average deal size, while Alfa operates at lower deal values  
- **Sales Representative Performance Summary (Matrix Table):** Consolidated view of sales, units sold, contribution percentage, and average deal size by manager  
- **Sales Growth Patterns of Top 4 Representatives (Small Multiples Line Charts):** Displays long-term sales consistency, volatility, and growth trends for top-performing representatives  

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
