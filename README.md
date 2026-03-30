# ☕ Maven Coffee Shop Analysis (Excel Project)
Interactive Excel dashboard for analyzing coffee shop sales performance, customer behavior, and operational patterns.

# 📌 Overview
This project focuses on analyzing coffee shop sales data using Microsoft Excel. The goal is to transform raw transactional data into a clear and interactive dashboard that highlights key business metrics.

**The analysis compares performance across:**
- Product categories
- Store locations
- Days of the week
- Hours of operation

The dashboard supports better decision-making in sales strategy, marketing, inventory planning, and staffing.

# 📂 Data Source
- **Source:** Kaggle – Coffee Shop Dataset
- **Structure:** Single table dataset
  
**Key Fields:**
- Transaction ID
- Transaction Date & Time
- Quantity Sold
- Unit Price
- Revenue
- Store Location
- Product Category
  
# Data cleaning & preparing 
- Converted transaction date and time columns into proper Excel/ date/time format
- Adjusted time display to AM/PM format for clarity (“hh:mm:ss AM/PM” format) 
-	Created Hour column using the HOUR() function to analyze sales by hour.
-	Created Day of Week column using the TEXT([transaction Date], "ddd") to analyze sales by weekday.
-	Created Month column using TEXT([transaction Date], "mmm") to create slicer.
-	Calculated Total Revenue : Quantity Sold * Unit Price
-	Verified that all numerical columns(quantity, price, revenue) were correctly calculated.
# Analysis Approach 
- Using Pivot Tables to summary data
- Using Pivot Chart to build visualization
# Results & Recommendations
[![Demo Image](Output/Dashboard.png)](build/Output/Dashboard.png)


