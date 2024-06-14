# -SQL-Explore-Ecommerce-Dataset
# I. Introduction 
This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.
# II. Requirement
- Google Cloud Platform account
- Project on Google Cloud Platform
- Google BigQuery API enabled
- SQL query editor or IDE
# III. Dataset access 
The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:

- Log in to your Google Cloud Platform account and create a new project.
- Navigate to the BigQuery console and select your newly created project.
- In the navigation panel, select "Add Data" and then "Search a project".
- Enter the project ID "bigquery-public-data.google_analytics_sample.ga_sessions" and click "Enter".
- Click on the "ga_sessions_" table to open it.
- [Table Schema](https://support.google.com/analytics/answer/3437719?hl=en)
- [Format Element](https://cloud.google.com/bigquery/docs/reference/standard-sql/format-elements)
# IV. Exploring the Dataset
In this project, I will write 08 query in Bigquery base on Google Analytics dataset  
**Query 01: Calculate total visit, pageview, transaction and revenue for January, February and March 2017 order by month**  
SQL code:  
<img width="515" alt="Screenshot 2024-06-14 at 21 21 46" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/112e3f45-651b-4f61-b33d-dbd8d7076779">  
Query result:  
<img width="632" alt="Screenshot 2024-06-14 at 21 22 32" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/c5879e88-7a50-4c15-9a65-e16c1d6844b5">  
**Query 02: Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)**  
SQL code:  

<img width="535" alt="Screenshot 2024-06-14 at 21 53 43" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/70e331a7-add4-467a-b6eb-c257943f6eed">  

Query result:  
<img width="637" alt="Screenshot 2024-06-14 at 21 54 50" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/048a6f21-ad24-4544-90d8-4c694518ab9b">  

**Query 3: Revenue by traffic source by week, by month in June 2017**  
SQL code:  
<img width="553" alt="Screenshot 2024-06-14 at 21 59 28" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/4d27d395-8385-40e5-89ea-b7255e7b58f4">
Query result:  
<img width="788" alt="Screenshot 2024-06-14 at 21 59 42" src="https://github.com/SteffanyTruong/-SQL-Explore-Ecommerce-Dataset/assets/171953683/34a9f758-d11e-420b-8c90-da0cb09dd59b">  
**Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017**  
SQL code:  
Query result:  
**Query 05: Average number of transactions per user that made a purchase in July 2017**  
SQL code:  
Query result:  
**Query 06: Average amount of money spent per session. Only include purchaser data in July 2017**  
SQL code:  
Query result:  
**Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.**  
SQL code:  
Query result:  
**Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. For example, 100% product view then 40% add_to_cart and 10% purchase.
Add_to_cart_rate = number product  add to cart/number product view. Purchase_rate = number product purchase/number product view. The output should be calculated in product level**


