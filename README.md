# **Hospitality Analytics Project**  

## **Overview**  
This project provides an in-depth analysis of hospitality data to derive actionable insights and evaluate key performance indicators (KPIs) essential for strategic decision-making in the hospitality sector. The dataset encompasses five CSV files detailing bookings, revenue, room types, and hotel information. Analyses were conducted using **Excel**, **Power BI**, **Tableau**, and **MySQL** to deliver comprehensive visualizations and data-driven recommendations.

---

## **Dataset Description**  

### **1. Dim Date**  
Contains date-related information for analysis, including week numbers and day types (Weekend/Weekday).

### **2. Dim Hotels**  
Details of hotel properties, including property ID, name, category (Luxury/Business), and city.

### **3. Dim Rooms**  
Room specifications, including room type (RT1, RT2, etc.) and classification (Standard, Elite, Premium, Presidential).

### **4. Fact Aggregated Bookings**  
Aggregated bookings data, encompassing room categories, capacities, and successful bookings.

### **5. Fact Bookings**  
Booking-level details, including booking dates, check-in/out dates, number of guests, platform used, ratings, and revenue.

---

## **Key Performance Indicators (KPIs)**  
The following KPIs were calculated to assess the performance of the hospitality business:

1. **Total Revenue**  
2. **Total Bookings**  
3. **Occupancy Rate**  
4. **Cancellation Rate**  
5. **Utilized Capacity**  
6. **Trend Analysis**  
7. **Weekday & Weekend Revenue and Bookings**  
8. **Revenue by City & Hotel**  
9. **Class-wise Revenue**  
10. **Checkout, Cancellation, and No-Show Rates**  
11. **Weekly Key Trend (Revenue, Total Bookings)**  

---

## **Data Cleaning and Preparation**  
To ensure the integrity and reliability of the analysis, the following data cleaning steps were implemented:

- **Duplicate Removal**: Verified datasets for duplicates and removed any redundancies.
- **Column Standardization**: Renamed columns for consistency and clarity across all datasets.
- **Data Type Validation**: Ensured appropriate data types for each column (e.g., dates, numerical values) for accurate analysis.
- **Handling Missing Values**: Identified missing values in critical columns and addressed them through imputation or removal based on context.
- **Outlier Analysis**: Detected and managed outliers to prevent skewing of results.
- **DAX Formulas**: For calculating important measures.

## Dashboards
The project includes comprehensive dashboards created in various tools, each visualizing key metrics and insights from the analysis.

### Excel Dashboard
- [View Excel Dashboard](https://github.com/Samikhya-Sahoo/Hospitality-Analytics/blob/main/Excel%20Dashboard.png)

### Power BI Dashboard
- [View Power BI Dashboard](https://github.com/Samikhya-Sahoo/Hospitality-Analytics/blob/main/POWER%20BI%20DASHBOARD.png)

### SQL Queries
- [View SQL Queries](https://github.com/Samikhya-Sahoo/Hospitality-Analytics/blob/main/SQL%20QUERIES.png)

### Tableau Dashboard
- [View Tableau Dashboard](https://github.com/Samikhya-Sahoo/Hospitality-Analytics/blob/main/TABLEAU%20DASHBOARD.png)


---

## **Key Insights**  

1. **Revenue & Bookings**:  
   - Total revenue generated: **1709M** with **135K total bookings**.  
   - **Cancellation Rate**: 24.83%, indicating substantial potential revenue loss.  
   - **Occupancy Rate**: 57.87%, suggesting underutilization of capacity (233K total available rooms).  

2. **Performance by Hotels**:  
   - **Top Performer**: Atliq Exotica stands out as the highest revenue-generating hotel.  
   - **Lowest Performer**: Atliq Seasons requires attention due to its lower revenue performance.  
   - **Revenue by Room Class**:  
     - Elite (33%) and Premium (27%) categories dominate revenue contributions.  
     - Standard (18%) and Presidential (22%) room categories contribute comparatively less.  

3. **City-wise Revenue Trends**:  
   - **Top City**: Mumbai leads in total revenue (413M), followed by Bangalore (270M), Hyderabad (219M), and Delhi (144M).  
   - Notable variations in business and luxury segments, with Mumbai excelling in both.

4. **Revenue by Booking Platform**:  
   - Direct booking platforms contribute the most (699M), indicating a strong performance, while OTA platforms show potential for growth.

5. **Booking Status**:  
   - **Checkout Rate**: 82% of bookings result in checkouts, while cancellations stand at 12%, reflecting a low no-show rate.

6. **Weekday vs. Weekend Performance**:  
   - Weekdays generate higher revenue (1070M) than weekends (639M), coupled with a greater volume of bookings.

7. **Weekly Trends**:  
   - A marked decline in revenue and bookings post-week 27 suggests possible seasonality or operational challenges.

---

## **Recommendations**  

1. **Reduce Cancellation Rate**:  
   - Implement stricter cancellation policies and offer incentives for guests to modify dates rather than cancel.  
   - Conduct an analysis of cancellation reasons and introduce targeted solutions, such as flexible pricing or special promotions.

2. **Optimize Occupancy**:  
   - Enhance marketing strategies for underperforming hotels like Atliq Seasons to boost bookings.  
   - Consider dynamic pricing strategies during periods of low demand to increase occupancy rates.

3. **Focus on High-Performing Categories**:  
   - Promote Elite and Premium room categories through targeted advertising campaigns to drive sales.

4. **Leverage City Insights**:  
   - Concentrate resources in high-revenue cities like Mumbai and Bangalore.  
   - Investigate lower performance in Delhi and develop localized promotional strategies to enhance sales.

5. **Expand OTA Platforms**:  
   - Invest in improving visibility and partnerships with online travel agencies to capture more bookings.  
   - Continuously monitor the performance of direct booking channels to ensure high return on investment.

6. **Address Week 27 Decline**:  
   - Investigate the reasons for the decline in performance after week 27 (seasonality, competition, etc.).  
   - Plan promotional campaigns and special events to revitalize performance during this period.

7. **Boost Weekend Bookings**:  
   - Introduce exclusive weekend packages or offers to attract more leisure travelers.  
   - Collaborate with local events or tourism boards to enhance demand during weekends.

8. **Regular Monitoring**:  
   - Utilize dashboards to track KPIs weekly, including occupancy rates, revenue by city, and cancellation trends, to facilitate proactive decision-making.

---
