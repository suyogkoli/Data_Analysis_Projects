From company’s perspective:

● shopping brand is a globally renowned brand and a prominent retailer in the United States.
shopping brand makes itself a preferred shopping destination by offering outstanding value,
inspiration, innovation and an exceptional guest experience that no other retailer can
deliver.

● This particular business case focuses on the operations of shopping brand in Brazil and provides
insightful information about 100,000 orders placed between 2016 and 2018. The
dataset offers a comprehensive view of various dimensions including the order status,
price, payment and freight performance, customer location, product attributes, and
customer reviews.

● By analyzing this extensive dataset, it becomes possible to gain valuable insights into
shopping brand's operations in Brazil. The information can shed light on various aspects of the
business, such as order processing, pricing strategies, payment and shipping efficiency,
customer demographics, product characteristics, and customer satisfaction levels.

The data is available in 8 different csv files:
1. customers.csv
2. geolocation.csv
3. order_items.csv
4. payments.csv
5. reviews.csv
6. orders.csv
7. products.csv
8. sellers.csv

I. Import the dataset and do usual exploratory analysis steps like checking the
structure & characteristics of the dataset.
  A. Data type of all columns in the “customers” table.
  B. Get the time range between which the orders were placed.
  C. Count the Cities & States of customers who ordered during the given period.
______________________________________________________________________________
II. In-depth Exploration:
  A. Is there a growing trend in the no. of orders placed over the past years?
  B. Can we see some kind of monthly seasonality in terms of the no. of orders being
  placed?
  C. During what time of the day, do the Brazilian customers mostly place their
  orders? (Dawn, Morning, Afternoon or Night)
  ● 0-6 hrs : Dawn
  ● 7-12 hrs : Mornings
  ● 13-18 hrs : Afternoon
  ● 19-23 hrs : Night
______________________________________________________________________________
III. Evolution of E-commerce orders in the Brazil region:
  A. Get the month on month no. of orders placed in each state.
  Hint: We want you to get the no. of orders placed in each state, in each month
  by our customers.
  B. How are the customers distributed across all the states?
______________________________________________________________________________
IV. Impact on Economy: Analyze the money movement by e-commerce by looking at
order prices, freight and others.
  A. Get the % increase in the cost of orders from year 2017 to 2018 (include
  months between Jan to Aug only).
  B. Calculate the Total & Average value of order price for each state.
  C. Calculate the Total & Average value of order freight for each state.
_____________________________________________________________________________________
V. Analysis based on sales, freight and delivery time.
  A. Find the no. of days taken to deliver each order from the order’s purchase date
  as delivery time.
  Also, calculate the difference (in days) between the estimated & actual delivery
  date of an order.
  Do this in a single query.
  ● time_to_deliver = order_delivered_customer_date -
  order_purchase_timestamp
  ● diff_estimated_delivery = order_estimated_delivery_date -
  order_delivered_customer_date
  B. Find out the top 5 states with the highest & lowest average freight value.
  C. Find out the top 5 states with the highest & lowest average delivery time.
  D. Find out the top 5 states where the order delivery is really fast as compared to
  the estimated date of delivery.
  You can use the difference between the averages of actual & estimated delivery
  date to figure out how fast the delivery was for each state.

______________________________________________________________________________
VI. Analysis based on the payments:
  A. Find the month on month no. of orders placed using different payment types.
  B. Find the no. of orders placed on the basis of the payment installments that have
  been paid.
