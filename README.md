# Sales Analysis Based On Revenue, Customer Type and Rep performance
A comprehensive analysis of sales performance across regions, product categories, customer types, and sales channels to identify revenue drivers and business growth opportunities.

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

---

## 📊 Project Overview
This project analyzes sales data to understand business performance across **regions, product categories, customer types, sales channels, and sales representatives**.

The goal of this analysis is to identify key revenue drivers, customer behavior patterns, and opportunities for improving business performance.

The primary objectives were:

- To analyze **overall sales and revenue performance**
- To identify **top-performing regions and product categories**
- To evaluate **sales representative performance**
- To compare **new vs returning customer revenue**
- To analyze **online vs retail sales channels**
- To understand the **impact of discounts on revenue**

An **interactive Power BI dashboard** was created to present insights using multiple visuals and filters for better decision-making.

---

## 🗂️ Data Source
- **Source:** Sample Sales Dataset
- **Format:** .csv / Excel
- **Dataset Size:** ~1000 records

### Key Variables
- Order ID
- Order Date
- Region
- Product Category
- Quantity
- Revenue
- Discount
- Sales Channel
- Payment Method
- Customer Type
- Sales Representative

The dataset contains transactional sales data used to analyze revenue trends and customer purchasing behavior.

---

## 🛠️ Tools & Technologies
- **Visualization Tool:** Power BI Desktop  
- **Data Preparation:** Microsoft Excel  
- **Data Transformation:** Power Query  
- **Data Modeling:** Star Schema Approach  
- **DAX Measures:** Custom calculations for KPIs  
- **Interactive Features:** Slicers, Filters, Drill-down, Forecasting

---

## 🧹 Data Cleaning & Preparation
The following steps were performed before analysis:

1. Removed duplicate and unnecessary columns.
2. Checked and corrected **data types** (date, numeric values).
3. Handled **missing or inconsistent values**.
4. Standardized category names and region values.
5. Created calculated measures in Power BI:
   - Total Revenue
   - Total Orders
   - Total Quantity Sold
   - Average Discount
6. Verified relationships between fields for proper analysis.

These steps ensured **clean, consistent, and analysis-ready data**.

---

## 🔍 Exploratory Data Analysis (EDA)

The following business questions were explored:

- Which **region generates the highest revenue**?
- Which **product category performs best**?
- How does **revenue vary month by month**?
- Which **sales representatives contribute the most revenue**?
- What is the **difference between new and returning customer sales**?
- Which **sales channel (Online vs Retail) generates more revenue**?
- Do **discounts significantly affect revenue**?

### Visualizations Created
- KPI Cards (Revenue, Orders, Quantity, Avg Discount)
- Monthly Sales Trend (Line Chart)
- Revenue by Region (Bar Chart)
- Revenue by Product Category (Bar Chart)
- Revenue by Payment Method (Donut Chart)
- Revenue by Sales Representative (Bar Chart)
- Revenue by Customer Type (Donut Chart)
- Revenue by Sales Channel (Stacked Bar Chart)
- Revenue Forecast (Time Series)

---

## 💡 Key Insights
- The business generated **$59.64M total revenue** from **997 orders**.
- **North region** contributes the highest revenue, while **South region** contributes the least.
- **Clothing** is the top-performing product category.
- **Food category** generates the lowest revenue among all categories.
- **Online sales channel slightly outperforms retail sales**.
- **New customers generate slightly more revenue than returning customers**.
- **Payment methods are evenly distributed** across bank transfer, credit card, and cash.
- **Discount levels show minimal impact on overall revenue generation**.

---

## 🚀 Recommendations
- Focus marketing strategies on improving sales in the **South region**.
- Promote **Food category products** to increase category performance.
- Strengthen **customer retention strategies** to increase repeat purchases.
- Invest further in **online sales channels** due to strong digital performance.
- Provide **performance improvement strategies or training for lower-performing sales representatives**.

---

## ⚙️ How to Use

To explore this project:

1. Download the **.pbix file** from this repository.
2. Open the file using **Power BI Desktop**.
3. Use available **filters/slicers** to analyze data by:
   - Region
   - Month
4. Hover over visuals to view detailed metrics.
5. Explore monthly trends and forecasts using the **time-series chart**.

No additional dependencies are required beyond **Power BI Desktop**.
