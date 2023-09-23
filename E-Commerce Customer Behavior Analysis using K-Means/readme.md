## About the Dataset
The dataset chosen for this analysis is the Online Retail II Data Set from the UCI Machine Learning Repository. This dataset contains transactions occurring between 01/12/2009 and 09/12/2011 for a UK-based online retailer that sells gifts primarily to consumers. The dataset has a total of 1,067,371 transactions.

The reason for selecting this dataset is that it contains transactional data for a period of two years and can be used to analyze customer behavior in an e-commerce setting. The dataset contains the following features:

InvoiceNo: Unique number assigned to each transaction StockCode: Unique number assigned to each product Description: Description of the product Quantity: The number of units of the product in the transaction InvoiceDate: The date and time the transaction was made UnitPrice: The price of one unit of the product in GBP CustomerID: Unique number assigned to each customer Country: Country where the customer resides

## Research Question
Can we segment customers based on their purchasing behavior and identify different groups of customers that have different purchasing patterns?

This is an unsupervised learning problem, as we do not have any pre-defined labels for the different groups of customers. We will use k-means clustering algorithm to group customers based on their purchasing behavior.
