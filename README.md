# Olist Customer Segmentation Model

## Background
[Olist](https://olist.com/) is an e-commerce platform that connects merchants and their products to the marketplaces of Brazil. Merchants are able to sell their products through the Olist Store and ship them directly to customers using Olist logistics partners.

## Problem Statement
Instead of analysing the entire customer base as a whole, Olist's marketing team would like to understand the behaviour of each customer segment. A customer segmentation model (RFM framework) will allow Olist to identify users and target them with differentiated and personalised marketing strategies. This will improve user engagement and retention.

## Dataset
We will be using real commercial data provided by Olist and hosted on [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce). The dataset consists of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers.

## Methodology
We will use the RFM framework to build our customer segmentation model. RFM stands for Recency, Frequency, Monetary Value. This would allow us to create the following segments:

Low Value: Customers who are less active than others, not very frequent buyers and generate very low revenue.

Mid Value: In the middle of everything. Uses the platform fairly frequently and generates moderate revenue.

High Value: The group we don’t want to lose. High Revenue, Frequency and Low Inactivity.

## Summary of Low, Mid and High segments
Mean values for each segment
|      | Inactive days | Number of orders | Payment value |
|------|:-------------:|:----------------:|:-------------:|
| Low  |     310.75    |       1.11       |     165.57    |
| Mid  |     84.22     |       1.39       |     244.52    |
| High |     97.03     |       5.35       |    2710.88    |

## Next steps
Each customer segment needs to be targeted differently:

High value: Maintain share of wallet. This can be done by personalising the shopping experience and introducing exclusive rewards to promote loyalty and advocacy.

Mid value: The mid segment (1.39 orders) has a much lower average order frequency than the high segment (5.35 orders). We should focus on improving frequency among mid value customers. Conduct A/B testing at various points of the customer journey (eg. search, product page) to improve conversion rate. We can also investigate if customers have had a bad experience which is deterring them from purchasing more frequently. Addressing these pain points will be crucial in driving frequency.

Low value: This group has very high platform inactivity, averaging at 310 inactive days. Awareness may be an issue with this group. Invest in paid ads, content marketing and organic social media posts to improve general awareness about Olist and its value proposition. After which, introduce gamification to encourage habitual platform use.