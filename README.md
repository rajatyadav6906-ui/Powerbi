 Sales & Returns Analysis Using Power BI & DAX

 Project Overview

This project focuses on analyzing sales and returns data using Power BI, Power Query, and DAX. The objective was to transform raw and messy transactional data into a structured analytical model capable of generating meaningful business insights.

The project demonstrates the complete Power BI workflow, including data cleaning, data modeling, DAX calculations, filter context analysis, time intelligence functions, and dashboard creation. A Star Schema design was implemented to ensure efficient relationships and optimized performance.



 Tools & Technologies

 Power BI Desktop
 Power Query
 DAX (Data Analysis Expressions)
 Star Schema Data Modeling
 Matrix-Based Dashboard Reporting



Data Model

The dataset was organized into a dimensional model consisting of:

Dimension Tables

 Date_Dim
 Product_Dim
 Customer_Dim
 Region_Dim

Fact Tables

 Sales_Fact
 Returns_Fact

Supporting Table

 Measure_Table

The model was designed using a Star Schema approach to establish efficient relationships between fact and dimension tables.



Star Schema Architecture

![Star Schema](star_schema.png)

The Star Schema serves as the foundation of the project by connecting transactional sales and returns data with descriptive dimensions such as customers, products, dates, and regions. This structure improves query performance, simplifies report development, and supports scalable analytical calculations.



 Tables & Measures Overview

![Tables and Measures](tables_and_measure.png)

The project includes multiple dimension tables, fact tables, calculated columns, and DAX measures designed to support advanced business analysis. A dedicated measure table was used to organize calculations and maintain a clean data model structure.

This approach improves model readability, simplifies maintenance, and follows Power BI best practices for enterprise-level reporting solutions.


 DAX Calculations & Business Logic

![DAX Formulas](dax_formulas.png)

DAX was used extensively throughout the project to create dynamic calculations and business metrics. The implemented logic supports profitability analysis, return tracking, customer insights, sales performance monitoring, filter context evaluation, and time-based comparisons.

The calculations transform raw transactional data into meaningful business indicators that can be used for strategic decision-making and performance assessment.


 Interactive Dashboard

![Dashboard](Final_dashboard.png)

The dashboard provides a consolidated analytical view of sales and returns performance across multiple business dimensions.

Dashboard Highlights

 Regional Sales Performance Analysis

 Time Intelligence & Trend Analysis

 Product Category Profitability Evaluation

 Customer Segment Performance Analysis

 Year-over-Year Sales Comparison

 Profitability and Return Monitoring

 Dynamic Business Performance Tracking



 Key Business Insights

 Regional Performance

The dashboard enables comparison of sales, cost, profit, and return rates across different regions, helping identify high-performing and underperforming markets.

 Time-Based Trends

Time intelligence calculations provide year-to-date performance, previous year comparisons, running totals, and rolling period analysis, making it easier to identify seasonal patterns and growth trends.

 Product Profitability

Category-level analysis helps determine which product groups contribute most to overall revenue and profitability, supporting better product strategy decisions.

 Customer Segmentation

Customer segment analysis reveals purchasing behavior and sales contribution across different customer groups, enabling targeted business strategies.

 Return Analysis

Returns data is integrated with sales transactions to monitor return patterns and evaluate their impact on profitability and overall business performance.



 Skills Demonstrated

 Data Cleaning & Transformation using Power Query

 Star Schema Data Modeling

 Relationship Management

 Calculated Columns & Measures

 Filter Context Functions

 Time Intelligence Functions

 Iterator Functions

 Matrix-Based Reporting

 Business Insight Generation

 Dashboard Design & Visualization



 Project Outcomes

This project successfully transformed raw sales and returns data into a structured analytical solution capable of delivering actionable business insights. By combining data modeling, DAX calculations, and dashboard reporting, the project demonstrates practical Power BI skills commonly used in real-world business intelligence environments.



 Developed Using Power BI, Power Query & DAX