# Home Sales Data Analysis with SparkSQL

## Overview
In this project, we use SparkSQL to analyze home sales data and determine key metrics. We perform various operations such as creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying the uncaching process.



## Key Steps
1. **Data Loading:** Read the home sales data into a Spark DataFrame.
2. **Temporary Views:** Create temporary views to query the data using SparkSQL.
3. **Metrics Calculation:** Calculate key metrics such as average price per year and per property type.
4. **Data Partitioning:** Partition the data based on certain criteria to optimize query performance.
5. **Caching:** Cache the temporary table to improve query speed.
6. **Uncaching:** Uncache the temporary table when no longer needed to free up memory resources.
7. **Verification:** Verify that the temporary table has been successfully uncached.

## Results
- Analysis results including average prices, trends over time, and other key metrics.
- Query runtimes and performance improvements achieved through caching and partitioning.

## Conclusion
Using SparkSQL, we were able to gain valuable insights into the home sales data and perform various operations efficiently. By leveraging Spark's distributed computing capabilities, we achieved significant performance improvements and streamlined the data analysis process.
