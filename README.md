# Business-Insights-360---Atliq-Hardwares


Project Overview

AtliQ Hardware is experiencing rapid growth, prompting the implementation of data analytics using Power BI to leverage insights from a dataset exceeding a million records. This initiative aims to extract actionable insights across Finance, Sales, Marketing, Supply Chain, and Executive domains. Live Dashboard: 

### Project Goal:

The primary objective is to utilize financial analytics to optimize AtliQ Hardware's performance and profitability. By analyzing the company's financial data, the goal is to uncover actionable insights empowering decision-makers to make informed strategic choices and drive sustainable growth.

### Key Focus Areas:

-Enhanced Profitability: Identify opportunities to boost profitability through analysis of net profit, gross margin, and profit percentages.

-Precision Forecasting: Improve financial planning with accurate forecasts, minimizing uncertainty and maximizing resource allocation efficiency.

-Risk Mitigation: Proactively identify and address potential risks, safeguarding financial stability.

-Strategic Empowerment: Equip decision-makers with insights to navigate market challenges, optimize strategies, and foster sustainable growth.

### Transformative Power BI Skills Learned from Business Insight 360: ➡ Strategic project kick-off questions

➡ Proficiency in ETL process

➡ Expertise in data modelling

➡ Development of calculated columns and DAX measures

➡ Utilization of functions such as CALCULATE, SUMX, RELATED, ALL, FILTER, SWITCH, CONCATENATE, SELECTEDVALUE, ISBLANK, FORMAT, etc.

➡ Implementation of seamless visual navigation with bookmarks

➡ Creation of KPI indicator visuals

➡ Design of new card visuals and button slicers

➡ Enhancement of visuals through conditional formatting with icons and background colours

➡ Application of data validation techniques

➡ Publication of reports to Power BI services

➡ Configuration of personal gateway for data auto-refresh

➡ Management of content on Power BI services

### Questions to Ask Before Starting with Dashboard: ➡ What is the primary objective of building this Power BI dashboard❓

➡ How will the success of this project be measured❓

➡ What is the project's deadline❓

➡ Do stakeholders expect a preview before the official release❓

➡ What are the stakeholders' expectations from this project❓

➡ What concerns do stakeholders have regarding the development of this dashboard❓

➡ Who will be using this dashboard and for what purposes❓

➡ What are the stakeholders' expectations upon project completion❓

➡ What potential challenges could arise during the project development❓

➡ What resources and data are required to build this dashboard❓

➡ Do stakeholders have specific inputs regarding the design and views of the dashboard❓

After the Project Kick-off Meetings The data engineering team has delivered the requested data to the analytics team. Let's dive in and explore the insights within.

### Dataset Understanding Understanding the available data is crucial for effective analysis. Before diving into analysis, it's essential to grasp the data at hand.

📌Dimension Table: Contains static data such as customer and product details.

📌Fact Table: Contains transactional data.

📌gdb041:

• Dim Customer: Details on markets, customers, platforms, and channels.

• Dim Market: Information on markets, sub-zones, and regions.

• Dim Product: Product divisions, categories, and variants.

• Fact Forecast Monthly: Forecasted customer needs.

• Fact Sales Monthly: Actual sales data.

📌gdb056:

• Freight Cost: Travel and other costs for each market.

• Gross Price: Gross prices with product codes.

• Manufacturing Cost: Manufacturing costs with product codes.

• Pre-Invoice Deductions: Pre-invoice deductions percentage for each customer.

• Post-Invoice Deductions: Post-invoice deductions and other details.

### Importing Data into PowerBI

* As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential.

  
Data Model
* Data modeling plays a vital role and is considered as the basement of the report. All the visuals will be built upon the data model.
* Poor data modeling affects the overall performance of the report.
* Following Good practices of data modeling is a must. Refer to this page to get to know the good practices of Blog
* In this project, we have followed the Snowflake data modeling schema.

![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/cb9e789910c346f0eb951bed0589149fb7e59b4c/Data%20Modelling.png)


Dashboard designing Based on the mock-ups received as required, the team will start designing the visuals and create measures as and when required.

In Home view, all the views button will be available. Users will land on a specific view page by clicking the button

* Home Page
* Info
* Finance View
* Sales View
* Marketing View
* Supply chain View
* Executive View
* Support

### Home Page
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Home%20Page.png)
### Info Page
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Info.png)
### Finance View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Finance%20View.png)
### Sales View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Sales%20View.png)
### Marekting View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Marketing%20View.png)
### Supply Chain View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Supply%20Chain%20View.png)
### Executive View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Executive%20View.png)
### Support View
![image alt](https://github.com/Satyam24/Business-Insights-360---Atliq-Hardwares/blob/f1e2f3a5c068490141bcbda49d3da4eca862f0c6/Support.png)
