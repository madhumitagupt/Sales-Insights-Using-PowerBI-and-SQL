# Atliq-Hardware-Sales-Insights-Using-PowerBI-and-SQL

## Problem Statement

AtliQ hardware is a company which delivers computer hardware & peripheral Manufacturers to his clients, which has several branches throughout India. The sales director of the company is facing a lot of issues in terms of understanding how the business is performing and what are all the problem company is facing currently as the sales are not as expected and declining gradually. And whenever he calls the regional managers to get the current status of the sales and market, as a human behaviour, these people Humans are not comfortable in consuming numbers from excel files, which is obvious reason for the frustration.Right now, they don't have a good grasp of their sales data, which makes it hard for them to make smart decisions and plan for the future. This lack of insight makes it difficult for AtliQ to spot trends, know what customers want, manage their stock efficiently, and advertise effectively. Because of this, they are missing out on chances to grow and make more money.

To fix this, AtliQ hardware needs a solution that can clearly show their sales patterns. This way, they can use data to make decisions and improve their business. This project aims to help them boost sales, meet their financial goals, and enhance their overall performance.

## Data Discovery

**Project  Planning using AIMS Grid** -
It is a project management tool which consists of four components-

- Purpose - (What to do exactly)
- Stackholder - (Who will be involved)
- End result - (What do you want to achieve)
- Success Criteria - (Cost optimization and time save)

### AIMS Grid
1. **Purpose** :- To unlock sales insights that are not visible before for the sales them for decision support and automate them to reduced manual time spent in data gathering.

2. **Stakeholders** :- Sales Director, Marketing Team, Customer Service Team, Data and Analytics Team, IT

3. **End result** :- An automated dashboard providing quick and latest sights in order to support Data driven decision making.

4. **Success Criteria** :- Dahboard uncovering sales order insights with latest data available. Sales team able to take better decisions and prove 10% cost saving of total spend. Sales analysis stop data gathering manually in order to save 20% business time andreinvest it value added activity.


## Data Analysis using MySQL
Completed the Data discovery and then used mySQL for data analysis. SQL database dump is in db_dump.sql file above. Download db_dump.sql file to your local computer.

- Importing Data to MySQL workbench.
- Analysis of data by looking into different tables and reflecting garbage values.
- Analysis of different SQL statement on database by executing complex SQL queries.

## Data Cleaning and ETL(Extract, Transform, & Load)

In the realm of data analysis, the process of data cleaning and ETL (Extract, Transform, Load) plays a crucial role in ensuring that the data we work with is accurate, consistent, and ready for analysis. Below are the detailed steps involved in our data cleaning and ETL process:

**Step 1: Connect to MySQL Database with PowerBI Desktop**- 
The journey begins by establishing a connection between our MySQL database and PowerBI Desktop. This connection serves as the bridge through which raw data is accessed, setting the stage for comprehensive analysis.

**Step 2: Load Data into Power BI Desktop**- 
During this step, all tables created within the database are loaded into Power BI Desktop. This loading process establishes a seamless connection with the SQL database, pulling in all the records and populating the Power BI environment. The integration of data from the source to Power BI is fundamental for subsequent analysis and visualization.

**Step 3: Transform Data Using Power Query**- 
The heart of the data cleaning and ETL process lies in transforming the raw data into a structured and usable format. Power Query comes to our aid, enabling us to cleanse and reshape the dataset. Through various transformations and manipulations, inconsistencies are resolved, missing values are handled, and the data is refined to align with our analytical objectives.
Once the dataset undergoes this meticulous cleaning and transformation, it emerges prepared for the next stage: data modeling. With a clean and structured dataset in hand, we are equipped to delve into advanced analytics, uncover patterns, and extract meaningful insights that drive informed decision-making.

This process ensures that the data we analyze is not just accurate but also optimized for deriving valuable insights, making it an integral part of our data analysis workflow.

## Building Dashboards or Reports

In this pivotal step, we leverage the power of Power BI Desktop to craft comprehensive dashboards and reports. Utilizing a range of Data Analysis Expressions (DAX) measures, we delve deep into data visualization, transforming raw data into actionable insights. DAX, a powerful formula language, enables us to create calculated columns, tables, and advanced measures, enhancing the granularity of our analysis.

## Insights

- In this dashboard, we can see company has generated total revenue in 4 years ₹ 985M, total profit margin ₹24.7M, Profit margin% 2.5%, Sales Qty ₹2M. in 2020 company has generated 
 total revenue of ₹ 142M by selling a total of 350K and earned a profit of ₹ 2.1M.
- In 4 years Delhi NCR is our largest market in terms of revenue with ₹ 520M and total contribution of 52.8% with total revenue but if you look at the profit margin Delhi NCR is 
 generating only 2.3% profit margin.
- If we check the profit margin then here In 2020 Bhubaneshwar comes into the picture which is generating the highest profit margin of 10.48%. Similarly, if we can check the Profit -- 
 Contribution % by Market then here Mumbai is the largest player with 23.89% of total contribution in total profit.
- In 4 years Bengaluru generating the lowest profit margin of -20.8%.if we can check the Profit Contribution % by Market then here also Bengaluru is the Lower with -0.3% of total 
 contribution in total profit.
- In our top 5 customers, the Electricalsara Stores is our biggest customer who has generated total ₹ 413 M revenue generated in 4 years.
- In our top 5 products,the Prod318 is our highest product has generated total ₹ 69M revenue generated in 4 years.
- In product type Distribution has generated the revenue of ₹494M and ownbrand revenue is ₹494M generated in entire 4 years.
- Revenue Trend is showing that in June 2020 revenue has been decreased drastically compared to the revenue last year and the profit margin was the least in April 2020.

## Tools, Softwares, and Libraries

- MySQL server and SQL workbench
- Microsoft Power BI desktop
- Power Query Editor
- DAX Language

## References

- https://codebasics.io/panel/webinars/purchases
- https://www.sqlbi.com/learn/introducing-dax-video-course/0/
- https://dev.mysql.com/doc/









