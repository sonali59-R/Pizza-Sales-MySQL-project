#  Pizza Sales Analysis Dashboard (MySQL + Power BI)

This project analyzes the sales performance of a fictional pizza restaurant chain using MySQL for data cleaning and Power BI for dashboard visualization.
It uncovers trends in revenue, orders, customer preferences, and product performance.

## Project Overview
the goal of this project is to understand the sales Trend

 Which pizza types and categories drive the most revenue?
 How do sales vary by day, week, and month?
 What are the busiest hours for orders?
 Which products underperform or exceed expectations?
 What’s the impact of size and category on sales?

##  Tools & Techniques

MySQL – For data extraction and transformation  
Power BI – For data modeling, visualization, and dashboard design  
DAX Measures – Used for dynamic KPIs and variance calculations  
Conditional Formatting – Dynamic bar coloring for performance analysis  
Calendar Filtering – Used for date-wise trend exploration  

## Dashboard Features

### Page 1 – Overall Sales Overview
 Key metrics: Total Orders, Revenue, Units Sold, Avg. Orders per Day,MOM growth for orders,MOM growth for Revenue,MOM growth for Units
 Monthly trend line of orders, revenue, and units
 Revenue breakdown by:
  Pizza size 
 Pizza category
 Top 5 pizzas by revenue
  Day of week & hour heatmap (for staffing insights)

###  Page 2 – Product-Level Performance
- Table with:
  - ProductName
  - Total Orders
  - Revenue
  - Qty
  - Revenue Variance vs Target  with conditional formating 
- Donut chart showing product mix by category
- Revenue vs Avg revenue trend by order_date


##  Key Insights

 Most revenue comes from Large and Medium pizzas.
 **Chicken** and **Supreme** categories have the highest variety.
 Top performers:  
   The California Chicken Pizza  
   The Barbecue Chicken Pizza  
  Sales are significantly higher on WeekDays than on Weekends and between 12 pm to 8 pm
  Variance analysis identifies pizzas that underperform (great for promotions).

 

##  Dashboard Preview

pizza Dashbord -Summery (pizza_sale1.png)
pizza details- details(pizza_sales2.png)


##  Dataset Source

Kaggle - Pizza sales 48k+ rows



## Author

**Sonali Rajgure**  
Self-driven data enthusiast, focused on learning through real-world projects.  
🔗 [LinkedIn](https://www.linkedin.com/sonalirajgure)




