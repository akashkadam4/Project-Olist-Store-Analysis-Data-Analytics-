# Project-Olist-Store-Analysis-Data-Analytics-

# Introduction

Olist is a Brazilian startup that operates in the e-commerce segment , mainly through the marketplace. It is well spread within the country. This project is a detailed analysis on the comprehensive Olist data. The original Olist dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. The schema of the dataset is as below:-

![image](https://user-images.githubusercontent.com/103564871/233910024-42caa9b9-6040-4701-9832-a427490afc21.png)

•	olist_order_customers_dataset - This dataset has information about the customer and its location. Use it to identify unique customers in the orders dataset and to find the orders delivery location.

•	olist_geolocation_dataset - This dataset has information Brazilian zip codes and its lat/lng coordinates.

•	olist_order_items_dataset - This dataset includes data about the items purchased within each order.

•	olist_order_payments_dataset - This dataset includes data about the orders payment options.

•	olist_order_reviews_dataset - This dataset includes data about the reviews made by the customers.

•	olist_orders_dataset - This is the core dataset. Every necessary information is mapped to each order in this.

•	olist_products_dataset - This dataset includes data about the products sold by Olist.

•	olist_sellers_dataset - This dataset includes data about the sellers that fulfilled orders made at Olist.

Multiple analysis tasks are carried out on the dataset, ranging from descriptive analysis to forecasting and predictive analysis.

# KPI's:

1)Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics

2)Number of Orders with review score 5 and payment type as credit card.

3)Average number of days taken for order_delivered_customer_date for pet_shop

4)Average price and payment values from customers of sao paulo city

5)Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.

# KPI_1  Weekday Vs Weekend Payment Statistics![image](https://user-images.githubusercontent.com/103564871/233911391-dbf402af-2089-457d-bf89-f17c958a45a6.png)

