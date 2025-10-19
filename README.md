# E-commerce-Dashboard
E-Commerce Customer Behavior Analysis

#### Scenario: 

An e-commerce platform wants to understand customer behavior by analyzing purchasing patterns, 
browsing data, and product reviews. The company aims to improve customer satisfaction and product 
offerings. 

#### Datasets: 
1. Customer Information: Includes customer ID, age, gender, location, and registration date (with 
some missing or inconsistent entries). 

2. Purchase History: Contains transaction IDs, product IDs, customer IDs, purchase date, quantity, 
and total price (with duplicates and some erroneous values). 

3. Product Reviews: Customer ratings and review texts for products, including some missing 
reviews and inconsistent rating scales.

#### Datasets

⬤ <a href="https://github.com/CelesNeba/E-commerce-Dashboard/blob/main/customers_info_clean.csv" target="_blank">
  View customers_info_clean.csv
</a>

<br>

⬤ <a href="https://github.com/CelesNeba/E-commerce-Dashboard/blob/main/ecommerce_product_reviews_clean.csv" target="_blank">
  View ecommerce_product_reviews_clean.csv
</a>

<br>

⬤ <a href="https://github.com/CelesNeba/E-commerce-Dashboard/blob/main/ecommerce_purchase_history_clean.csv" target="_blank">
  View ecommerce_purchase_history_clean.csv
</a>


#### Tasks: 
• Python: Clean and preprocess the data (handle missing values, correct data types). 

• SQL: Create a database, import the cleaned data, and run queries like finding the most 
purchased products or identifying customers with the highest lifetime value. 

• Tableau: Visualize trends such as top-selling products, regional sales distribution, and sentiment 
analysis of reviews. 


#### Phase 1: Data Cleaning with Python 

1. Import datasets using Pandas. 

2. Check for missing values, duplicates, and outliers. 

3. Standardize inconsistent formats (e.g., date formats, currency). 

4. Handle missing values using appropriate techniques (mean, median, or removal). 

5. Export the cleaned data to new CSV files.


#### Phase 2: SQL Database Integration 





1. Set up a database with Mysql. 

2. Create tables for each dataset (Customer Info, Purchase History, Product Reviews). 

3. Import cleaned CSV files into SQL tables.





![E-commerce Database & Tables](https://github.com/CelesNeba/E-commerce-Dashboard/blob/main/ecom%20database%20%26%20tables%20screnshort.png?raw=true)






#### 4. Run SQL queries: 


#### Most Purchased Product Screenshot

![Most Purchased Product](https://github.com/CelesNeba/E-commerce-Dashboard/blob/main/Most%20purchase%20product%20screenshot%20.png?raw=true)



o Top customers by lifetime value. 


o Product rating trends over time. 
