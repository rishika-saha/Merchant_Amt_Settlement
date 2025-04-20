# Merchant_Amt_Settlement

UPI Transactions Real Time CDC Feed Processing (Industrial Project)
       -> Tech Stack - Databricks, Spark Structured Streaming, Delta Lake
       -> Create Source Delta table to ingest mock UPI Transactions data based on Update Merge query
       -> Enable CDC Feed on Source Delta table
       -> Create Spark structured streaming code to consume CDC feed from Source Delta table
       -> Run aggregations on micro batches to update target delta table with Merge query to keep latest aggregated data for merchant payment settlement
       -> Query target delta table using SQL Data Warehouse Serverless Compute

Merchant Amount Settlement using Change Data Capture
