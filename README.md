# MeteroGoods-Retail-Sales-Analysis
An end-to-end Excel based retail analysis project exploring MeteroGoods sales performance. Includes data cleaning, KPI creation, pivot table dashboards and interactive charts for sakeholders reporting.

## Introduction
This project explores sales performance at MeteroGoods Retail Stores, focusing on customer demographics, product categories, purchase patterns,and sales trends. The goal is to uncover actionable insights that guides business decisions, improve revenue, and optimize inventory

## Project Description
* Analyzed Sales data to evaluate revenue performance, customer trends, customer behavour and product trends.
* Developed key performance indicators (KPIs) that measures business health across time, and product categories.
* Built a dynamic stakeholder friendly dashboard to monitor sales performance and trends.
* Provide insightful reporting that supports data driven  decisions in retail operations.

 **Approach**
 1. Data Cleaning & Preparation: Standerdized and structured the MeteroGoods dataset, ensuring accuracy and consistency
 2. Exploratory Data Analysis: Performed trend analysis across time, and product categories etc. to identify performance drivers.
 3. KPI Development: Calculated core metrics such as total revenue, revenue growth, total quantity, and total selling price
 4. Dashboard Design: Develoed an interactive Excel dashboard using pivot tables, charts, and slicers for real time exploration of insights
 5. Reporting & Insights: Interpreted the results and provided recommendations for improving sales performance.

  ## Project Aim 
  To demonstrate proficiency in data cleaning, KPI development, and dashboard creation by applying Excel based analysis to MeteroGoods dataset, with the goal of uncovering insights that   informs strtegic business decisions.

  ## About the  Dataset
  * **Source**: The dataset is a simulated retail dataset representing MeteroGoods transactional sales record gotten from the Skills To Career Mentorship
  * **Size**: Contains 1000 rows and 9 columns of transactional data
  * **Key Feilds**
    1. Transaction ID: Unique Identifier for each sale
    2. Date: Date of Transaction, used for time based analysis
    3. Customer ID: Unique identifiers for customers
    4. Product Category: Category of items purchased
    5. Quantity: Number of units sold
    6. Selling Price per Unit: Price per unit of product
    7. Gender: Gender of customers
    8. Age: Age of customers
    9. Revenue: Computed feild (Quantity * Selling Price per Unit)
  
   ## Tools Used
   * **Microsoft Excel**: Core tool for analysis, visuslization annd dashboard creation.
   * **Power Query**: For data cleaning, preparation, and transformation of raw raw dataset.
   * **Pivot Tables &Pivot Charts**: To summarizeand analyze sales performance across multile dimensions
   * **Excel Slicers**: To add interactivity and dynamic filtering to the dashboard.
   *  **Github**: For documentation and portfolio presentation
 
   ## Importig the Dataset
   The MeteroGoods dataset was imported using Power Query in Microsoft Excel to ensure a smooth and structured woerkflow. The steps includes:
   1. **Data Source Connection**: Connected directly to the raw excel file containing the raw MeteroGoods dataset via Power Query.
   2. **Data TYpe Recognition**: Ensured all columns where assigned correct datatype.
   3. **Initial Cleaning**: Applied basic transformations such as renaming columns, and checking for duplicates
   4. **Load To Excel**: Loaded the clean dataset into Excel's Data Model for further analysis and dashboard development
 
  ## Data Cleaning and Transformation
  To ensure MeteroGoods dataset was reliable and business ready, I aplied systematic cleaning and transformation steps in Power Query(Excel):
  * **Renamed Columns for Clarity**: Simplified confusing headers to make the dataset stakeholder friendly(E.g "Total Amount" - "Revenue", and "Unit Per Price" - "Selling Price per            Unit")
  * **Corrected Data Types**: Changed Transaction ID from number to text, since IDs are identifiers and not measurable, I also changed the date data type to date using locale, I changed       the Selling Price per Unit and revenue column to currency data type as well.
  * **Checked for Dupliates**: Checked for duplicates and didnt find any.
  * **Scanned for Missing Values**: Applied filters across columns to verify completeness
  * **Ensured Consistency**: Validated that numeric feids contained only numerical values without text errors.
     
  ## Data Analysis
  The MeteroGoods dataset was analyzed to evaluate sales performances, customer behavior, and revenue trends (Year-Year). The metrics and KpIs  explored includes:
  * **Revenue**: Overall Revenue generated
  * **Quantity**: Units sold across different product categories
  * **Selling Price**: Total Price Sold
  * **Monthly Sales Trend**: Time series analysis of sales volume and revenue across months.
  * **Purchase Behavior Analysis**: Understanding customer buying patterns and frequency.
  * **Best Performing Product**: Identifying producttop performing categories based on revenue
  * **Revenue Contribution by Age Group**: Analyzing how different customers age bracket contributes to revenue.
  These analysis provided a comprehensive view of MeteroGoods retail performance, highlighting both product level and customer level insights. 

## Data Visualization
To communicate insights effectively, i designed an interactive Excel dashboad combining KPI cards and visual charts. The visualizations where selected to make complex data simple and stakeholder friendly:
* **KPI Cards**: Displaying high level metrics which includes Total Revenue, Total Quantity and Selling Price for quick performance tracking.
* **Bar Chart (Best Performing Product)**: Highlighting the top selling products and categories, enabling easy comparison of performance.
* **Line Chart (Monthly Sales Trend)**: Showing revenue trends across months to uncover seasonality and growth patterns.
* **Pie Chart (Purchase Behavior Analysis)**: Illustrating customer purchasing distribution for a clear vew of buying patterns.
* **Bar Chart (Revenue Contribution by Age Group)**: Comparing how different age brackets contribute to overall revenue.
This visualizations combined to a stakeholder ready dashboard allowing decision makersto explore sales peformance, customer behavior, and revenue trends at a glance.

## Key insights
This analysis addressed sevsral critical business questions. Below are findingss tied directly to each question:
1. **Which age group drives the highest revenue**: Customerss with ages ranging from 45-54 (Mature Adults) were the top revenue drivers contributing $97.2k in revenue.
2. **Which product category contributes most in overall revenue**: Electronics led all product categories with $156.9k in revenue showing strong demand for tech products and gadgets.
3. **When are the peak sales period**: May emerged as the peak sales months, generating $58.6k in revenue
4. **What purchase pattern do top spenders follow**: Bulk purchases accounted for 90% of total revenue (411.1k), far surpassing single purchases.
5. **Which low performin product category should be improved**: Beauty products generated only $142.0k, signaling weak demand or poor positioning 
    
 
  
  
