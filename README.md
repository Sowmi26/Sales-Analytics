## Business Problem:
AtliQ Hardware is a company manufacturing Hardware components like Personal Computers, laptops, mouse etc.  As their business is expanding, the amount of data generated is also expanding, so the Business leaders of the company decided to adopt Data Analytics into their company.  In this project, I have built reports like Sales and Finance Analytics for better decision-making.

## Business Model:
Atliq reaches its end consumers through two different platforms: Brick-and-mortar stores and e-Commerce.  
They have three different channels for product distribution:  
  Retailer - Croma, Amazon
  Direct - AtliQ exclusive, AtliQ e-store
  Distributors - NEPTUNE 

 ## Requirements:
**1. Customer Performance Report:** 
     Comparing the Net Sales of each customer for the years - 2019, 2020, 2021.
**2. Market Performance Report:**
     Comparing the Net Sales across different countries for the years - 2019, 2020, 2021, comparing target vs actual Net Sales.
**3. Profit & Loss(P&L) statement:**
     This report should provide Net Sales along with key metrics like COGS, Gross Margin, and GM% for yearly, monthly, and quarterly.

## Methodology:
1. **Data collection:**  Datasets containing three dimensions tables - dim_customers, dim_product, dim_market, and a fact table - fact_sales_monthly
2. **ETL(Extract, Transform, Load):**
     Extract .csv files into Excel,
     Transforming the data to identify and correct inaccuracies, inconsistencies, and errors in data using Power Query,
     Reload the data into Excel for data modeling and analysis.
3. **Data Modelling:** Using a Star schema, I have created relationships between the dimensions and the fact table in Power Pivot.
4. **Data Analysis / Report Generation:** Based on the given requirement, the reports are generated to help the stakeholders to make better business decisions.

## Report 1- Sales Analytics:
**Customer Performance Report:**
- The YoY Net Sales data provides a baseline to measure current performance against past results
- It also helps with Performance monitoring and to set realistic and informed sales targets.
- To identify which customers generate more revenue, so the business can explore more opportunities for upselling or cross-selling.

**Market Performance Report:**
- To identify High-performing markets to allocate strategic resources to increase profit, and implement different strategies to recover underperforming markets.
- Helps marketing teams to implement targeted marketing campaigns to improve ROI.

## Report 2 - Finance Analytics
**P&L Report:**
- The P&L is a critical tool for creating and adjusting budgets
- To track business performance towards its financial goals.
- As it covers COGS and other expenses, it helps in expense management.
- By understanding the gross margin, businesses can assess if current pricing structures are sufficient to cover operating expenses and generate desired profit levels.

## Technical skills:
- Power Query - To extract and transform data
- Power Pivot - For Data Modelling
- Dax - To create measures for calculating YoY growth %, Actual vs Target Net Sales, Growth Margin and other business metrics
- Pivot Table - For report generation

## Contact:
[LinkedIn](https://www.linkedin.com/in/sowmiyamuralidharan/)


