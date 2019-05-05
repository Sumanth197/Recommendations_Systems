# Recommendations_Systems



Task is to recommend a product that a user is most likely to buy next using the purchase history provided.

For the purpose of this interview test, we have provided mock data on customer purchase history from an e-commerce retail company. The 'Purchased Product' events were queried through Mixpanel's API and is exported into the file `training_mixpanel.txt`, as provided, in JSON format. Each event describes a singular product purchased by a particular user, with  descriptive attributes of the product (e.g., quantity, unit price). Transactions purchasing multiple products is denoted by `invoice_no`.
Final submission should include all relevant code used, and an output csv file. The csv file should be a M x N matrix, where M is the number of users and N is the number of products, where each entry represents the rating of product j for a given user i. A higher rating indicates that the user is more likely to purchase a product.
