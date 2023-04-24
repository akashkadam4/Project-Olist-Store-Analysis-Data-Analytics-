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

# KPI_1  Weekday Vs Weekend Payment Statistics!

Weekday  sales – 79 %
Weekend sales – 22 %
# Analysis:
Most of the sales are done on weekdays. Major sales happened on Tuesdays and on the weekend it’s on Sundays. 
The highest number of payments are made through Credit card mode. 
The number of orders received on weekdays is 76k and on weekends 23k.
# Suggestion:
To increase the weekend sales we can release any special offers on the weekends or Tuesdays. Which helps to generate more revenue.

![image](https://user-images.githubusercontent.com/103564871/233911608-2bf4fbe7-e074-4624-b8d7-622f55226484.png)

# KPI_2  Number of Orders with review score 5 and payment type as credit card

With a review score of 5 and payment type as a credit card, We received 44333 orders.

# Overview:
- More orders have been placed via credit card payment than boleto, voucher, and debit card.
-  More than 70% of sales were paid by Credit Card which is the main payment method in the market. However, payment using Boleto has slightly increased by 7% and a significant increase in using a debit card has been founded.
# Suggestion:
If we want to increase sales, we can have a certain amount of discounts or no-cost EMI’s on card payments.
![image](https://user-images.githubusercontent.com/103564871/233911765-f25680bc-2dd4-44c9-a0cb-beb6fe23892f.png)

# KPI_3 Average number of days taken to deliver order for pet_shop

11 days is the avg days taken to deliver the order for pet shop.

# Overview:
- 21 days is the maximum avg days taken to deliver the order and for the product : (Office furniture).
- 5 days is the minimum avg days taken to deliver the order and for the product: artes_e_artesanato (arts and craftmanship).
- Year wise sales are increasing which means we doing good in the market.

# Suggestion:
We can work on faster delivery of the product moveis_escritorio by taking additional delivery measures.

![image](https://user-images.githubusercontent.com/103564871/233911969-1ed873ce-423d-41e5-a985-9a44f3f6feef.png)


# KPI_4  Average price and payment values from customers of sao paulo city

Sao Paulo City – Avg price is 108 and avg payment is 153
# Overview :
- The total number of customers is nearly 100K. We found out that São Paulo (SP) contains the most customers and is 3 times more than the second one. It is expected São Paulo has, particularly the most order payment value. Either Rio de Janerio (RJ) or Minas Gerais (MG) takes 10% of total customers. This indicates that the top 5 states contribute 80% of total customers.
# Suggestion:
To increase sales on other cities we can work on faster delivery and easy payment modes and product wise offers.

![image](https://user-images.githubusercontent.com/103564871/233912137-bdc4a3ff-77af-4458-bb76-5f6410390549.png)

# KPI_5  Relationship between shipping days Vs review scores.

11 avg shipping days taken for review score 5 & 20 avg shipping days taken for review score 1.
# Overview:
We get positive/high ratings when delivery time is less and negative feedback from the customers when it takes long to deliver the product.
Lesser the delivery days – the higher the positive reviews.
After analysing the review scores(customer satisfaction rating), the average score is 4.07/5, which shows positive satisfaction with Olist’s services.
# Suggestion:
Minimizing the shipping days would lead to more positive reviews. Consecutively customer satisfaction will be met which leads to more business.
![image](https://user-images.githubusercontent.com/103564871/233912371-40247d5f-6a75-43b1-9051-98ea5cc9c567.png)

# CONCLUSION

The analysis also focuses on the product categories with respect to the price and the review score of the customer. So, if the company focuses on the product’s pricing strategy and makes product improvements on the basis of consumer opinion, the company can make better revenue and can increase the range of products under each category. 

The organization needs to purposely address the purchaser's survey and continue to adjust and change the item range. Future work in this space might incorporate recognizing how connections revealed in this investigation might be applied to further develop income inside comparative internet business organizations in Brazil

