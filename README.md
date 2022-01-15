# Project 1 - SQL Queries (Part A)
**Introduction**

After trying various online SQL tutorials, I wanted to test my knowledge by working on a new dataset and try my hacking skills on some SQL queries. This project makes use of data sourced from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php), a popular repository for machine learning datasets. In particular, we will be using the ["Online Retail Data Set"](https://archive.ics.uci.edu/ml/datasets/online+retail). My interest in exploring this dataset is based on my previous work experience at ShopBack. [ShopBack](https://www.shopback.sg/) is a Singapore based ecommerce loyalty platform serving over 30 million shoppers across 9 markets in Asia Pacific. 

![ecommerce- part 1](https://user-images.githubusercontent.com/88034960/148794800-935af2c6-fbfa-46c7-9cc7-0009d7a203aa.png)


## **About the dataset** 

- **Dataset**: [Online retail.xlsx](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/) (42.2 MB)
- **Description**: This contains transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

The original xlsx file consists of 2 sheets - Year 2009-2010 & Year 2010-2011. For this project, I will be working with the data from the sheet **"Year 2009-2010" only**.

The following descriptions of the 9 variables in the dataset are taken from the [UCI web site](https://archive.ics.uci.edu/ml/datasets/online+retail):
- **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description**: Product (item) name. Nominal.
- **Quantity**: The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate**: Invoice date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
- **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country**: Country name. Nominal, the name of the country where each customer resides.

## **Installation and setup**

- We're going to be using SQLite which is a database engine that works in a single application. In order to access it we'll be using DBeaver. DBeaver is an open-source database manager that connects to almost all database engines. When downloading, select the [**DBeaver community only**](https://dbeaver.io/download/).

- After opening DBeaver and downloading the database file from the link mentioned above, create a new connection and select the option for SQLite. 

- Covert the Online retail.xlsx file to a csv file and upload it under tables in SQLite.

- The SQL queries will be shown in the Jupyter notebooks.

## Table of contents:
1. **SQL technique #1** - Counting rows, select and distinct functions
2. **SQL technique #2** - Aggregation functions
3. **SQL technique #3** - Slicing data
4. **SQL technique #4** - Sorting data
5. **SQL technique #5** - Filtering patterns



