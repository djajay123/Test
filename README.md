# Uber Trip Analysis - Power Bi Dashboard

## Project Overview
The Uber Trip Analysis Dashboard was built in Power BI to uncover insights into trip bookings, revenue generation, trip distances, and customer demand patterns. This dashboard empowers stakeholders to make data-driven decisions to optimize ride operations, pricing strategies, and customer satisfaction.

![Image](https://github.com/user-attachments/assets/806c8d60-0d76-46f5-bb2e-c1ae2c57dad6)

## 🔍 Business Objectives

- Track and visualize key Uber trip metrics like **Total Bookings**, **Total Booking Value**, and **Trip Distance**  
- Identify **high-demand time periods** and **locations** for operational planning  
- Enhance data exploration using **interactive charts**, **slicers**, and **drill-through** functionality  
- Optimize pricing and resource allocation using **trend analysis** and **vehicle preference data**

## Tools Used
- Power BI Desktop
- DAX (Dynamic Measures, Drill-through setup, Dynamic Titles)
- GitHub for version control

## Key Features

### 📈 Dashboard 1: Overview Analysis

- **KPIs**: Total Bookings, Booking Value, Trip Distance, Avg Booking Value & Duration  
- **Charts**: Measure Selector with dynamic visual updates by:
  - Payment Type (Card, Cash, Wallet)  
  - Trip Type (Day/Night)  
- **Vehicle Type Analysis**: Grid View with conditional formatting  
- **Location Metrics**:  
  - Most Frequent Pickup & Drop-Off Points  
  - Farthest Trips  
  - Top 5 Booking Locations  
  - Preferred Vehicle per Location  
- **UX Enhancements**:  
  - Dynamic Chart Titles  
  - Slicers (Date, City)  
  - Tooltips for deeper metric insight  

---

### 🕒 Dashboard 2: Time Analysis

- **Dynamic Measure Filter** – Filters all charts via user-selected KPIs  
- **Visuals**:
  - Area Chart by Pickup Time (10-min intervals)  
  - Line Chart by Day Name  
  - Heatmap (Matrix) – Hour vs. Day demand pattern  

---

### 📋 Dashboard 3: Detailed Grid View

- **Drill-through Functionality**:  
  - View granular trip records from any visual  
- **Bookmark Toggle**:  
  - Switch between filtered view and full dataset  
