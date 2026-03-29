##🍕 Pizza Sales Performance Analysis (2015)

##Project Overview
This project involves a comprehensive analysis of a pizza restaurant's sales data from 2015. The goal was to transform over 48,000 rows of raw transactional data into actionable business insights regarding sales trends, customer behavior, and inventory requirements.

#Tools & Technologies
- Microsoft Excel: Primary tool for data cleaning, analysis, and visualization.
- Data Cleaning Techniques: Text to Columns (Date Standardization), Data Validation, and helper columns using =TEXT(), =HOUR(), and =VALUE().
- Data Visualization: Pivot Tables, Dynamic Charts, and Interactive Slicers.

#Data Cleaning & Preparation
To ensure the accuracy of the dashboard, the following steps were taken:
- Date Standardization: Resolved inconsistencies where dates were stored as text using the Text to Columns wizard.
- Feature Engineering: Created new attributes for Month Name, Day of Week, and Order Hour to identify peak performance periods.
- Currency Formatting: Standardized all financial columns to ensure accurate Revenue and AOV (Average Order Value) calculations.

#Key Insights
- Total Revenue: $817,860
- Average Order Value (AOV): $38.31
- Peak Sales Period: Fridays recorded the highest sales volume, with daily "Double Peaks" occurring at 12:00 PM and 6:00 PM.
- Best Selling Category: The Classic pizza category drives the most revenue, while Large (L) sizes account for nearly 46% of total sales.

#Dashboard Preview
Here is my dashboard screenshot 
![Dashboard Screenshot](Screenshot(10)_1.png)

#Lessons Learnt
1. Data Integrity: Learned how to troubleshoot "Text-to-Date" conversion issues in Excel which initially broke the time-based formulas.
2. Business Acumen: Understood how to translate raw numbers into operational advice (e.g., suggesting staffing changes based on peak hour trends).
3. UX Design: Focused on building an interactive experience using Slicers so stakeholders can filter data by size or category without needing Excel expertise.
