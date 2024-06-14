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
