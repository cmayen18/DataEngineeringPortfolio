# Real-Time Log Analytics with Apache Spark, Python, and Kafka: Leveraging NASA Kennedy Space Center WWW Server Logs for Scalable Log Analysis

## Objective
The "Real-Time Log Analytics" project aims to implement real-time log analytics for NASA's Kennedy Space Center web servers using Apache Kafka, Spark, and Cassandra. It seeks to ingest, process, and analyze log data in real-time to enhance operational efficiency and facilitate data-driven decision-making.

## Approach
This project adopts a systematic approach to real-time log analytics, leveraging technologies like Apache Kafka, Spark, and Cassandra. It involves setting up the environment, parsing and cleaning log data, ingesting data from various sources using NiFi and Kafka, loading data into Cassandra and HDFS, and finally, visualizing insights through live dashboards using Plotly and Dash.

## Implementation
- **Setting Up Environment:**
  - Creation of an EC2 instance on AWS with Docker and essential tools.
- **Data Parsing and Cleaning:**
  - Parsing and cleaning log data using Spark Streaming API.
- **Data Extraction Using NiFi:**
  - Ingesting NASA dataset into Kafka topic using NiFi.
- **Data Ingestion From NiFi to Kafka:**
  - Creating a Kafka topic and configuring NiFi dataflow for continuous data ingestion.
- **Loading Data Into Cassandra and HDFS:**
  - Writing data from Kafka topic into Cassandra and HDFS using Spark structured streaming API.
- **Data Visualization:**
  - Creating live dashboards with Plotly and Dash for real-time visualization of log data.

## Tools
- **Language:** Python
- **Tools and Technologies:**
  - Apache Kafka, Apache Spark, Cassandra, Docker, AWS EC2, Apache NiFi, HDFS, Jupyter Lab, Plotly, Dash

## Key Learnings and Outcomes
- Gain understanding of the Lambda Architecture.
- Familiarity with Docker, Kafka, NiFi, Spark, Cassandra, and HDFS.
- Hands-on experience in integrating NiFi, Kafka, and Spark.
- Visualization of data using Plotly and Dash.
- Insight into real-time log analytics and its applications in operational efficiency and decision-making.

