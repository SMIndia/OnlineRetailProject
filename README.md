# OnlineRetailProject
An online retail store is trying to understand the various customer purchase patterns for their firm, give enough evidence based insights to provide the same.

Project Objective:
1. Using the given data, find useful insights about the customer purchasing history that can be an added advantage for the online retailer.
2. Segment the customers based on their purchasing behaviour.

Data Description:
Feature Name       Description
InvoiceNo          Invoice Number
StockCode          Product ID
Description        Product Description
Quantity           Quantity of the product
InvoiceDate        Date of the Invoice
UnitPrice          Price of product per unit
CustomerID         Customer ID
Country            Region of Purchase

Choosing the Algorithm for the Project and reasons for choosing the Algorithm:
Strategy 1: To understand the recency, frequency and monetary value of the customer, based on their past transaction and we leverage these features as an input to k-means clustering algorithm. We will use these features to identify segments of customers.
After getting segments we will do the profiling of the customer. And identify which segment is basically the done most recent transactions, most frequent transactions, and high monetary valued transactions which can be used for developing marketing campaign strategies.
Strategy 2: To understand which products are frequently brought together, based on the transactions and leveraging these transactions data as an input to apriori (association rule) algorithm.
These lists of can be used to develop marketing strategy and manage the online display on website or application.
