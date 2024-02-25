# Building a Real-Time Spark Streaming Pipeline for GPS Trajectory Analysis on AWS

## Objective
The objective of this project is to build a real-time Spark streaming pipeline using various AWS services like AWS S3, Amazon Lambda, Amazon Kinesis Data Streams, Amazon EMR, Amazon Kinesis Firehose, and OpenSearch. The pipeline aims to ingest GPS trajectory data, analyze it in real-time, and deliver insights using visualization tools like Kibana.

## Tools
- Language: Scala, Python
- Services: AWS S3, Amazon Lambda, Amazon Kinesis Data Streams, Amazon EMR, Amazon Kinesis Firehose, Amazon DynamoDB, OpenSearch, Kibana

## Implementation

1. **Understanding the GPS Trajectory Dataset:**
   - Gained insights into the GPS trajectory dataset, understanding its structure and fields such as latitude, longitude, altitude, date, and time.
   - Analyzed the PLT file format and its fields, including their significance in representing GPS trajectories.

2. **Setting up AWS Infrastructure:**
   - Created an AWS S3 bucket to serve as the storage for the GPS trajectory data, ensuring proper permissions and access controls.
   - Configured Amazon Kinesis Data Streams to handle real-time data ingestion, setting up shard configuration and stream settings.
   - Developed and deployed Lambda functions using Python or Scala to stream log files into Amazon Kinesis Data Streams, ensuring proper error handling and logging.

3. **Configuring Spark Streaming Job on EMR:**
   - Set up an EMR cluster with appropriate instance types and configurations to run Spark streaming jobs, leveraging AWS Management Console or AWS CLI.
   - Developed Spark streaming job using Scala or Python, configuring it to read data from Kinesis Data Streams in real-time and process the GPS trajectory data.
   - Deployed the Spark streaming job onto the EMR cluster, ensuring scalability and fault tolerance for processing large volumes of streaming data.

4. **Utilizing Amazon Kinesis Firehose and OpenSearch:**
   - Created an Amazon Kinesis Firehose delivery stream to collect, transform, and deliver the processed GPS trajectory data to desired destinations.
   - Integrated OpenSearch with Kinesis Firehose, configuring the delivery stream to write data to OpenSearch for indexing and analysis.
   - Defined index patterns and mappings in OpenSearch to organize and structure the GPS trajectory data for efficient querying and visualization.

5. **Visualization with Kibana:**
   - Utilized Kibana, a part of OpenSearch, to create dynamic visualizations and interactive dashboards for analyzing the GPS trajectory data in real-time.
   - Designed visualizations such as maps, charts, and histograms to showcase spatial and temporal trends in the GPS trajectory data, enabling users to gain actionable insights.

## Data Architecture

![Data Architecture](./Building_Real_Time_Spark_Streaming_Pipeline.png
)

## Key Learnings and Outcomes
- Understanding the concepts and implementation of real-time analytics pipelines.
- Hands-on experience with various AWS services for data ingestion, processing, and visualization.
- Familiarity with deploying and managing Spark streaming jobs on Amazon EMR.
- Ability to integrate different components of the pipeline for seamless data flow and visualization.

