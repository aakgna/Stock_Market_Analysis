# Stock_Market_Analysis

## Description

This is a Real Time Financial Market Analysis tool I developed to check different technical analysis and price prediction techniques. I used technologies including: Python, Amazon Web Services (AWS), Apache Kafka, AWS Glue, AWS Athena, and SQL.

## WHat is Included in this Github

1. Kafka Producer: The python script to read the financial data coming in (this is simulated by a loop) and write it to the Kafka Cluster which communicates with the Zookeeper to maintain the ETL Pipeline
2. Kafka Consumer: This data this gets read by the Consumer when writes the data into AWS S3 to store the data.
3. Analysis: Finally, the Analysis takes the code and does proper analysis to predict the price of a stock, futures, etc. There can also be other technical analysis done like calculating the RSI.

## What is not Included in this Github

1. The intermediate step of setting up Apache Kafka and the Zookeeper
2. Intermediate step between Consumer and Analysis in AWS
