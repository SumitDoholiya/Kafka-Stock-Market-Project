# Kafka-Stock-Market-Project

This project simulates a real-time data engineering pipeline using Apache Kafka and AWS services. It demonstrates how stock market data can be ingested, streamed, stored, cataloged, and queried in real time.

## Project Overview

The goal of this project is to build an end-to-end streaming architecture that mimics a stock market data feed, processes it in real time using Kafka, stores the data in Amazon S3, and allows analytics using AWS Athena.

## Tech Stack

- **Apache Kafka** – For real-time data streaming
- **Python** – Kafka producer & consumer scripts
- **AWS S3** – Data lake to store the stream
- **AWS Glue** – For data cataloging and ETL jobs
- **AWS Athena** – To run SQL queries on the stored data
- **Docker (optional)** – For local Kafka setup

## Features

- Real-time streaming of stock market data
- Kafka producer simulates a live stock ticker
- Kafka consumer writes incoming data to AWS S3 in JSON/CSV format
- AWS Glue crawler automatically catalogs S3 data
- Serverless querying using AWS Athena
- Scalable architecture following best practices in data engineering

## Project Structure

![Architecture](https://github.com/user-attachments/assets/9f7d1c2c-e5bd-4ae9-a73f-20aba58ee30e)


