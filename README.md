# Finding_valuable_customers



## Business Context
With growing demands and cut-throat competitions in the market, a Superstore Giant would like to design a customer loyalty program that strengthens its relationship with its' customers and incentivizes repeat purchases. The objective of the loyalty program is to increase customer retention and drive incremental sales by targeting customers with personalized promotional offers. The company's marketing manager has proposed to implement a tier-based marketing campaign where customers are offered cash rewards as incentives towards their first purchase following enrollment into the loyalty program. The proposed cash reward offers are as follows:

Get $200 on first purchase

Get $100 on first purchase

Get $25 on first purchase

The Superstore Giant is seeking our knowledge in identifying which customers should get what offer as this requires understanding the customers' buying behaviors. I have been provided access to the customer transaction database contained in the Superstore.csv file and asked to provide valuable insights into customer behavior by grouping customers into different segments based on their buying behavior and loyalty to the business.

In other to solve this problem, I have performed a value-based customer segmentation analysis (also known as RFM Segmentation) using customers' transaction histories to group the customer base into different value segments. The final output of my analysis is a table containing customer Ids, customer value segment and the cash reward recommendation.

As part of my effort to support the marketing team in the personalization of promotional offers, I have also developed a predictive analytics model which takes into account  the total expected profit from a customer in the value ranking. The model provide to the marketing team  how much profit could be expected from each customer in the next one year of transactions


### Dataset Overview

Below provides the description of columns contained in the Superstore.csv dataset.

Order ID: Unique Order ID for each Customer.

Order Date: Order Date of the product.

Ship Date: Shipping Date of the Product.

Ship Mode: Shipping Mode specified by the Customer.

Customer ID: Unique ID to identify each Customer.

Customer Name: Name of the Customer.

Segment: The segment where the Customer belongs.

Country: Country of residence of the Customer.

City: City of residence of the Customer.

State: State of residence of the Customer.

Postal Code: Postal Code of every Customer.

Region: Region where the Customer belongs.

Product ID: Unique ID of the Product.

Category: Category of the product ordered.

Sub-Category: Sub-Category of the product ordered.

Product Name: Name of the Product.

Sales: Sales of the Product.

Quantity: Quantity of the Product.

Discount: Discount provided.

Profit: Profit/Loss incurred.
