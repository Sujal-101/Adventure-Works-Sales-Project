#  🚴 Mountain Bikes Sales Dashboard-Power BI Project 🚴

## 🧩 Problem Statement
The sales team at a mountain bike company needed a centralized and interactive solution to monitor overall sales performance, identify top-selling products, analyze return rates, and understand customer segments. The goal was to transform raw sales data into actionable insights to support better business decisions and improve profitability.

## 📌 Project Overview:
This Power BI dashboard provides a comprehensive analysis of Mountain Bikes sales performance. It showcases key metrics like revenue, profit margin, order volume, and return rates, along with visual breakdowns by product categories and sales trends over time.

## 🔍 Key Insights

1. Total Revenue: $24.91M
This figure represents the overall sales generated from mountain bike products over the selected time period. A revenue of nearly $25 million indicates a healthy business with strong customer demand and successful product strategies.

2. Profit Margin: $10.46M
The profit margin highlights how much of the total revenue remains after deducting costs. With a profit of $10.46M, the business is operating efficiently and earning a solid return on sales. The average product profit margin (44.26%) shown in the product table supports this strength.

3. Total Orders: 25K
This metric reflects the volume of customer transactions. A total of 25,000 orders shows a strong customer base and steady demand across categories, particularly in Accessories and Bikes, as seen in the category-wise order chart.

4. Return Rate: 2.17%
A low return rate indicates high customer satisfaction and low product issues. At 2.17%, this rate suggests that most buyers are happy with their purchases and that the logistics, quality control, and product descriptions are effective.

## 🔗 Model View

<img src="Model View.jpg" width=1000>

The data model follows a star schema, with a central fact table (Sales_Final) connected to dimension tables like Customer, Product, Calendar, and Territory. This structure ensures efficient data relationships, enables smooth filtering, and supports powerful analysis across multiple business dimensions.

## 🧹 Data Cleaning & Transformation

The raw data was cleaned and transformed using Power Query to make it analysis-ready. This included removing errors, correcting data types, and creating custom fields. New columns like full name, age, age group, income level, and parent status were added in the Customer table. The Product table was enhanced with a gender type column, and the Calendar table was enriched with useful date fields like month name, quarter, and start of week. These transformations made the data more meaningful, structured, and ready for building an insightful dashboard.

## 🧮 DAX Measures Used in This Project

DAX calculations using functions like SUM, SUMX, DIVIDE, and DISTINCTCOUNT were used to derive key metrics such as total revenue, profit margin, order count, etc. These dynamic measures enabled interactive analysis across time, product, and customer dimensions, providing meaningful business insights through the dashboard.


## 📊 Dashboard Features

1. KPI Cards for Revenue, Profit Margin, Orders & Returns

2. Year and Month Slicers for custom filtering

3. Revenue Trend Line Chart showing sales performance over time

4. Category-wise Order Distribution (Accessories, Bikes, Clothing)

5. Top 10 Product Performance Table with metrics: Revenue, Orders, Profit Margin %, Return Rate %

## 🛠 Tools & Skills Used

1. Power BI Desktop

2. DAX (for calculated measures like profit margin %, return rate, etc.)

3. Power Query (data cleaning and transformation)

4. Data Visualization Best Practices (consistent color scheme, clear labels, KPIs)

## 🎯 Objectives

1. Analyze sales trends and top-performing products

2. Understand customer return behavior

3. Identify which categories contribute most to total orders

4. Gain hands-on experience with Power BI tools and dashboarding

## Sample Dashboard

<img src="Mountain Bike Sales Dasboard.jpg" width=1000>

<img src="Orders by Country.jpg" width=1000>


