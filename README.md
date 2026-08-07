
# AdventureWorks Sales and Customer Analysis
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/Adventure_works_logo.png)
--

## Project Overview

Behind every sales figure is a customer choice, a product preference, and a business decision.

This project explores AdventureWorks sales and customer data from 2015 to 2017 using a two-page Power BI dashboard. The first page focuses on sales performance, while the second examines customer behaviour and demographics.

The goal was not simply to display revenue and order figures, but to understand what was driving performance, which customers and products contributed the most value, and where management might need to investigate further.


## Business Problem

AdventureWorks management needed a clearer understanding of sales and customer performance between 2015 and 2017.

Although the company had data on customers, orders, products, revenue, and geographic markets, it was difficult to see how these areas were performing together and whether business activity was translating into stronger revenue performance.

The analysis was therefore designed to evaluate revenue and order trends, assess performance against the revenue target, identify the products, categories, and markets contributing most to sales, and understand whether changes in the customer base were associated with changes in overall performance.

## Business Questions

1. How did customers, orders, total revenue, and average revenue change from 2015 to 2017?

2. How did product-category performance change as overall revenue declined?

3. Which products generated the most revenue in each year?

4. Which countries generated the highest revenue in each year, and did the leading market change?

5. How did monthly revenue patterns change across the three years?

6. Did the size or composition of the customer base change alongside the decline in revenue?

# DATA SOURCING
 This dataset was gotten from Kaggle.com, a website which offers a vast repository of datasets which can be used for personal projects and competitions for data enthusiasts and professionals

 ## Data Preparation and Modelling

Before building the dashboards, the data was prepared in Power Query to improve its structure and reliability. The process included:

- Importing the CSV files into Power BI
- Removing unnecessary columns and duplicate records
- Correcting column names and data types
- Appending the yearly sales tables into one consolidated table
- Creating additional columns where required
- Building a calendar table for time-based analysis
- Reviewing and adjusting table relationships to support accurate filtering
- Creating DAX measures for revenue, orders, customers, targets, and other KPIs
  
## Skills Demonstrated

- Data cleaning and transformation using Power Query
- Relational data modelling
- DAX measure and KPI development
- Sales and customer analysis
- Time-based and geographic analysis
- Interactive design 
- Business insight communication

 ## Data Model
 The dataset has nine tables;
   * AdventureWorks_Customers
   * AdventureWorks_Product_category
   * AdventureWorks_Product_Subcategory
   * AdventureWorks_Product
   * AdventureWorks_Returns
   * AdventureWorks_Sales_2015
   * AdventureWorks_Sales_2016
   * AdventureWorks_Sales_2017
   * AdventureWorks_Territory

  The model below shows the relationships between the tables used for the analysis across both dashboards.
 --- 
  ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/model_view.png)
--- 

# ANALYSYS AND VISUALISATION 

The two-page Power BI report was analysed across 2015, 2016, and 2017 to understand how sales performance, products, geographic markets, and customer patterns changed over time.

The Sales Analysis dashboard focuses on revenue, orders, products, categories, countries, and monthly performance, while the Customer Analysis dashboard provides additional context on customer growth and composition.

---

 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_dashboard_2015.png)

---
 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_dashboard_2015.png)     

---

1. How did customers, orders, total revenue, and average revenue change from 2015 to 2017?

Finding: Customer numbers increased from 2,630 in 2015 to 9,133 in 2016 and 10,502 in 2017. Orders followed the same upward trend, rising from 2,630 to approximately 11,000 and 12,000 respectively.

Despite this growth, total revenue declined from about $6 million in 2015 to $4 million in 2016 and $2 million in 2017. Average revenue also dropped sharply from $2,435 to $395 and then $149. The $5 million revenue target was achieved only in 2015.

Interpretation: AdventureWorks was gaining customers and processing more orders, but the increase in activity was not translating into stronger revenue. The sharp decline in average revenue suggests that later sales were generating less value on average. This makes product performance, geographic contribution, monthly trends, and customer behaviour important areas to investigate further.

2. How did product-category performance change as overall revenue declined?

Finding: Bikes remained the main revenue-generating category across all three years, but revenue from bikes fell sharply—from about $6.4 million in 2015 to $4.0 million in 2016 and about $1.5 million in 2017. Accessories and clothing appeared as additional revenue sources in 2016 and 2017, but their contribution remained much smaller.

Interpretation: The decline in overall revenue was closely reflected in the performance of the bike category. Although the product mix became broader, growth in accessories and clothing was not enough to offset the drop in bike revenue.


3. Which products generated the most revenue in each year?
   
Finding: In 2015, the top five revenue-generating products were Road-150 models, led by Road-150 Red, 48 at approximately $641K. In 2016, Mountain-200 models became the leading products, with Mountain-200 Silver, 46 generating about $342K. Mountain-200 products remained dominant in 2017, led by Mountain-200 Black, 38 at approximately $121K.

Interpretation: The leading product family shifted from Road-150 models in 2015 to Mountain-200 models in 2016 and 2017. At the same time, revenue generated by the top products declined considerably. This suggests that the change in product mix is an important area to investigate when assessing the overall decline in revenue.

4. Did the size or composition of the customer base change alongside the decline in revenue?

Finding: The customer base grew substantially, from 2,630 customers in 2015 to 9,133 in 2016 and 10,502 in 2017. Despite this growth, the overall customer profile remained fairly stable. The gender split stayed close to 50/50 across all three years, while customers in the average- and low-income groups continued to make up the largest share. Customers with bachelor’s degrees and partial college education also remained the largest education groups.

Interpretation: AdventureWorks was reaching a much larger customer base, but there was no major shift in customer composition that clearly explains the decline in revenue. This suggests that the revenue problem was more likely connected to factors such as product performance, purchasing patterns, or market-level differences rather than a significant change in who the company was selling to.

---
RECOMMENDATION AND CONCLUSION
---
* Following the  monthly trend,sales gradually increases as the year begins and peaks up at June while gradually decreasing afterwards,more investigation needs to be done by the sales team to find out why in order to improve sales during the months of low sales and how to optimize and further boost revenue during May/June.
* From product category,bikes generated the most revenue across the three years especially Road-150,Red 48 in 2015,thus there is need to constantly ensure the bikes in demand are always stocked up and readily available for purchase and delivery to the customers.
* Europe had the most customers but it generated lesser revenue compared to Australia which generated the most revenue with lesser customers.This should be looked into by the marketing team in order promote advertisement of the company's product in thise areas.
* Finally, since majority of the customers are average income earners the prices of the products should be looked into to ensure that the target market can afford the products. 
