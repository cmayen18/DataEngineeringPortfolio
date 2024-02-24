# Automating Big Data Processing with Docker, GKE, and Cloud Functions on Google Cloud Platform

## Objective
# Objective
This project aims to utilize Google Cloud Platform (GCP) services such as Dataflow and Apache Beam for batch and real-time data processing, exploring Dataflow features and implementing data pipelines.

# Tools
- Language: Python3
- Services: Cloud Storage, Dataflow, Apache Beam, BigQuery, G-Cloud SDK, Pub/Sub

## Implementation

1. **Read JSON Encoded Messages from Cloud Storage File:**
   - Utilized Cloud Storage service to access a JSON file containing encoded messages.
   - Used appropriate methods or libraries to read the JSON data from the file.

2. **Transformed the Data Using Apache Beam:**
   - Developed data transformation logic using Apache Beam, which included defining transformations such as mapping, filtering, and aggregating.
   - Apache Beam provided a unified programming model to process both batch and streaming data efficiently.

3. **Wrote the Transformed Data to BigQuery:**
   - Established a connection to BigQuery, a cloud-based data warehousing service.
   - Defined the schema for the transformed data to ensure compatibility with BigQuery's table structure.
   - Used Apache Beam's connectors or BigQuery APIs to write the transformed data into designated BigQuery tables.

4. **Published JSON Encoded Messages to Pub/Sub for Streaming:**
   - Utilized Pub/Sub, a messaging service for event-driven systems, to publish JSON-encoded messages.
   - Published the messages to specific topics within Pub/Sub, which acted as channels for data streams.

5. **Processed Streaming Data with Dataflow Runner:**
   - Deployed Dataflow runner, a service for executing data processing pipelines on Google Cloud Platform.
   - Configured the Dataflow pipeline to consume messages from Pub/Sub topics and apply necessary transformations using Apache Beam.
   - Dataflow runner ensured efficient and scalable processing of streaming data in real-time.

6. **Stored the Processed Data in BigQuery for Analysis:**
   - Configured the Dataflow pipeline to write the processed data into BigQuery tables.
   - Defined appropriate partitioning and clustering strategies to optimize query performance in BigQuery.
   - The processed data was now stored in BigQuery, ready for analysis using SQL queries or visualization tools like Data Studio.


# Key Learnings and Outcomes
- Practical understanding of Apache Beam and Dataflow for data processing.
- Hands-on experience with creating and optimizing data pipelines.
- Familiarity with Pub/Sub and BigQuery for data ingestion and storage.
