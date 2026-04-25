# 🍔 Swiggy Sales & Performance Analysis

## 📌 Introduction
Welcome to the **Swiggy Sales & Performance Analysis** repository! This project explores a comprehensive dataset of Swiggy food delivery orders across multiple states and cities in India (recorded during 2025). The data provides a granular look into customer ordering behaviors, restaurant performance, geographic demand, and pricing trends. 

By analyzing various metrics such as order dates, food categories, pricing, and customer ratings, this repository serves as an end-to-end demonstration of Exploratory Data Analysis (EDA) and business intelligence reporting for the food delivery industry.

## 🗂️ Dataset Overview
The primary dataset (`Swiggy Data.csv`) contains over **197,000 records** at the dish/order level. 

**Key Features (Columns) include:**
* **Geographic Data:** `State`, `City`, `Location`
* **Time-Series Data:** `Order Date`, `Day`, `Quarter`, `Week`
* **Vendor & Item Data:** `Restaurant Name`, `Category`, `Dish Name`, `Food Type` (e.g., Veg/Non-Veg)
* **Metrics:** `Price (INR)`, `Rating`, `Rating Count`

## 📊 Key Analysis Points & Insights
Based on the aggregated analysis (`Analysis.csv`), here are the high-level Key Performance Indicators (KPIs) and initial findings:

### 1. Overall Business KPIs
* **Total Revenue (Sales):** ₹53,012,505 (~ ₹5.3 Crores)
* **Total Items/Orders Analyzed:** 197,430
* **Average Item Rating:** 4.34 ⭐ 
* **Total Rating Count:** 5,591,574 (Indicating high user engagement)
* **Average Item Value:** ₹268.51

### 2. Time-Series & Trend Analysis
Sales maintain a relatively stable and strong volume across the months analyzed, showing consistent consumer reliance on the platform:
* **Peak Months:** January (₹6.82M) and August (₹6.79M) generated the highest revenue.
* **Stable Demand:** Even the lowest performing month (February at ₹6.26M) maintained a very narrow gap compared to the peak months, indicating that food delivery demand is practically entirely non-seasonal or well-sustained in these regions.

### 3. Geographic & Vendor Opportunities (Areas for Deep Dive)
* **Top Performing Cities:** Bengaluru and Lucknow are among the cities driving high transaction volumes. (Bengaluru alone accounted for ~₹5.45M in a subset breakdown).
* **Category Performance:** By analyzing the `Category` and `Food Type` columns, we can identify whether Snacks, Main Courses, Veg, or Non-Veg items drive the highest basket value.

## 🎯 Project Objectives
If you are exploring this repository, the main objectives of the code and dashboards herein are to:
1. **Uncover Customer Preferences:** Identify the most popular dish categories and highest-rated restaurants.
2. **Geographical Mapping:** Understand which cities and micro-locations have the highest order density and revenue generation.
3. **Price vs. Rating Correlation:** Determine if higher-priced items yield better or worse customer satisfaction.
4. **Day-of-Week Trends:** Analyze whether weekends significantly out-perform weekdays in order volume.

