# ☕ Coffee Shop Sales Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Retail%20%26%20FMCG-FF6B35?style=for-the-badge)

---

## 📌 Project Overview

A **sales performance dashboard** built in Power BI and Excel to evaluate coffee shop performance across multiple locations using **time, date, and location dimensions**.

**Business Question:** *Which locations, time periods, and products are driving the most revenue — and where are we losing sales?*

---

## 🎯 Problem Statement

A multi-location coffee shop chain needs to:
- Track **daily, weekly, and monthly** revenue trends
- Compare **store-level performance** across locations
- Identify **peak hours** and high-demand products
- Spot **underperforming outlets** for improvement

---

## 📊 Dataset Features

| Dimension | Description |
|---|---|
| Date Dimension | Day, Week, Month, Quarter, Year |
| Time Dimension | Hour-level breakdown of transactions |
| Location | Coffee shop branch / outlet |
| Product | Item sold (coffee, tea, pastries, etc.) |
| Sales | Revenue per transaction |
| Quantity | Units sold per item |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, formatting, pivot tables |
| Power BI | Interactive dashboard & DAX measures |
| DAX | Custom KPI calculations |

---

## 🔍 Workflow

### 1️⃣ Data Preparation (Excel)
- Cleaned raw transaction data
- Built date and time dimension tables
- Removed duplicates and standardized location names

### 2️⃣ Data Modelling (Power BI)
- Created star schema: Fact Sales + Date Dim + Time Dim + Location Dim
- Established relationships between tables
- Built DAX measures for KPIs

### 3️⃣ Dashboard Design (Power BI)
- Revenue trend line chart (daily/weekly/monthly toggle)
- Location performance heatmap
- Peak hours bar chart
- Product category breakdown

---

## 📈 Key Insights

✔ **Morning hours (7–10 AM)** drive 60%+ of total daily revenue  
✔ **Downtown locations** consistently outperform suburban outlets  
✔ **Weekends show 25% higher** footfall vs weekdays  
✔ **Coffee (hot)** is the highest revenue product category  
✔ Two branches show declining MoM revenue — potential for targeted campaigns  

---

## 💡 Business Impact

- Enables **data-driven staffing decisions** (peak hour planning)
- Identifies **locations needing operational improvements**
- Helps marketing teams run **targeted promotions** during low-traffic periods
- Supports **inventory management** based on product demand trends

---

## 🚀 Future Improvements

- [ ] Add customer satisfaction scores
- [ ] Build forecasting model for revenue prediction
- [ ] Integrate weather data (rain impact on footfall)
- [ ] Deploy as live Power BI Service dashboard

---

## 👨‍💻 Author

**Rohit Gupta**
📍 Mumbai, India | 🎓 BCA @ Amity University
🔗 [LinkedIn](https://linkedin.com/in/rohit-gupta-o7) | [GitHub](https://github.com/Rohit-Gupta-07)

---

⭐ *Found this useful? Give it a star!*
