
### Project Goal
This PySpark project aims to simulate a sophisticated real-world data pipeline based on messaging, leveraging a comprehensive tech stack including NiFi, PySpark, Hive, HDFS, Kafka, Airflow, Tableau, and AWS QuickSight. The project focuses on demonstrating end-to-end implementation of a Big Data pipeline on AWS, emphasizing scalability, reliability, and security, while providing detailed insights into building and automating data pipelines.

### Approach
1. **Real-time Data Streaming**: Extract Covid-19 dataset in real-time from an external API using NiFi.
2. **Data Parsing and Encryption**: Parse complex JSON data into CSV format using NiFi and encrypt one of the PII fields for data security.
3. **Data Processing with PySpark and Kafka**: Process data sent to Kafka using PySpark and write the processed data to an output Kafka topic.
4. **Data Storage and Querying**: Consume processed data from Kafka and store it in HDFS, then create a Hive external table on top of HDFS for querying.
5. **Data Cleaning and Transformation**: Clean and transform data stored in the data lake.
6. **Data Visualization**: Visualize key performance indicators using Tableau and AWS QuickSight.

### Tools and Technologies
- NiFi: Real-time data transfer and encryption.
- PySpark: Data processing and manipulation.
- Hive: Data warehousing and querying.
- HDFS: Data storage.
- Kafka: Messaging and data streaming.
- Airflow: Data flow orchestration.
- Tableau and AWS QuickSight: Data visualization.

### Implementation

1. **Covid-19 Dataset Streaming**: The Covid-19 dataset was streamed in real-time using NiFi. NiFi processors were configured to fetch data at regular intervals, ensuring continuous data flow from an external API.

2. **JSON to CSV Parsing and Encryption**: JSON data was parsed into CSV format and Personally Identifiable Information (PII) fields, like country code, were encrypted for enhanced data security using NiFi's encryption mechanisms.

3. **Data Processing with PySpark and Kafka**: PySpark was employed to process data from Kafka topics, leveraging Spark's distributed processing capabilities. Processed data was then written back to Kafka topics for further consumption.

4. **Data Storage in HDFS**: Processed data was consumed from Kafka topics and stored in HDFS, ensuring fault tolerance and data redundancy across the distributed file system.

5. **Hive External Table Creation**: An external table schema was defined in Apache Hive to represent the data stored in HDFS. The location of data files in HDFS was registered as an external table in Hive's metastore for querying.

6. **Data Cleaning and Transformation**: Data stored in the data lake underwent cleaning and transformation processes, handling missing values and inconsistencies to prepare it for analysis. Techniques such as normalization and aggregation were applied for data refinement.

7. **Visualization using Tableau and AWS QuickSight**: Tableau and AWS QuickSight were utilized for creating interactive dashboards and reports. Visualizations showcased key performance indicators like total confirmed cases, total recovered cases, and total deaths, facilitating data-driven decision-making.

By implementing these steps, a robust data pipeline was established for processing, storing, and analyzing real-time Covid-19 dataset updates, while providing insights through interactive visualizations.


### Key Learnings and Outcomes
- Understanding of NiFi for real-time data streaming and encryption.
- Proficiency in PySpark for data processing and manipulation.
- Knowledge of Hive for data warehousing and querying.
- Hands-on experience with HDFS for data storage.
- Understanding of Kafka for messaging and data streaming.
- Experience with Airflow for data flow orchestration.
- Data visualization skills using Tableau and AWS QuickSight.

