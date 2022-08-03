# Market-Basket-Analysis
Market Basket Analysis to identify association rules using transaction data

## Methodology
This analysis is focused on understanding the product association patterns seen in the transactions of an online retail store. The following steps are covered in this analysis:
- Data Cleaning
- Data Preparation
- Product association using Apriori algorithm for Frequent Itemset generation
- Product association using FP Growth algorithm for Frequent Itemset generation

Product association rules have been evaluated using Lift and Confidence metrics.

## Dataset
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

<b>Source citation</b>: Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17)

<b>Link</b>: http://archive.ics.uci.edu/ml/datasets/Online+Retail

<b>Dataset description</b>:
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.
