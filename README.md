# Overview
This Excel project analyzes sale performance, specifically comparing the revenue and qty from product name, store location, days and hours. The dashboard provides insights into sale stategies, maketing campaign, staff and stock inventory.
# Data Source
The project use only one table that contain : transactionID, transaction date, Qty sold, unitprice, store location, product categories 
# Data cleaning & preparing 
- Converted transaction date and time columns into proper Excel/ date/time format
- Adjusted time display to AM/PM format for clarity (“hh:mm:ss AM/PM” format) 
-	Created Hour column using the HOUR() function to analyze sales by hour.
-	Created Day of Week column using the TEXT([transaction Date], "ddd") to analyze sales by weekday.
-	Created Month column using TEXT([transaction Date], "mmm") to analyze monthly trends.
-	Calculated Total Revenue : Quantity Sold * Unit Price
-	Verified that all numerical columns(quantity, price, revenue) were correctly calculated.
# Analysis Approach 
- Using Pivot Tables to summary data
- Using Pivot Chart to build visualization
# Results 
[![Demo Image](build/Screenshot%202026-03-03%20222905.png)](build/Screenshot%202026-03-03%20222905.png)


