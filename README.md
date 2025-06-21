# GLOBAL-SUPERSTORE-ANALYSIS
A complete sales performance analysis using POWERBI for Global Superstore

# Global Superstore Sales Analysis Project
## Project Overview
Global Superstore is a global online retail business with the vision of becoming a one-stop shop for customers worldwide. With a diverse customer base across 147 countries and an extensive product range, I was hired as a data analyst to uncover key insights that will help improve profitability and customer experience.

The main objective of this project is to explore sales data using Power BI, with a focus on:

Cleaning and transforming data using Power Query

Data modeling and calculations

Data visualization through interactive charts and dashboards

Delivering business insights to inform strategic decisions

# Tools Used
Power BI Desktop (for end-to-end analysis)


Power Query Editor (for data cleaning and transformation)


DAX (Data Analysis Expressions) (for calculated columns and measures)


Microsoft Excel (original dataset format)


PowerPoint (for dashboard design enhancement)


GitHub (for portfolio presentation)



# Project Structure
```
Global-Superstore-Project/
├── GlobalSuperstore.pbix                # Power BI project file
├── DashboardDesign.png                  # Screenshot of final dashboard
├── insights.txt                         # Business insights and summary
└── README.md                            # Project description and process
```


## Business Problem
Global Superstore wants to be a one-stop shop . In my understanding, their aim is to meet a wide range of customer needs in one place. For this to be achieved,the business has to;

1.Improve profitability


2.Identify best-selling products and customers


3.Reduce costs (e.g. shipping, discounting)


4.Focus on markets with high potential


5.My role was to explore and analyze their transactional dataset to offer actionable insights.

# Data Cleaning Process
I cleaned and prepared the data in Power Query:

Removed unnecessary columns (e.g. postal codes, customer segment)


Checked for null values


Converted date columns into proper formats


Split country regions to simplify filtering


Ensured all numerical fields were in the correct data types



# Key Metrics Created (DAX Measures)
Total Sales = SUM(Sales)


Total Profit = SUM(Profit)


Average Shipping Cost = AVERAGE(Shipping Cost)


Number of Orders = DISTINCTCOUNT(Order ID)


Average Profit = AVERAGE(Profit)



# Visualizations & Analysis

Some of the specific business questions I answered through the visualizations are:

1.Top 3 Countries by Profit (2014)


2.Top Profitable Products in These Countries


3.Highest Shipping Cost Subcategories (US)


4.Nigeria's Poor Performance Analysis


5.Least Profitable Subcategory in Southeast Asia


6.City in US with Lowest Average Profit


7.Most Valuable Customers and What They Purchase


**Each visual was done using KPI Cards, slicers, clustered charts, tables, and filters.**

# Final Dashboard Highlights
Total Sales, Profit, Orders, Shipping KPIs


Top Performing Country Card


Interactive filters and drilldowns


Visually appealing layout with floating panels, shadows, and consistent themes (This was done in PowerPoint)



# Key Insights

USA, Australia, and India are the top profit-generating countries.


Nigeria's profit is low due to high discounts and low shipping costs.


Some Southeast Asian countries are performing poorly in specific subcategories.


Several U.S. cities with low orders still skew the average profit.


High-value customers usually bought a single product type per order, with high associated profit.



# Lessons Learned

The power of filtering and slicers to gain focus


Importance of clean, intuitive dashboards for stakeholders


How PowerPoint can enhance Power BI presentations visually


GitHub as a valuable tool for project documentation and visibility



