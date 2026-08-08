
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

4. Did the size or composition of the customer base change alongside the decline in revenue?

5. How was revenue distributed across countries, and which markets generated the most revenue from 2015 to 2017?

6. How did monthly revenue patterns change from 2015 to 2017?

7. Which products or product categories were driving revenue in each country?

   
## Data Sourcing 

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
 
  ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/model_view.png)


## ANALYSYS AND VISUALISATION 

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

Interpretation: AdventureWorks was reaching a much larger customer base, but there was no major shift in customer composition that clearly explains the decline in revenue. This suggests that the revenue problem was more likely connected to factors such as product performance, purchasing patterns, or market-level differences rather than a 
significant change in who the company was selling to.

5. How was revenue distributed across countries, and which markets generated the most revenue from 2015 to 2017?

Finding: Revenue came from Australia, the United States, Canada, France, Germany, and the United Kingdom. Australia remained the highest-revenue market, generating about $2.12M in 2015, $1.63M in 2016, and $617K in 2017.

Interpretation: Revenue was spread across several markets, but Australia and the United States remained the strongest contributors across the period.

6. How did monthly revenue patterns change from 2015 to 2017?
   
Finding: Across all three years, revenue generally strengthened toward May and June, then dropped in July. In 2015 and 2016, revenue recovered toward December, though not to the mid-year peak. In 2017, revenue fell sharply after June and remained at a much lower level for the rest of the year.

Interpretation: AdventureWorks showed a recurring mid-year revenue peak followed by a July decline. However, the weak recovery in 2017 suggests a more significant change in performance than the seasonal pattern seen in the previous two years.

7. Which products or product categories were driving revenue in each country?
   
Finding: Bikes were the main revenue-driving category across the markets reviewed. In the highest-revenue countries, particularly Australia and the United States, revenue was concentrated around a few dominant bike models—Road-150 in 2015 and Mountain-200 in 2016–2017. Lower-revenue markets such as Germany showed a more varied mix of bike models.

Interpretation: AdventureWorks depended heavily on bike sales across markets, but the specific models driving revenue differed by country and over time. This suggests that product demand was not identical across markets.

## Recommendations

* Prioritise **Australia and the United States**, the strongest revenue markets.
  
* Grow lower-performing markets such as **Germany, France, Canada, and the United Kingdom** with market-specific product and promotional strategies.
  
* Maintain strong availability of **Bikes**, especially the models performing best in each country.
  
* Plan inventory and promotions around the recurring **May–June revenue peak**.

* Use **market-specific product strategies**, since model preference varied by country.
  
- Investigate why rising customer and order volumes did not translate into stronger revenue.
  
## Limitations 

* The dashboard identifies where revenue changed across customers, products, categories, time, and markets, but does not isolate deeper drivers such as pricing, quantity, discounts, or returns. These would be useful for a fuller root-cause analysis.


## Conclusion

* AdventureWorks grew its customer base and order volume, but revenue declined over the period.

* The analysis showed that Bikes remained the main revenue driver, Australia and the United States were the strongest   markets, and product demand varied across countries and over time.

* These findings give management a clearer view of where revenue is coming from and where further growth opportunities may exist.
