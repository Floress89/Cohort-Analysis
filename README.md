User Activity and Retention Analysis
This project involves analyzing user activity and retention rates over a period from September 2020 to February 2021. The analysis is performed using several sheets in a Google Sheets document, where various pivot tables and calculations are made to derive insights into user behavior, purchase activity, and retention rates.

Project Description
The objective of this project is to analyze user activity data to understand the conversion funnel, purchase behavior, and retention rates. This analysis helps in identifying key trends and patterns in user behavior, which can be used to inform business decisions and improve user engagement and retention strategies.

Data Sources
The data used in this project includes user activity logs with the following attributes:

user_id: Unique identifier for each user
event_type: Type of user activity (e.g., view, shopping_cart, purchase)
category_code: Product category
brand: Product brand
price: Product price
event_date: Date of the event
Sheets Overview
1. raw_user_activity
Contains raw user activity data.

2. conversion_funnel
Displays the conversion funnel with events in rows and unique user IDs as values.

3. purchase_activity
Shows purchase activity with the user ID as rows and minimum event date as values.

4. first_purchase
Uses VLOOKUP to paste results of user event columns into the purchase_activity sheet and calculate cohort ages.

5. cohort_analysis
Creates a cohort analysis pivot table with first_purchase_month as rows, event_month as columns, and user_id as values.

6. retention_rates
Displays a pivot table with the first purchase and cohort age as rows and the unique count of user IDs as values.

7. retention_rates_clean
Calculated retention rates by dividing the size of the cohorts in following months by the original size of the cohorts.

Analysis Summary
Conversion Funnel
Funnel consists of three major events: view, shopping cart, and purchase.
29% of users who viewed the website added items to their cart.
36% of users who added items to their cart completed a purchase.
Retention Rates
User retention is very low, decreasing month after month.
Suggests providing coupons or incentives to long-time users to improve retention.
Raw Data
Categories include user_id, event_type, category_code, brand, price, and event_date.
Methodology
Data Collection: Gather raw user activity data.
Data Processing: Create pivot tables to summarize the data.
Conversion Funnel Analysis: Calculate conversion rates at each stage of the funnel.
Cohort Analysis: Group users by their first purchase month and track their activity over time.
Retention Rate Calculation: Determine retention rates by dividing the number of retained users by the original cohort size.
Conclusion
The analysis reveals key insights into user behavior:

A significant drop-off occurs between the view and purchase stages of the funnel.
User retention declines steadily over time.
Implementing strategies such as targeted promotions or loyalty programs could help improve user retention and overall sales.
How to Use
To replicate or extend this analysis:

Download the provided Google Sheets document.
Review the individual sheets for detailed analysis steps and pivot tables.
Use the insights to inform business strategies aimed at improving user retention and conversion rates.
For any questions or further information, please feel free to contact me.
