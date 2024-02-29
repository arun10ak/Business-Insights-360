# Business-Insights-360 [SQL | Power BI | MS Excel]
---
## SQL Data Exploration & Power BI Dashboard
### Domain: Financial Domain
### Project Overview:
--- 
AtliQ Hardware has been growing rapidly in recent years, and they have decided to implement data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data-driven decisions. This project is hoped to give answers to the questions of stakeholders in terms of all aspects like finance, sales, marketing, and supply chain.

I worked on this project by following the Codebasics PowerBi Course, The Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

❇️ Novypro Power BI Dashboard - [Live Report Link](https://www.novypro.com/project/business-insight---360)

❇️ MySQL Finding - 

### Company's Background:
---
AtliQ Hardware manufactures and sells hardware like PC, Mouse, Printers, etc to multiple companies across the world. AtliQ’s customers are companies like Croma, Amazon, Neptune, Staples, Walmart, etc.

*These customers are of two types,*
- Physical Stores 
- E-commerce platforms

*They sell their products through three mediums/channels,*
- Retailers
- Direct
- Distributors

### Problem Statement:
--- 
AtliQ Hardware is struggling to do good business in various parts of the world. So far, all the decisions that AtliQ took have been based on some surveys and intuitions.

AtliQ Team uses MS Excel for data analysis but as the business expands globally company's Top management decides to use Power BI for data analytics. So Top management wanted the analytics team to Provide insights through SQl to make decisions and as the later part of the Project, a dashboard was created for various key departments, so they can get insights on important metrics and make data-driven Decisions.

### WorkFlow:
---
### MySQL WorkBench
- Data was Loaded into Mysql and the database was designed by establishing relationships in a Snowflake schema format between the tables with ERD in MySQL.
- Data was ready for Data Analysis and key metrics were Derived, for all the requests from Product owners.
- A Data pipeline was established in deriving Metrics, with many Data Cleaning methods implemented in between.
- Stored Procedures were created for the complex Queries so that Product owners can extract reports by necessary filters.

### PowerBI Dashboard:
- The first step was to load the data into MySQL Database and connect it to the Power BI. 
- Review and delete the Database relationship created by Power BI by default. Also, creating the required dimension table in Power Query.Data validation using some tables in Power BI and matching the values with the data provided.
- Data Transformation. For example, creating a Last Sales Month Reference table. So, the last sales month reference table will be dynamic and will change after every sale. Created calculated columns in Power Query like a fiscal year and merged the tables.
- Data modeling is a connection between different tables using a common table between them. In this project, Start Schema is used for Data Modelling where all the dimension tables were connected with Fact tables.
  
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/c5b0c1a1-7f51-4e54-9236-0cb8f560782b)
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/c26b7516-1dbb-48aa-a47a-e2f06ecdf82f)

- Created calculated columns using more than 40 DAX formulas (Formulas listed at the bottom). After the columns are created, verify them in either MySQL.
- 
### Dashboard Overview:
---
✔ Home:

The first page of the report is a home page with the navigation to all other views and a summary of each page so a user can directly access the report they need to look at.

![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/bed29a7a-82ed-4d4d-b6d6-5fc35887251d)
---

I have created 5 different report views in this report which serve the needs of various stakeholders, and specifically targeted to various departments to give an overview of the company's performance.

✔ Finance View :

- The profit and loss Statement, explains various P&L Metrics from Gross Sales to Net Profit.BM indicates the benchmark, which is Either Last year or the Target, which can be selected through Slicer Provided.
- KPIs for Net Sales, Gross Margin %, Net Profit %.
- Net sales Performance Trend in comparison with Target/Last Year which can be selected Dynamically.
- Top / Bottom Products and Top / Bottom Customers based on Net Sales
  
  ![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/321f8881-e9e7-474c-8e28-436a04248100)

✔ Sales View :

- Unit Economics 1: Net Sales vs Total Post Invoice Discount Amount and Pre-Invoice Discount Amount given by the Company.
- Unit Economics 2: Total Cost of Goods Sold (COGS) spent by the Company and then finally got the actual Gross Margin.
- Customer and Product Performance analysis based on Net Sales, Gross Margin, and Gross Margin %.
- Performance Matrix analysis for Market, Customer, and Region based on Net Sales and Gross Margin %.
- Sales Trend Tooltip for every single Customer based on Net Sales and Gross Margin %.
  
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/5166a159-01ee-47c4-ac91-a4ec412660dc)
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/3b2cc835-28d5-4cc4-a94e-7b15eb97f3b7)

✔ Marketing View :

- Unit Economics: There are some Operational Expenses spent for the Product. After subtracting these Expenses got the actual scenario of Net Profit.
- Performance Matrix analysis for Segment, Category, and Product based on both “Net Sales & Net Profit %” and “Net Sales & Gross Margin %” by using a dynamic toggle button.
  
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/6ef1f022-b036-4cdb-a286-1992b33e2c92)

✔ Supply Chain View :

- KPIs for Forecast Accuracy, Net Error, ABS Error.
- Risk Factor analysis.
- Accuracy vs Net Error Trend analysis.
- Key Metrics for both Customer and Products based on FA%, FA% LY, Net Error, Net Error%, Risk Factor.
  
  ![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/226525df-ab9b-4112-bc5b-66c2fa769a52)

✔ Executive View :

- Report Page for the Top Level Management of the Company who want to check on all key metrics and KPIs.
- Market Share Trend analysis for AtliQ and other competitors.
- Revenue analysis by Division and Channel.
- Top 5 Products and Top 5 Customers by Revenue.
- Key Insights by Sub Zone with Revenue Contribution % analysis.
  
![image](https://github.com/arun10ak/Business-Insights-360/assets/117892039/ece6bb19-c89d-4334-9c87-a0a8de5480a0)




### Tools Used:
- MS Excel
- MySQL
- Power BI
  




