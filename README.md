# Kafka-Stock-Market-Project

# 📈 Stock Market Real-Time Data Engineering Project

This project simulates a real-time data engineering pipeline using Apache Kafka and AWS services. It demonstrates how stock market data can be ingested, streamed, stored, cataloged, and queried in real time.

## 🚀 Project Overview

The goal of this project is to build an end-to-end streaming architecture that mimics a stock market data feed, processes it in real time using Kafka, stores the data in Amazon S3, and allows analytics using AWS Athena.

## 🔧 Tech Stack

- **Apache Kafka** – For real-time data streaming
- **Python** – Kafka producer & consumer scripts
- **AWS S3** – Data lake to store the stream
- **AWS Glue** – For data cataloging and ETL jobs
- **AWS Athena** – To run SQL queries on the stored data
- **Docker (optional)** – For local Kafka setup

## 📌 Features

- Real-time streaming of stock market data
- Kafka producer simulates a live stock ticker
- Kafka consumer writes incoming data to AWS S3 in JSON/CSV format
- AWS Glue crawler automatically catalogs S3 data
- Serverless querying using AWS Athena
- Scalable architecture following best practices in data engineering

## 📂 Project Structure

```bash
.
├── kafka_producer.py         # Sends real-time stock data to Kafka
├── kafka_consumer.py         # Reads from Kafka and uploads to S3
├── stock_data/               # Sample data folder
├── glue_catalog_config/      # AWS Glue configuration
├── athena_queries/           # Sample SQL queries
└── README.md
