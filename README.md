# Maven Coffee Shop Analysis  Excel Project 
Welcome to the Coffee Shop analysis project repository! This project aims to provide insightful analysis and visualization of Coffee shop data using Excel.
# Overview
This Excel project analyzes sale performance, specifically comparing the revenue and Quantity sold by product categories, store location, days and hours. The dashboard provides insights into sale stategies, maketing campaign, inventory and staffing.
# Data Source
The data is from Kaggle that contain only one table, the coffee shop analysis dataset comprises essential fields such as transactionID, transaction date, Qty sold, revenue, store location, product categories etc.
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


