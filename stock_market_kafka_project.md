# Real-Time Stock Market Data Engineering Project with Kafka

## Overview
This project demonstrates an **End-to-End Data Engineering Pipeline** for processing real-time stock market data using Apache Kafka and AWS services. The goal is to simulate the ingestion, storage, and analysis of live stock market data, showcasing a practical real-time data engineering workflow.

## Architecture
The project architecture involves data ingestion, processing, storage, and querying layers.  
<img src="Architecture.jpg" alt="Project Architecture">

### Workflow:
1. Real-time stock market data is ingested using **Apache Kafka**.
2. Data is streamed to **AWS S3** for storage.
3. **AWS Glue Crawler** catalogs the data.
4. **AWS Athena** is used to query and analyze the stored data.
5. **Python scripts** manage data streaming, transformation, and orchestration.

## Technologies Used

- **Programming Language:** Python
- **Apache Kafka** – Real-time data streaming
- **Amazon Web Services (AWS):**
  - **S3:** Storage of streaming data
  - **Glue Crawler & Catalog:** Automated schema detection and metadata management
  - **Athena:** Querying and analysis
  - **EC2:** Hosting Kafka producers/consumers or scripts

## Dataset
You can use any stock market dataset of your choice. The focus of this project is on **building a robust real-time data pipeline**, rather than the dataset itself.

## Key Features
- Real-time data ingestion and processing
- Scalable architecture with AWS and Kafka
- Queryable storage using Athena
- Automated metadata management via Glue

## How to Run
1. Start your Kafka cluster (locally or on EC2).
2. Launch the Python Kafka producer to send stock market data.
3. Configure AWS S3 bucket and Glue Crawler.
4. Stream data into S3 and verify using Athena queries.

