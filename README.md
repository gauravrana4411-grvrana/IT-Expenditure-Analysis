# IT-Expenditure-Analysis

The main objective is to give full visibility into how IT costs behave across regions, departments, and cost categories.
Using Power BI, I built an interactive dashboard that compares Actual, Forecast, and Planned IT spend, and highlights variances, overspending, and savings opportunities.”
________________________________________
Business Problem 
“Organizations spend a significant amount on IT operations—labor, infrastructure, governance, shared services, and support.
But without a proper analytical view, it becomes difficult to answer questions like:
•	Where is the IT budget going?
•	Which regions or departments overspend?
•	Are we aligned with the plan?
•	Which cost elements are driving the variance?
This project solves that problem by turning raw IT cost data into a clear, actionable dashboard for decision-making.”
________________________________________
Dataset Overview
“The dataset includes Actual, Forecast, and Plan costs by:
•	Region and Country
•	Business Area
•	IT Area and IT Sub Area
•	Cost Element Group and Sub Group
•	Month and Year
This structure allowed me to analyze the spending across both geography and functional IT categories.”
________________________________________
Data Preparation 
“After importing the Excel dataset into Power BI, I performed several data-preparation steps:
1.	Standardized column names for easy modeling
2.	Handled missing values by filling blank cost fields with zero
3.	Created a proper Date Table for time-series analysis
4.	Categorized fields into dimensions like Region, IT Area, Business Area
5.	Built key DAX measures such as:
o	Total Actual Spend
o	Total Forecast Spend
o	Total Plan Spend
o	Actual vs Plan Variance
o	Forecast vs Plan Variance
These measures formed the foundation for analysis and visualization.”
________________________________________
Key Measures 
“Here are the most important measures I used:
•	Total Actual Spend = SUM(Actual)
•	Total Forecast Spend = SUM(Forecast)
•	Total Plan Spend = SUM(Plan)
•	Actual vs Plan Variance = Actual – Plan
•	Forecast vs Plan Variance = Forecast – Plan
These measures helped me compare the organization’s actual performance against expectations and upcoming forecasts.”
________________________________________
Exploratory Analysis & Findings 
“Before building visuals, I explored the data and found important patterns:
•	Labor is the biggest contributor to IT spending
•	USA and Europe have the highest total spend
•	Actual spending peaks mid-year, while later months drop because the future dataset lacks actuals
•	Planning is slightly optimistic for Governance and Infrastructure categories
•	A few business areas consistently deviate from plan
These findings helped me design the dashboard to reflect the most important metrics.”
________________________________________
Executive Summary Dashboard 
“This is the main dashboard I built. It includes:
•	KPI cards showing total Actual, Forecast, and Plan spend
•	Variance cards highlighting overspend or underspend
•	Pie chart showing distribution of IT costs
•	Stacked bar charts comparing categories like Region or IT Area
•	Monthly trend line chart comparing Actual, Forecast, and Plan
•	Slicers for Region, Business Area, and Month
The goal is to give leadership a one-page snapshot of the financial health of IT.”
________________________________________
Drilldown Dashboard 
“The second dashboard provides deeper cost breakdowns.
It includes:
•	Treemaps for cost distribution by IT Area and Cost Element Group
•	Bar charts comparing internal labor vs shared services
•	Tables with conditional formatting to highlight variances
•	Pie charts for subgroup distribution like hardware, software, depreciation, etc.
This allows finance teams to drill into what exactly is driving spending.”
________________________________________
Category-Level Insights 
“Some key insights derived from the dashboard include:
 IT Area with Highest Spend
Functional & BU Support consistently lead in spending.
Region with Highest Variance
USA shows the highest overspend against plan.
 Cost Category Trends
Internal labor dominates the organization’s IT expense structure.
 Under-utilized Budgets
Governance & Infrastructure show areas where plan was higher than actual spend.
These insights are useful for decision-making, resource allocation, and future budgeting.”
________________________________________
Business Value & Recommendations 
“Based on the analysis, I prepared a few actionable recommendations:
•	Improve forecasting accuracy in regions with consistent variance
•	Re-evaluate labor allocation, since it is the primary cost driver
•	Review planned budgets in Governance and Infrastructure, as underutilization is visible
•	Provide tighter financial governance in high-spend regions like USA
•	Automate monthly data refresh using Power BI Gateway for real-time monitoring
These steps will help optimize IT spending and improve budget adherence.”
________________________________________
Project Impact 
“With this dashboard, decision-makers can now:
•	Track IT spending in real time
•	Compare Actual vs Forecast vs Plan at any level
•	Identify overspending before it becomes critical
•	Drill into specific departments or cost elements
•	Strengthen budget planning for the next fiscal cycles
Overall, the project transforms raw cost data into a strategic tool for financial control.”
________________________________________
Conclusion 
“To summarize:
I built a complete Power BI solution that analyzes IT costs across regions, business units, and cost categories.
The dashboard highlights spending patterns, variances, and cost drivers and enables interactive drilldown capabilities.
This project showcases my skills in data modeling, DAX, visualization design, and business analysis.”

