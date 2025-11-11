# sales-analytics-dashboard
E-commerce Sales Dashboard provides interactive insights into sales performance, revenue, and customer trends. It visualizes key metrics, identifies top products, and helps businesses make data-driven decisions through dynamic charts and KPIs for improved growth and strategy.

# E-Commerce Sales Dashboard (Power BI)

## 📖 Project Overview
This Power BI project showcases an **E-Commerce Sales Dashboard** designed to analyze key business metrics such as total sales, profit, quantity sold, and order details.  
It provides valuable insights into **regional sales performance**, **category-wise distribution**, and **customer payment preferences**, helping businesses make **data-driven decisions**.


## 🎯 Objectives
- Analyze overall sales, profit, and quantity trends.
- Identify top-performing states and product categories.
- Track monthly profit performance.
- Understand customer payment preferences.
- Support business decisions through visual insights.



 📊 Key Performance Indicators (KPIs)
| Metric | Value |
|--------|--------|
| 🧾 Total Orders | 121K |
| 💰 Total Sales Amount | 438K |
| 📦 Total Quantity Sold | 5615 |
| 📈 Total Profit | 37K |


 📈 Dashboard Insights
- **Top States:** Maharashtra, Uttar Pradesh, Delhi  
- **Top Categories:** Clothing (63%), Electronics (21%), Furniture (17%)  
- **Most Used Payment Mode:** Cash on Delivery (44%)  
- **Best Performing Months:** October and December  
- **Top Sub-Categories:** Bookcases, Printers, Tables  



##  Tools & Technologies Used
- **Power BI Desktop** – For creating dashboard visualizations  
- **Excel / CSV** – As data source  
- **Power Query Editor** – For data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – For custom calculations and KPIs  
- **GitHub** – For project documentation and version control  



## 🧮 DAX Measures Used
DAX
Total Sales = SUM(Sales[Amount])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Amount]))
Total Quantity = SUM(Sales[Quantity])
