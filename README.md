# Sales-Product-and-Operational-Analytics-Using-Power-BI

## Project Overview  
Northwind Traders, a global retail company, aims to improve decision-making across sales, product performance, and operational efficiency. This project analyzes historical transactional data to uncover trends in revenue, customer behavior, product performance, and shipping operations, while identifying inefficiencies and growth opportunities.  

## Problem Statement
Northwind Traders need clear visibility into their performance across sales, products, and operations, but raw transactional data alone does not provide actionable insights. This project aims to address critical business questions by transforming data into an interactive dashboard that supports decision-making.

## Business Questions Answered
The analysis is focused on answering the following key questions:  
- How is revenue evolving over time, and what patterns exist in order volume?  
- Are there noticeable seasonal trends affecting sales?  
- Which product categories and individual products generate the highest revenue?  
- How does the discontinuation of products impact overall sales performance and potential revenue opportunities?  
- Which customers contribute the most to revenue, and which countries or regions represent the largest market share?  
- How efficient are shipping operations in terms of delivery time and cost?  
- Do higher freight costs result in faster deliveries?  
- Which employees handle the most orders and generate the highest revenue?  
- Which shipping companies provide the best balance between cost and performance?  

By addressing these questions, the dashboard provides a comprehensive view of business performance, helping stakeholders identify growth opportunities, optimize operations, and improve strategic decision-making.

## Tools and Methodology   

- **Tools Used:**  
i.	Power BI for data visualization and dashboard design  
ii.	Power Query for data cleaning and transformation  
iii.	DAX (Data Analysis Expressions) for calculated measures  

- **Methodology:**  
To prepare the data for analysis, a series of transformation and modeling steps were carried out:  
i. Performed data cleaning in Power Query (handling missing values, correcting data types, and removing inconsistencies)  
ii. Created a centralized Fact Table by combining transactional data from Orders and Order Details  
iii. Built supporting Dimension Tables (Customers, Products, Employees, Shippers, Categories)  
iv. Established relationships between fact and dimension tables using a star schema model  
v. Developed a Calendar Table to enable time-based analysis (YoY, monthly trends, seasonality)  
vi. Created calculated columns, including:  
      - Shipping Days  
      - Delivery Delay  
      - Shipping Days Bucket  
vii. Designed DAX measures for key metrics such as:  
      - Total Revenue  
      - Total Orders  
      - Average Order Value  
      - Profit Margin  
      - Discount Loss  
      - Freight Cost  
      - Year-over-Year Growth  

## Dashboards

<img width="509" height="283" alt="Screenshot 2026-04-29 203101" src="https://github.com/user-attachments/assets/6cfa777a-8228-403e-b8c2-a44510e1048e" />

<img width="506" height="285" alt="Screenshot 2026-04-29 203210" src="https://github.com/user-attachments/assets/4ac882b3-cdce-4bf4-8d7e-05b097aca443" />

<img width="505" height="281" alt="Screenshot 2026-04-29 203234" src="https://github.com/user-attachments/assets/862c84f2-5382-4366-8c09-50d5eb31497e" />

## Key Insights  

- **Revenue vs Order Volume:** Revenue increased significantly (+179.3% YoY) despite a decline in total orders (-33.8%). This indicates growth is driven by higher-value transactions rather than increased customer activity, creating dependency on fewer large orders.  

- **Seasonality Trends:** Sales show strong seasonal variation, with a peak in April ($176.8K) and a sharp decline in June ($36.4K). This reflects inconsistent monthly demand and potential cash flow volatility.  

- **Customer Concentration:** A small group of customers contributes a disproportionately large share of revenue, with QUICK-Stop alone generating over $110K. This highlights a high customer concentration risk.  

- **Regional Performance:** The USA and Germany dominate revenue contribution, significantly outperforming other countries such as Austria, Brazil, and France, indicating uneven geographic market penetration.  

- **Product Performance:** High-performing products such as Côte de Blaye ($141K+) and Thüringer Rostbratwurst ($80K+) drive a large portion of revenue, while overall quantity sold declined (-36.3% YoY), showing reduced volume but higher value per transaction. 

- **Discount Impact:** Discount losses increased sharply (+164.6% to $88.67K) without proportional revenue growth, indicating that discount strategies are not effectively driving additional sales and may be eroding profitability.  

- **Category Trends:** Beverages and Dairy Products are the strongest performing categories by volume (over 49K units combined), while Meat & Poultry shows significant disruption due to discontinued products.  

- **Operational Efficiency:** Freight costs increased significantly (+183.7%), while shipping time improved only slightly (-4.8%). This suggests rising logistics costs are not translating into meaningful efficiency gains.  

- **Shipping Performance:** Most deliveries occur within 3–14 days, with very few same-day deliveries, indicating limited fast-shipping capability.  

- **Shipper Performance:** United Package generates the highest revenue ($534K) but also incurs the highest freight cost ($92K), showing a trade-off between revenue contribution and cost efficiency.  

- **Employee Performance:** Employee output varies significantly, with the top performer generating $233K in revenue, highlighting imbalance in workload distribution and productivity across staff.  

## Recommendation  
**Sales & Growth:**  
- Focus on high-value customers to sustain revenue growth
- Expand into underperforming regions
  
**Product Strategy:**  
- Reassess discontinued products with strong demand  
- Optimize product mix toward high-performing categories
  
**Pricing & Discounts:**  
- Reduce excessive discounting  
- Implement data-driven discount strategies  

**Operations:**  
- Investigate rising freight costs  
- Optimize shipper selection based on cost vs speed trade-off  
- Improve fast delivery options
  
**Workforce Optimization:**   
- Balance workload across employees  
- Identify best practices from top performers  

## Link to Report  

[Power BI ]([https://www.example.com](https://app.powerbi.com/view?r=eyJrIjoiZDU5NDg2NTctMGEyNS00ZGRlLTkzNmQtOGU2MjIwYTUxMjZhIiwidCI6IjU2YjNjMjUzLTdlM2MtNDFjNC04NjEwLTc4YjIyYWNjN2E2MCJ9&pageName=22e1f0c1a858a0a300c8))


## Conclusion

This analysis provides Northwind Traders with a data-driven understanding of business performance across sales, products, customers, and operations. By leveraging insights from revenue trends, customer concentration, product performance, discount effectiveness, and operational efficiency, the business can make more informed strategic decisions.

Implementing targeted improvements based on these findings will help Northwind Traders reduce operational inefficiencies, optimize pricing strategies, diversify customer and regional exposure, and ultimately drive more sustainable and profitable growth.
