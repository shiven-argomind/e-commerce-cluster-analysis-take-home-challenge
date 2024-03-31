<p align="center">
    <img align="center"  src="https://static.wixstatic.com/media/0dc899_b4e5e0f319d244f58b9850f2094d6a12~mv2.png/v1/fill/w_157,h_41,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/transparent_edited.png">
</p>

# E-commerce Cluster Analysis Take Home Challenge

## Overview

Perform a Cluster Analysis on a customer order data set

## Skills Tested

EDA, Unsupervised Learning

## Deliverable

Jupyter notebook

## Dataset

| Column Name | Description                                   | Type     |
| ----------- | --------------------------------------------- | -------- |
| InvoiceNo   | Invoice number that represents a unique order | (String) |
| StockNo     | ID of the product                             | (String) |
| Description | Description of the product                    | (String) |
| Quantity    | Quantity of the product                       | (String) |
| InvoiceDate | Date of the order                             | (Date)   |
| UnitPrice   | Price of the product                          | (String) |
| CustomerID  | ID of the customer                            | (String) |
| Country     | Country of purchase based on the user's IP    | (String) |

Each row represents one line item in a single order

## Task

Perform a cluster analysis of the data that segments users into actionable groups

Use the clusters to:

1. Profile the customers based on their purchase history. These customer profiles will be used by store owners to target customers for specific marketing campaigns for e.g. targeting customers with high purchase frequency for new product launches.
2. Use the clusters to recommend new products to customers.

## Tips

1. Focus on the cluster analysis first to get a good segmentation between customers.
2. Identify underlying patterns in the clusters to create customer profiles.
3. For the recommendation system, find high selling products using the purchase history of other customers in the cluster.
4. Optionally, you can look into ranking the products recommended based on how well they sell and how much revenue they contribute to the store owners.
