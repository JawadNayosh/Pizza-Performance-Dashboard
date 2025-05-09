# Pizza Performance Dashboard
<img width="659" alt="Image" src="https://github.com/user-attachments/assets/180c9cf4-4777-482f-b05b-f1a8644bfa7c" />

## Project Overview
This project focuses on analyzing pizza sales data to generate key insights into revenue, order patterns, and top-selling items. 
The analysis was performed using SQL Server for data extraction and transformation, followed by creating a visually rich Excel 
dashboard to showcase the findings.

## Objective
The primary goal of this project is to gain insights into pizza sales performance, including:
Total revenue and average order value.
Order trends by day and time.
Sales distribution by pizza category and size.
Identification of best and worst-selling pizzas.
Analysis of hourly and daily order patterns.

## Tools and Technologies Used
SQL Server: Data cleaning, transformation, and analysis.
Excel: Data visualization and dashboard creation.
GitHub: Project documentation and sharing.

## Project Workflow
### 1. Data Cleaning and Preparation (SQL)
Extracted the raw pizza sales data from Pizza DB.
Checked for missing values and inconsistencies.
Standardized date and time formats for uniformity.
Calculated key metrics such as total revenue, average order value, and total pizzas sold.

### 2. Data Analysis (SQL)
Executed several SQL queries to derive insights:
#### KPIs Calculation:
Total revenue
Average order value
Total pizzas sold
Total orders
Average pizzas per order

#### Trend Analysis:
Daily trend for total orders.
Hourly trend for total orders.

#### Sales Breakdown:
Percentage of sales by pizza category.
Percentage of sales by pizza size.
Total pizzas sold by category.

#### Best and Worst Sellers:
Top 5 best-selling pizzas.
Bottom 5 least-selling pizzas.

### 3. Data Visualization (Excel)
Imported the cleaned data into Excel for visualization.
Built a dynamic Excel Dashboard to present the analyzed data.
Utilized bar charts, pie charts, and KPI cards to display key metrics.
Included interactive filters (slicers) to explore data by time and category.

## Key Insights
### Sales Performance:
Total Revenue: $817,860
Average Order Value: $38.31
Total Pizzas Sold: 49,574
Total Orders: 21,350
Average Pizzas Per Order: 2.32

### Order Patterns:
Busiest Days: Friday to Sunday
Peak Order Time: 12:00 PM - 1:00 PM and 4:00 PM - 7:00 PM
Most orders occur during weekends.

### Category Insights:
Top Pizza Category: Classic
Popular Pizza Size: Large
Best and Worst Sellers:

### Best Sellers:
The Classic Deluxe Pizza
The Barbecue Chicken Pizza
The Hawaiian Pizza

### Worst Sellers:
The Soppressata Pizza
The Spinach Supreme Pizza

### Hourly Trends:
Peak ordering hours are 10:00 AM to 2:00 PM and 6:00 PM to 8:00 PM.

## Visualization Highlights (Excel Dashboard)
KPIs: Displayed key sales metrics at the top.
Daily and Hourly Trends: Bar and line charts to visualize order frequency.
Category and Size Analysis: Pie charts for percentage breakdown.
Top and Bottom Sellers: Horizontal bar charts to compare pizza sales.
Interactive Date Filter: Allows filtering data by month.

## Conclusion:
The Pizza Sales Analysis project provided valuable insights into the sales performance and ordering patterns of a pizza business. 
Using SQL for data cleaning and aggregation, and Excel for visualization, we were able to:
Identify peak sales periods (weekends and specific times of the day).
Highlight top-performing pizza categories and sizes, with Classic and Large pizzas leading the market.
Determine the most popular pizzas by volume and revenue, with The Classic Deluxe Pizza being the top seller.
Uncover less popular items, allowing for potential menu optimization.
The dashboard serves as a comprehensive tool for decision-makers to monitor sales trends, evaluate performance, and develop targeted strategies to enhance revenue.

## Recommendations:
### Marketing and Promotion:
Focus marketing efforts on weekends (Friday to Sunday) when order volume is highest.
Offer special deals during peak hours (12:00 PM - 1:00 PM and 4:00 PM - 7:00 PM) to maximize revenue.

### Menu Optimization:
Consider reducing or rebranding less popular items, such as The Soppressata Pizza and The Spinach Supreme Pizza.
Introduce more variations or seasonal promotions for the top-selling categories.

### Inventory and Supply Chain:
Prioritize stock and ingredients for the most ordered pizza sizes (Large and Medium).
Reduce inventory for less popular sizes to minimize waste.

### Data-Driven Strategy:
Continuously update the dashboard with new sales data to track changes in customer preferences.
Implement A/B testing for new promotions and analyze their impact on sales trends.

### Customer Engagement:
Conduct customer satisfaction surveys to better understand why some pizzas are less popular.
Introduce limited-time offers for underperforming pizzas to gauge customer interest.



## Challenges Encountered
Date Formatting Issues: Resolved using SQL date functions to ensure consistent formatting.
Grouping Data in Excel: Managed to group dates by months after correcting formatting inconsistencies.

