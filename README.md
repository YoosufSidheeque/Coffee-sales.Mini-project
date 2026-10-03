# ☕ Coffee Sales Dashboard

## Overview

This project is an interactive Power BI dashboard created to analyze coffee shop sales data.

The dashboard provides an overview of sales performance and helps identify patterns based on coffee type, date, time of day, weekday, and transaction activity.

## 🛠 Tools Used

- Microsoft Excel
- Power Query
- Power BI
- DAX

## 📊 Dashboard

The report contains two pages:

### Sales Overview
- Total Revenue
- Total Transactions
- Average Transaction Value
- Coffee Types
- Monthly Revenue Trend
- Revenue by Coffee Type
- Revenue by Time of Day

### Sales Analysis
- Transactions by Hour
- Revenue by Weekday
- Transactions by Payment Method
- Coffee Sales by Time of Day heatmap

The dashboard also includes interactive slicers for Date, Coffee Type, Payment Method, and Time of Day.

## 🔍 Key Insights

- Latte generated the highest overall revenue.
- Americano with Milk recorded a high number of transactions.
- Afternoon and night periods generated strong sales.
- 10 AM was one of the busiest hours based on transaction volume.
- Sales performance varies across weekdays and coffee types.

## 🧹 Data Preparation

The dataset was cleaned and transformed before visualization.

Main steps included:

- Checking and correcting data types
- Checking for missing values
- Creating Month-Year fields
- Sorting weekdays and months correctly
- Creating time-based categories
- Creating DAX measures for KPIs

## ⚠️ Note About Payment Data

The original dataset did not contain meaningful variation in payment methods.

Cash, Card, and UPI values were simulated for learning purposes to practice payment-method analysis, slicers, and Power BI visualizations.

Therefore, payment-method results should not be considered actual customer behaviour.

## 📁 Project Files

- `Coffee_Sales_Dashboard.pbix` - Power BI dashboard
- Cleaned coffee sales dataset
- Dashboard screenshots

## 🎯 Project Purpose

This project was created as part of my data analytics learning journey to practice the complete workflow:

**Data Cleaning → Data Transformation → DAX → Data Analysis → Visualization → Interactive Dashboard**

---

Thanks for checking out my project!
