# pyspark_ETL_RDD
## Project Overview
This project demonstrates scalable big data analytics using PySpark on the Online Retail dataset. The project covers Spark fundamentals including RDDs, DataFrames, SparkSQL, ETL processing, aggregations, window functions, partitioning, persistence, and performance optimization.

The system performs customer analytics, product analytics, country-wise revenue analysis, and monthly sales trend analysis using distributed data processing techniques.

# Technologies Used
- Python
- PySpark
- Apache Spark
- SparkSQL
- Google Colab
- Pandas
- NumPy

# Dataset Used

Dataset:
`OnlineRetail.csv`

Main Columns:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country
# Features Implemented

## RDD Fundamentals
- RDD creation
- map()
- filter()
- count()
- take()

## Data Cleaning and ETL
- Null value handling
- Duplicate removal
- Feature engineering
- Revenue calculation

## DataFrame Operations
- Selection
- Filtering
- Sorting
- Aggregations
- GroupBy operations

## SparkSQL
- Temporary views
- SQL queries
- Revenue analytics
- Customer analysis

## Window Functions
- Customer ranking
- Revenue ranking
- Dense ranking

## Partitioning
- Repartition
- Coalesce
- Partition analysis

## Persistence
- cache()
- persist()

## Shared Variables
- Broadcast variables

## Performance Optimization
- Execution plan analysis
- Spark optimization concepts

---

# Analytics Performed

## Customer Analytics
- Top spending customers
- Customer ranking
- Revenue contribution

## Product Analytics
- Best-selling products
- Product revenue analysis

## Sales Analytics
- Monthly revenue trends
- Country-wise revenue
- Transaction analysis

