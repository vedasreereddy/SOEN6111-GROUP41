# SOEN6111-GROUP41
SOEN6111

**1. PROJECT DEFINITION :** 

Recent economic and social changes have dramatically affected the retail industry, especially in the way that customers and retail businesses interact with one another. The retail sector previously concentrated on promoting the products without having in-depth understanding of the clients who used the products. Consumers are no longer being drawn to buy things by generic mass marketing messaging. Retail stores must be original and creative in order to compete in the market of today. But forecasting this is a challenging issue. Retail businesses must think creatively and proactively to meet the requirements and expectations of their customers in order to succeed in the competitive market of today. Through the use of machine learning techniques, this project will estimate whether the customer will buy something again from the online shop in the next quarter. This will be accomplished by looking at the sales history. When consumers are about to make a purchase, these predictions will help retailers to personalize their discount offers. In turn, this project will assist retailers in implementing sustainable practices in product manufacturing.

**2. DATASET DESCRIPTION :**

"Online Retail II" is a dataset available on the UCI Machine Learning Repository. It is a subset of the larger "Online Retail" dataset, which contains all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The "Online Retail II" dataset contains transactions from 01/12/2009 to 09/12/2011. The features and their type included in the "Online Retail II" dataset are:

InvoiceNo: a unique identifier for each transaction with 28816 records : alphanumeric, categorical
StockCode: a unique identifier for each product with 4632 records : alphanumeric, categorical
Description: a description of each product with 4682 records : alphanumeric, categorical
Quantity: the number of each product sold in the transaction  : integer, numerical
InvoiceDate: the date and time of the transaction : timestamp, temporal
UnitPrice: the price of each product : float, numerical
CustomerID: a unique identifier for each customer : alphanumeric, categorical
Country: the country where the customer resides : alphanumeric, categorical

**3. RESEARCH QUESTIONS:**

1. Can we predict future sales revenue for the online retailer based on historical sales data, such as transaction date, customer ID, and product purchases?
2. Can we predict which customers are likely to make repeat purchases for the next quarter?
3. What customer behavioral patterns can be derived from the selected dataset?

For the given dataset, the following class of models and algorithms will be applied:

1. Regression models: such as linear regression & logistic regression will be used to predict future sales revenue based on historical sales data.

2. Classification models: such as logistic regression, decision trees, and random forest can be used to predict which customers are likely to make repeat purchases in the next quarter.

3. Clustering models: such as k-means will be used to segment customers based on their behavior and purchase history.




