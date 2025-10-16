# Amazon Stock Price Data Analysis Using AWS and Python

# Overview
This project aims to analyze Amazon’s (AMZN) historical stock price data, applying a complete data engineering and analysis workflow on AWS.
The solution was built with a focus on cloud data engineering best practices, data processing, and exploratory analysis using Python.


# Project Architecture

The data pipeline was structured to simulate a real-world cloud-based workflow:

1 - Data Ingestion:
Historical Amazon stock price data was stored in an Amazon S3 bucket.

2 - Cataloging and ETL with AWS Glue:
A table was created in the Glue Data Catalog, defining schemas and data types to facilitate queries.

3 - SQL Queries with Amazon Athena:
Athena was used to query and process the data directly from S3 using SQL.

4 - Analysis and Visualization with Python:
Pandas and Matplotlib (via Google Colab) were used to calculate metrics and visualize closing prices, moving averages, and daily variations.

5 - Data Ready for Analytical Consumption:
The processed data was prepared and validated for use in BI tools or further analytical processes.


# Analysis Goals

- Compute 7-day and 30-day moving averages to detect price trends.

- Analyze daily percentage variation of closing prices.

- Generate visualizations showing price evolution over time.

- Prepare data for future analytical layers (BI, Machine Learning, etc.).


# Tech Stack

| Category         | Tool                            | Description                                     |
| ---------------- | ------------------------------- | ----------------------------------------------- |
|    Language      | **Python (Pandas, Matplotlib)** | Data processing and analysis                    |
|    Cloud         | **Amazon Web Services (AWS)**   | Cloud infrastructure and data orchestration     |
|    Storage       | **Amazon S3**                   | Central storage for raw and processed CSV files |
|    ETL / Catalog | **AWS Glue**                    | Schema creation and data cataloging             |
|    Query Engine  | **Amazon Athena**               | Serverless SQL querying from S3                 |
|    Environment   | **Google Colab**                | Notebook environment for running Python code    |


# How to Run the Project

1 - Requirements

- AWS Free Tier account

- S3 bucket containing the dataset

- AWS Glue database and catalog configured

- Permission to run Athena queries

2 - Steps

- Upload the dataset to your S3 bucket.

- Create a table in AWS Glue Data Catalog using the correct schema.

- Use Amazon Athena to query, clean, and validate the dataset.

- Export the results and open them in Google Colab.

- Run the Python notebook to:

- Compute 7-day and 30-day moving averages

- Generate trend and variation charts


# Results

- Identified long-term upward trends using moving averages.

- Visualized volatility through daily percentage variations.

- Prepared and structured data ready for analytical consumption in BI or ML applications.
