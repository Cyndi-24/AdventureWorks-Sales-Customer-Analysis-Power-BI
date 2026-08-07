
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
---
  This report contains two dashboard;customer and sales
  
---

 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_dashboard_2015.png)

---
 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_dashboard_2015.png)     

---
 KPI's for customer report 2015
---

![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/Average_Income_%20customer_2015.png)
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/total_customers_kpi_2015.png)


The detailed dashboard views below reflect the 2015 slicer selection. Therefore, the customer, product, geographic, and monthly findings in this section describe 2015 only and are not presented as three-year results.

---
Which gender had the most patronage?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_by_gender_2015.png)

 The females patronised the most
    
---
Which customers by educational level patronised the most?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_edu_level_2015.png)

 Bachelors 

---
Which customer by income segment patronised the most?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_income_sgt_2015.png)

Average Income Earners patronised more than other income segments

---
Which country had the most customers?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_by_country_2015.png)

Europe had the most customers

---
What are the top 5 products by revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/product_by_revenue-sales2015.png)

 Road-150,Red 48 genarated the most revenue in 2015

---

## Sales Performance Across 2015–2017
Sales Report KPI's 2015
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2015.png)
---
Sales Report KPI's 2016
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2016.png)
---
Sales Report KPI's 2017
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2017.png)


## How did sales performance change across the three years?

* Finding: Total orders increased from 2,630 in 2015 to approximately 11,000 in 2016 and 12,000 in 2017. However, total revenue declined from approximately $6 million in 2015 to $4 million in 2016 and $2 million in 2017.

Average revenue also fell from $2,435 in 2015 to $395 in 2016 and $149 in 2017. The $5 million revenue target was achieved only in 2015.

* Interpretation:The increase in order volume did not translate into stronger revenue performance. Both total revenue and average revenue declined, suggesting that the additional transactions generated lower revenue values on average.

Possible contributing factors include a shift toward lower-priced products, changes in quantities purchased, heavier discounts, returns, or changes in customer purchasing behaviour. Further year-level analysis would be required to identify the exact cause.

---
What was the revenue generated by each product category?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/product_cat_by_rev_sales2015.png)

Bikes generated the most revenue across the three years but generated the most in 2015 with 6million but there was a  decline to about  4 million in 2016 and to 1.4 million in 2017.

---
Who are the top customers by revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customers_by_revenue_sales2015.png)

---
What was the revenue generated monthly?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/monthly_trend_sales2015.png)

Over the three year period,the revenue grows gradually increases and hits its peak around June and steadily declines down the year.

---
Which country generated the most revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/revenue_by_country_2015.png)

Australia generated the most revenue

---
RECOMMENDATION AND CONCLUSION
---
* Following the  monthly trend,sales gradually increases as the year begins and peaks up at June while gradually decreasing afterwards,more investigation needs to be done by the sales team to find out why in order to improve sales during the months of low sales and how to optimize and further boost revenue during May/June.
* From product category,bikes generated the most revenue across the three years especially Road-150,Red 48 in 2015,thus there is need to constantly ensure the bikes in demand are always stocked up and readily available for purchase and delivery to the customers.
* Europe had the most customers but it generated lesser revenue compared to Australia which generated the most revenue with lesser customers.This should be looked into by the marketing team in order promote advertisement of the company's product in thise areas.
* Finally, since majority of the customers are average income earners the prices of the products should be looked into to ensure that the target market can afford the products. 
