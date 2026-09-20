# Credit-Card-Financial-Weekly-Report-Power-BI

![image alt](https://github.com/AnkitaSarkar-98/Credit-Card-Financial-Weekly-Report-Power-BI/blob/main/Credit%20Card%20Customer%20Weekly%20Dashboard.png?raw=true)


# Overview

An interactive Power BI Credit Card Financial Weekly Report built to analyze customer profiles, credit card usage, transaction performance, spending patterns, and weekly revenue trends.

The project contains:
- Credit Card Customer Report
- Credit Card Transaction Report
- Customer Details Drill-Through Page
The dashboards use interactive slicers and DAX measures to make the analysis easy to explore by Gender, Age Group, Income Group, Week, Spending Category, Education, and Card Type.

  # Key Insights
  
- 10,293 customers analyzed.
- Total transaction revenue: 45.53M
- Total transaction volume: 667K
- Total interest earned: 7.98M
- Bills generate the highest revenue among spending categories.
- Blue is the dominant card category.
- The largest customer age groups are 36–45 and 46–55.
- Income segmentation:
  - Low: < 25,000
  - Med: 25,000–75,000
  - High: > 75,000
- Weekly analysis tracks revenue, transaction volume, interest earned, and WoW revenue change across Week 1–Week 53.
- Drill-through allows users to move from the customer dashboard to detailed information for an individual Client_Num.

 # Tools & Methods
 
# Power BI

- Interactive dashboards
- KPI cards
- Slicers and filters
- Drill-through
- Weekly trend analysis
- Data modelling

# Power Query

- Data cleaning and transformation
- Data type correction
- Text trimming
- Week data preparation
- Data quality validation

# DAX

Created calculated columns and measures including:
- Age Group
- Income Group
- Total Customers
- Total Revenue
- Total Transaction Volume
- Total Interest Earned
- Average Income
- Average Age
- Average Satisfaction
- Average Credit Limit
- Current/Previous Week Revenue
- WoW Revenue %
Data Model
The project uses:
- DimCustomer
- FactCreditCard
- DimWeek
Client_Num is used to connect customer and credit card information.

   Dashboard Features

# Customer Report

Includes:
- Customer distribution by Age Group
- Income Group analysis
- Customer Job
- Education Level
- State distribution
- Card Category
- Customer KPIs
- Customer Details Drill-Through

# Transaction Report

Includes:
- Revenue by Spending Category
- Revenue by Card Category
- Revenue by Transaction Type
- Weekly Revenue Trend
- Transaction Volume by Week
- Weekly performance table
- WoW Revenue analysis

   Data Quality Considerations

The source Week_Start_Date contained inconsistent date representations, so Week_Num was used to create a reliable weekly sequence.
The project brief mentions a Credit Score, but the provided customer dataset does not contain a Credit Score field. Therefore, no credit score was invented or calculated.

# Conclusion

This project demonstrates an end-to-end Power BI data analytics workflow, from Power Query data preparation and data modelling to DAX calculations, interactive dashboards, weekly performance analysis, and customer-level drill-through.
The final solution provides a clear view of customer characteristics, revenue performance, transaction activity, and spending behavior.


Thank you for taking the time to check out this project! Your interest, feedback, and contributions mean a lot. If you have any suggestions, feel free to share.
Don't forget to ⭐ star this repository if you found it helpful — it really helps others find it too.
Happy coding
