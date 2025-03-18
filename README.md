# Home_Sales

### Overview

This project leverages Apache Spark and PySpark SQL to analyze home sales data efficiently. The dataset is sourced from a CSV file, processed using SQL queries, and optimized through caching and Parquet file storage for improved performance.

### Technologies Used

* Python
* PySpark (Apache Spark)
* SQL Queries
* Parquet File Format
* Jupyter Notebook

### Key Tasks

### 1. Data Loading and Preparation
* Initialize a Spark session
* Read the dataset from a CSV file
* Create a temporary SQL table

### 2. Data Analysis Using SQL
* Calculate average home prices based on bedroom count and view ratings
* Filter homes by size, number of floors, and square footage
* Identify the most expensive home sold per year

### 3. Performance Optimization
* Cache the dataset to enhance query performance
* Partition data by date_built and store it in Parquet format
* Compare execution times of cached vs. non-cached queries

# Instructions:

### 1. Install Dependencies 

*  Ensure PySpark and required packages are installed:
    * pip install pyspark findspark

### 2. Run the Jupyter Notebook 

* Execute all cells sequentially to process and analyze the data.

### 3. Verify Outputs

* Run SQL queries to extract insights from the dataset
* Use .show() to display results in a DataFrame format
* Measure and compare execution times for cached vs. non-cached queries

### File Structure

* Home_Sales_starter_code.ipynb – Main Jupyter Notebook with all analysis and queries
* home_sales_revised.csv – Dataset (sourced from AWS S3)
* home_sales_partitioned/ – Directory containing partitioned Parquet data  

### Additional Notes

* Ensure the dataset is available before running the notebook
* Modify the Parquet file output path if needed
