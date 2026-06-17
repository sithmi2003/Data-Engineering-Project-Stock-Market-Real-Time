# Data-Engineering-Project-Stock-Market-Real-Time

# 📈 Real-Time Stock Market Data Pipeline Using Kafka and AWS

## Overview

This project demonstrates a real-time data engineering pipeline for processing stock market data using Apache Kafka and AWS services.

The pipeline streams stock market data through Kafka producers and consumers, stores the data in Amazon S3, and enables querying through Amazon Athena.

---

## Technologies Used

- Python
- Apache Kafka
- AWS EC2
- Amazon S3
- Amazon Athena
- Pandas
- Jupyter Notebook

---

## Architecture

Stock Data Source
↓
Kafka Producer
↓
Apache Kafka Topic
↓
Kafka Consumer
↓
Amazon S3
↓
Amazon Athena
↓
Analysis and Reporting

---

## Features

✔ Real-time data streaming

✔ Kafka Producer and Consumer

✔ AWS S3 Storage

✔ Querying using Amazon Athena

✔ Data Analysis with Pandas

---

## Project Workflow

### Step 1: Producer

Streams stock market data to Kafka topics.

### Step 2: Kafka Topic

Acts as a message broker.

### Step 3: Consumer

Reads messages from Kafka and stores them in Amazon S3.

### Step 4: Athena

Queries the data directly from S3.

---

Sithmi Maheema
