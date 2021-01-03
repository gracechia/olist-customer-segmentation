# Olist Customer Segmentation Model (WIP)

## Background
[Olist](https://olist.com/) is an e-commerce platform that connects merchants and their products to the marketplaces of Brazil. Merchants are able to sell their products through the Olist Store and ship them directly to customers using Olist logistics partners.

## Problem Statement
Instead of analysing the entire customer base as a whole, Olist's marketing team would like to understand the behaviour of each customer segment. A customer segmentation model (RFM framework) will allow Olist to identify users and target them with differentiated and personalised marketing strategies. This will improve user engagement and retention.

## Dataset
We will be using real commercial data provided by Olist and hosted on [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce). The dataset consists of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers.

## Methodology
We will use the RFM framework to build our customer segmentation model. RFM stands for Recency, Frequency, Monetary Value. This would allow us to create the following segments:

Low Value: Customers who are less active than others, not very frequent buyer/visitor and generates very low - zero maybe negative revenue.
Mid Value: In the middle of everything. Often using our platform (but not as much as our High Values), fairly frequent and generates moderate revenue.
High Value: The group we don’t want to lose. High Revenue, Frequency and low Inactivity.