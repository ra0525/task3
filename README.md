# 🧩 Sales Financial Dashboard (Tableau Project)

This project presents a **Sales Financial Dashboard** built using **Tableau**, designed to provide business stakeholders with clear, interactive insights into company performance using real-world sales data.

## 📊 Objective

To design a visually compelling and interactive dashboard that:
- Tracks key performance indicators (KPIs)
- Supports data-driven decision-making
- Identifies trends across regions, time, and product lines

## 🛠️ Tools & Technologies
- Tableau (Dashboarding and Visual Analytics)
- Microsoft Excel / CSV (Data Source)
- PowerPoint (Summary Presentation)
- GitHub (Version Control)

---

## 📁 Dataset

The dataset used is `sales_data_sample.csv` and includes:
- Order Date
- Sales Amount
- Product Line
- Customer Details
- Region/Country
- Order Quantity

---

## 📌 Key KPIs & Metrics

| Metric              | Description |
|---------------------|-------------|
| **Total Sales**     | Sum of `SALES` |
| **Order Date**    | Month/Year of `ORDERDATE` |
| **Order Count**     | Count of unique `ORDERNUMBER` |
| **Average Order Value** | `SUM(SALES) / COUNTD(ORDERNUMBER)` |

---

## 📈 Dashboard Features

- ✅ **KPI Cards**: Total Sales, Order Count, Order Date, Average Order Value, Country, ProductLine
- ✅ **Sales Over Time**: Line chart for trend analysis
- ✅ **Sales by Product Line**: Identify top performing categories
- ✅ **Sales by Region**: Bar chart visualization
- ✅ **Order Status Distribution**: Pie chart visualization of distinct count of Ordernumber based on their status
- ✅ **Deal Size Contribution**: Identify sales based on deal size
- ✅ **Interactive Filters**: Region, Product Line, Year
- ✅ **Consistent Color Theme** for professional look

---

## 📷 Dashboard Preview

> Sales Dashboard
<img width="2500" height="3800" alt="Sales Financial Dashboard" src="https://github.com/user-attachments/assets/917a2b78-31d9-4244-8518-b3cda5304947" />

---

## 🧮 How to Reproduce

1. Open Tableau
2. Connect to the dataset: `sales_data_sample.csv`
3. Create calculated fields:
   - `Average Order Value`: `SUM([SALES]) / COUNTD([ORDERNUMBER])`
4. Build sheets for each insight (KPI, Region, Time, etc.)
5. Combine all sheets into a **Dashboard**
6. Add filters, legends, and formatting

---

## 📄 Project Outcome

- Built a professional, interactive dashboard
- Derived actionable insights for Sales and Profit
- Demonstrated time-series analysis and regional breakdown
- Delivered a PowerPoint summary for stakeholders
