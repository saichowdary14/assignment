# User Behavior and Order Trends Analysis

This project focuses on analyzing user behavior, cooking preferences, and order trends using data from three datasets. The goal is to uncover meaningful insights and present them through visualizations.

## Project Overview

The analysis combines and examines three datasets:
1. **User**: Contains information about users, such as demographics and preferences.
2. **Orders**: Tracks orders placed by users, including items, statuses, and timestamps.
3. **Cooking**: Records details about users' cooking sessions, including preparation times and dish ratings.

### Objectives
- Clean and merge the datasets to prepare them for analysis.
- Explore relationships and trends in the data.
- Create visualizations to highlight key insights.
- Compile a report summarizing findings and recommendations.

## Process

### 1. Data Cleaning
- Removed missing and duplicate records.
- Standardized data formats for consistency (e.g., date and time).
- Validated key relationships among datasets using joins and cross-checks.

### 2. Data Analysis
- Analyzed correlations between user behavior and order trends.
- Identified popular cooking sessions and their impact on orders.
- Explored ordering patterns across different user demographics.

### 3. Visualizations
Created a Power BI dashboard including:
- **Bar Chart**: Number of orders by meal type, revealing that most orders are dinner orders.
- **Donut Chart**: Orders by area, showing that most orders came from Chicago, Los Angeles, and New York.
- **Area Chart**: Preparation time by dish, highlighting that grilled chicken took the longest time (42 minutes) and oatmeal the shortest (10 minutes).
- **Pie Chart**: Order completion status, showing 88% of orders were completed while 12% were canceled. Notably, all canceled orders originated from Chicago.
- **Bar Chart**: Dish ratings, indicating most dishes (10) received a 4.0 rating, with a few (4) receiving 5.0.
- **Cards**: 
  - Total revenue: $180
  - Average order value: $11
  - Total orders: 94
  - Average preparation time: 30 minutes

### 4. SQL Validation
- Fired SQL queries to validate card values and ensure data accuracy.

### 5. Documentation
- Compiled SQL queries and insights into a Word document.

## Tools and Technologies
- **Python**: For data cleaning and preprocessing.
- **SQL**: For data validation and querying.
- **Power BI**: For creating interactive dashboards and visualizations.
- **Microsoft Word**: For documenting insights and SQL queries.

## Insights
1. Most orders are dinner orders.
2. The majority of orders (3) came from Chicago, Los Angeles, and New York.
3. Grilled chicken took the longest preparation time (42 minutes), while oatmeal took the least (10 minutes).
4. 88% of orders were completed, and 12% were canceled.
5. All canceled orders originated from Chicago.
6. Most dishes (10) received a rating of 4.0, while a few (4) received 5.0.
7. The average preparation time was 30 minutes.
8. The average order value was $11.
9. Total revenue generated was $180.
10. Total orders were 94.

## Repository Structure
```
├── datasets
│   ├── User.csv
│   ├── Orders.csv
│   ├── Cooking.csv
├── analysis
│   ├── data_cleaning_scripts.py
│   ├── merged_data.sql
├── visualizations
│   ├── power_bi_dashboard.pbix
│   ├── charts_and_graphs.png
├── report
│   ├── project_report.docx
├── README.md
```

## How to Use
1. Clone this repository: `git clone https://github.com/your-username/user-behavior-analysis.git`
2. Navigate to the project directory.
3. Explore the `datasets` folder for raw data.
4. Check the `analysis` folder for scripts and SQL queries.
5. Open `visualizations` to view the Power BI dashboard and charts.
6. Read the `report` folder for detailed insights and SQL queries.

## Conclusion
This analysis provides a comprehensive understanding of user behavior and its impact on order trends. The insights can help businesses tailor their offerings to improve user engagement and sales.

---
**Author**: Jetti Sai  
**Contact**: [Your Email Address]
