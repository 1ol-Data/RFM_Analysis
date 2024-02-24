# RFM_Analysis
RFM is a method used for analyzing customer value, creating customer segments. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries.

RFM stands for the three dimensions:

Recency : How recently did the customer purchase? / What is the last time of shopping?
Frequency : How often does the customer purchase?
Monetary Value : How much does the customer spend?

Steps:

Find R, F and M values
Calculating RFM Scores
Creating segments based on RFM scores --> That defines customer behavior
Develop marketing strategies for each customer segment
Business Problem
An e-commerce company wants to segment its customers and determine marketing strategies according to these segments.

For this purpose, we will define the behavior of customers and create groups according to clustering in these behaviors.

In other words, we will include those who display common behaviors to the same groups and we will try to develop sales and marketing techniques specific to these groups.

Data set story

https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

The data set named Online Retail II includes the sales of a UK based online store between 01/12/2009 - 09/12/2011.

This company sells souvenirs. It can be thought as promotional products.

Most of their customers are wholesale traders.

Variables:

InvoiceNo: Invoice number. The unique number for each transaction i.e. invoice. If this code starts with C, it indicates that the transaction has been canceled.
StockCode: Product code. Unique number for each product.
Description: Product name
Quantity: Number of items. It expresses how many products in the invoices are sold.
InvoiceDate: Invoice date and time.
UnitPrice: Product price (in Pounds)
CustomerID: Unique customer number
Country: Country name. The country where the customer lives.
Customer Segmentation with RFM Scores
It consists of the initials of Recency, Frequency, Monetary.

It is a technique that helps determine marketing and sales strategies based on customers' buying habits.

Recency: Time since the customer's last purchase

In other words, it is the time elapsed since the last contact of the customer.

Today's date - Last purchase

For example, if we are doing this analysis today, today's date - the last product purchase date.

For example, this could be 20 or 100. We know that the customer with Recency = 20 is hotter. He has been in contact with us recently.

Frequency: Total number of purchases.

Monetary: The total expenditure made by the customer.
