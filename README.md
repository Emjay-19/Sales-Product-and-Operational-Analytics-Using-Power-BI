# Sales-Product-and-Operational-Analytics-Using-Power-BI

## Project Overview  
Northwind Traders, a global retail company, aims to improve decision-making across sales, product performance, and operational efficiency. This project analyzes historical transactional data to uncover trends in revenue, customer behavior, product performance, and shipping operations, while identifying inefficiencies and growth opportunities.  

## Problem Statement
Northwind Traders need clear visibility into their performance across sales, products, and operations, but raw transactional data alone does not provide actionable insights. This project aims to address critical business questions by transforming data into an interactive dashboard that supports decision-making.

## Business Questions Answered
The analysis is focused on answering the following key questions:  
•	How is revenue evolving over time, and what patterns exist in order volume?  
Are there noticeable seasonal trends affecting sales?  
•	Which product categories and individual products generate the highest revenue?  
How does the discontinuation of products impact overall sales performance and potential revenue opportunities?  
•	Which customers contribute the most to revenue, and which countries or regions represent the largest market share?  
•	How efficient are shipping operations in terms of delivery time and cost?  
Do higher freight costs result in faster deliveries?  
•	Which employees handle the most orders and generate the highest revenue?  
Which shipping companies provide the best balance between cost and performance?  

By addressing these questions, the dashboard provides a comprehensive view of business performance, helping stakeholders identify growth opportunities, optimize operations, and improve strategic decision-making.

## Tools and Methodology  
   Tools Used  
i.	Power BI for data visualization and dashboard design
ii.	Power Query for data cleaning and transformation
iii.	DAX (Data Analysis Expressions) for calculated measures

    Methodology  
To prepare the data for analysis, a series of transformation and modeling steps were carried out:  
•	Performed data cleaning in Power Query (handling missing values, correcting data types, and removing inconsistencies)  
•	Created a centralized Fact Table by combining transactional data from Orders and Order Details  
•	Built supporting Dimension Tables (Customers, Products, Employees, Shippers, Categories)  
•	Established relationships between fact and dimension tables using a star schema model  
•	Developed a Calendar Table to enable time-based analysis (YoY, monthly trends, seasonality)  
•	Created calculated columns, including:  
      - Shipping Days  
      - Delivery Delay  
      - Shipping Days Bucket  
•	Designed DAX measures for key metrics such as:  
o	Total Revenue
o	Total Orders
o	Average Order Value
o	Profit Margin
o	Discount Loss
o	Freight Cost
o	Year-over-Year Growth

Dashboard

<img width="509" height="283" alt="Screenshot 2026-04-29 203101" src="https://github.com/user-attachments/assets/6cfa777a-8228-403e-b8c2-a44510e1048e" />

<img width="506" height="285" alt="Screenshot 2026-04-29 203210" src="https://github.com/user-attachments/assets/4ac882b3-cdce-4bf4-8d7e-05b097aca443" />

<img width="505" height="281" alt="Screenshot 2026-04-29 203234" src="https://github.com/user-attachments/assets/862c84f2-5382-4366-8c09-50d5eb31497e" />

