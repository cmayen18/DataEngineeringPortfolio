## Objective
The objective of this project is to build a real-time Spark streaming pipeline using various AWS services like AWS S3, Amazon Lambda, Amazon Kinesis Data Streams, Amazon EMR, Amazon Kinesis Firehose, and OpenSearch. The pipeline aims to ingest GPS trajectory data, analyze it in real-time, and deliver insights using visualization tools like Kibana.

## Tools
- Language: Scala, Python
- Services: AWS S3, Amazon Lambda, Amazon Kinesis Data Streams, Amazon EMR, Amazon Kinesis Firehose, Amazon DynamoDB, OpenSearch, Kibana

## Implementation
1. **Understanding the GPS Trajectory Dataset:**
   - Gain insights into the GPS trajectory dataset, including its structure and fields.
2. **Setting up AWS Infrastructure:**
   - Create an AWS S3 bucket to store the GPS trajectory data.
   - Configure Amazon Kinesis Data Streams to handle real-time data ingestion.
   - Create necessary Lambda functions for streaming log files into Kinesis Data Streams.
3. **Configuring Spark Streaming Job on EMR:**
   - Set up an EMR cluster to run Spark streaming jobs.
   - Develop and deploy a Spark streaming job to read from Kinesis Data Streams and process the data.
4. **Utilizing Amazon Kinesis Firehose and OpenSearch:**
   - Create an Amazon Kinesis Firehose delivery stream to collect and transform the processed data.
   - Integrate OpenSearch with Kinesis Firehose for data visualization.
5. **Visualization with Kibana:**
   - Use Kibana, a part of OpenSearch, to create visualizations and dashboards for analyzing the GPS trajectory data in real-time.

## Key Learnings and Outcomes
- Understanding the concepts and implementation of real-time analytics pipelines.
- Hands-on experience with various AWS services for data ingestion, processing, and visualization.
- Familiarity with deploying and managing Spark streaming jobs on Amazon EMR.
- Ability to integrate different components of the pipeline for seamless data flow and visualization.

