# 

## Objective
Explore Hive's analytical capabilities by performing analytics on Customer Demographics data from the Adventure Works dataset using big data tools like Sqoop, Spark, and HDFS.

## Approach
- **Setup AWS EC2 Instance**: Launch an AWS EC2 instance to deploy the project environment.
- **Containerization with Docker**: Utilize Docker to create container images via a docker-compose file on the EC2 machine.
- **Data Preparation in MySQL**: Create tables in MySQL and ingest data from the Adventure Works dataset, focusing on Customer, Individual, and Credit Card tables.
- **Data Ingestion with Sqoop**: Load data from MySQL into HDFS storage using Sqoop commands.
- **Data Transformation with Hive**: Move data from HDFS to Hive for analytics, leveraging Hive's SQL-like interface.
- **Integration with Spark**: Integrate Hive into Spark to perform analytics tasks efficiently.
- **Analytics with Scala**: Use Scala programming language to extract Customer demographics information from the data and store it as Parquet files.
- **Data Storage and Retrieval**: Transfer Parquet files from Spark to Hive and create tables in Hive to load data from Parquet files.
- **Hive Analytics**: Perform analytical queries on Customer Demographics data using Hive.

## Implementation

1. **AWS EC2 Setup and Docker Deployment**:
   - Set up an AWS EC2 instance to host the project environment and ensure sufficient resources for Spark execution.
   - Deploy Docker containers on the EC2 instance using a docker-compose file, including Spark, Hive, and any other required dependencies.

2. **MySQL Table Creation and Data Import**:
   - Create tables in MySQL database to match the schema of the Adventure Works dataset, including Customer, Individual, and Credit Card tables.
   - Import data from the Adventure Works dataset into the MySQL tables using MySQL commands or GUI tools, ensuring data consistency and correctness.

3. **Data Loading with Sqoop**:
   - Use Sqoop commands to extract data from MySQL tables and load it into the Hadoop Distributed File System (HDFS), preserving the table schema and data types.
   - Specify Sqoop parameters such as source, target, and data format to ensure successful data transfer from MySQL to HDFS.

4. **Data Processing and Analysis with Spark**:
   - Implement Spark jobs using Scala or Python to perform data processing and analysis tasks on the datasets stored in HDFS.
   - Utilize Spark's DataFrame API or RDDs (Resilient Distributed Datasets) to manipulate and transform the data according to analytical requirements.

5. **Integration of Spark with Hive**:
   - Integrate Apache Spark with Apache Hive to leverage Hive's SQL-like querying capabilities within Spark applications.
   - Configure Spark to interact with Hive tables by specifying the Hive metastore URI and Hive table names, enabling seamless data exchange between Spark and Hive.

6. **Customer Demographics Extraction and Storage**:
   - Develop Spark jobs to extract specific customer demographics information from the datasets stored in HDFS, such as age, gender, income, etc.
   - Store the extracted demographic data as Parquet files, a columnar storage format optimized for analytics, ensuring efficient storage and retrieval of data.

7. **Table Creation and Data Loading in Hive**:
   - Create external Hive tables to represent the Parquet files containing customer demographics data, defining appropriate schemas and partitioning strategies.
   - Load the Parquet files into the Hive tables using Spark SQL or HiveQL commands, ensuring data consistency and compatibility with Hive queries.

8. **Analytical Queries in Hive**:
   - Execute analytical queries on the Customer Demographics data stored in Hive tables using HiveQL, leveraging Hive's SQL-like interface for data analysis.
   - Perform various analytics tasks such as demographic segmentation, trend analysis, and pattern recognition to derive actionable insights from the data.

## Key Learnings and Outcomes

- Understanding Hive's analytical features and its integration with other big data tools.
- Proficiency in setting up environments using AWS EC2 and Docker.
- Hands-on experience with data ingestion and transformation using Sqoop and Hive.
- Knowledge of transferring data between Spark and Hive for streamlined analytics.
- Skill development in executing analytical queries on large datasets using Hive's SQL-like interface.

