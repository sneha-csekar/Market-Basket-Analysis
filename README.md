# Market-Basket-Analysis
Market Basket Analysis to identify association rules using transaction data

## Description
This analysis is focused on understanding the product association patterns seen in the transactions of an online retail store. The following steps are covered in this analysis:
- Data Cleaning
- Data Preparation
- Product association using Apriori algorithm for Frequent Itemset generation
- Product association using FP Growth algorithm for Frequent Itemset generation

Product association rules have been evaluated using Lift and Confidence metrics.

## Dataset
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.
