# BigQuery

# Overview

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%201.png)

Focus on serverless compute, real time insights, machine learning instead of data placement, cluster configuration (no managing of infrastructure, nodes, clusters etc.)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%202.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%203.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%204.png)

- each value on a different disk

## **Row Oriented Databases**

Traditional Database Management Systems were created to store data. They are optimized to read and write a single row of data which lead to a series of design choices including having a row store architecture.

In a row store, or row oriented database, the data is stored row by row, such that the first column of a row will be next to the last column of the previous row.

For instance, let’s take this Facebook_Friends data:

![https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling1.png](https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling1.png)

This data would be stored on a disk in a row oriented database in order row by row like this:

![https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling2.png](https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling2.png)

This allows the database write a row quickly because, all that needs to be done to write to it is to tack on another row to the end of the data.

## **Column Oriented Databases**

Data Warehouses were created in order to support analyzing data. These types of databases are read optimized.

In a C-Store, columnar, or Column-oriented database, the data is stored such that each row of a column will be next to other rows from that same column.

Let’s look at the same data set again and see how it would be stored in a column oriented database.

![https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling8.png](https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling8.png)

A table is stored one column at a time in order row by row:

![https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling9.png](https://dataschool.com/assets/images/data-modeling-101/row_vs_col_databases/modeling9.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%205.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%206.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%207.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%208.png)

# Load and Export data

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%209.png)

When we talk about loading data to bigquery we are talking about three different things, two of them are storing data in BigQuery itself and the third one is reading from an external source not actually stored in BigQuery. Our two options are either use batch load where we can load from either cloud storage or a local computer or we can insert streaming data from streaming and processing services such as PubSub into Cloud Dataflow. You can also just read the data from an external source, which acts as if the data was actually stored in BigQuery.

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2010.png)

BigQuery transfer service - used to import data to bigquery from other google SaaS applications

(youtube)

To load data from Cloud Dataproc to BQ you can use the default connector, however is it important to note that it doesnt do it directly, it uses **Cloud Storage for a staging process**

# Optimize performance and cost

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2011.png)

Denormalize data → you make nested columns so the data is pretty much duplicated, but it is done for faster read (for example you have author:commits, author:name, which means that commits and name is nested in the author column)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2012.png)

- yellow = wait
- purple = read
- orange = compute
- blue = write

# Example

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2013.png)

# BigQuery Logging and Monitoring

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2014.png)

# BigQuery best practices

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2015.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2016.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2017.png)

![Untitled](BigQuery%207d8c30fa01194edb8d8f003dc49a0283/Untitled%2018.png)