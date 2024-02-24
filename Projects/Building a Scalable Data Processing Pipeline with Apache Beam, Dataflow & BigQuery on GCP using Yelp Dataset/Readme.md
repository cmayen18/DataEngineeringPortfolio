# Building a Scalable Data Processing Pipeline with Apache Beam, Dataflow & BigQuery on GCP using Yelp Dataset

## Objective
Understanding and implementing a data ingestion and processing pipeline on Google Cloud Platform using real-time streaming and batch loads with the Yelp dataset.

## Approach
1. **Understanding the Project, Architecture, and Tools:**
   - Gain insights into the project objectives, system architecture, and the role of Google Cloud Storage, SDK, PubSub, Apache Beam, Cloud Composer/Airflow, Dataflow, BigQuery, and Data Studio.

2. **Setting Up Environment and Connecting Services:**
   - Install and configure Google Cloud SDK, connect it to the service account, and create a Google Cloud Storage bucket.

3. **Data Exploration and Preparation:**
   - Explore the Yelp dataset, including its JSON stream and file, and prepare for ingestion.

4. **Data Ingestion and Processing:**
   - Utilize PubSub for data ingestion by creating topics, understand Apache Beam for executing data processing pipelines, and create data flow stream and batch jobs.

5. **Orchestration and Integration:**
   - Utilize Cloud Composer/Airflow for orchestrating batch workloads, and integrate PubSub, Cloud Composer/Airflow with Apache Beam, Google Cloud Dataflow, and BigQuery.

6. **Data Warehousing and Visualization:**
   - Use BigQuery as a data warehouse for storing structured data and integrate it with Data Studio for visualization and reporting of data insights.

## Tools
- Google Cloud Platform
- Google Cloud Storage
- Google Cloud SDK
- Yelp dataset (JSON)
- PubSub
- Apache Beam
- Google Cloud Dataflow
- Google BigQuery
- Cloud Composer/Airflow
- Google Data Studio

  
## Implementation

- **Service Account Creation on GCP:**
  - Navigate to the Google Cloud Platform (GCP) console and create a service account with the necessary permissions for accessing resources.

- **Downloading and Setting up Google Cloud SDK:**
  - Download and install the Google Cloud SDK on your local machine to interact with GCP services from the command line.

- **Connecting Python Software and Dependencies to GCP:**
  - Install and configure Python along with any necessary dependencies for data processing and analysis, ensuring seamless integration with GCP.

- **Downloading Yelp Dataset in JSON Format:**
  - Obtain the Yelp dataset in JSON format from the relevant source and ensure it is accessible for further processing.

- **Connecting JSON File to Cloud Storage:**
  - Upload the JSON dataset file to Google Cloud Storage, establishing a connection for efficient data storage and retrieval.

- **Creating PubSub Topics for Data Ingestion:**
  - Create PubSub topics to facilitate the ingestion of data streams, enabling real-time processing and analysis.

- **Creating Data Processing Pipelines with Apache Beam:**
  - Develop data processing pipelines using Apache Beam, defining the necessary transformations and actions to be performed on the incoming data.

- **Setting up Cloud Composer Instance for Orchestration:**
  - Provision a Cloud Composer instance on GCP, configuring it to orchestrate and manage the execution of batch processing workflows.

- **Tracking DAG Runs and Configurations in Cloud Composer:**
  - Monitor and manage Directed Acyclic Graph (DAG) runs within Cloud Composer, ensuring proper execution and configuration of data processing tasks.

- **Integrating PubSub, Cloud Composer/Airflow with Apache Beam:**
  - Integrate PubSub and Cloud Composer/Airflow with Apache Beam to establish a seamless flow of data between ingestion, processing, and storage components.

- **Utilizing Google Cloud Dataflow for Processing:**
  - Utilize Google Cloud Dataflow to efficiently process data at scale, leveraging the parallelism and fault tolerance provided by the service.

- **Storing Structured Data in BigQuery:**
  - Store structured data in Google BigQuery, creating tables and schemas to organize and query the processed data effectively.

- **Visualizing Data in Data Studio:**
  - Visualize the processed data using Google Data Studio, creating insightful dashboards and reports to derive actionable insights from the analyzed data.


## Key Learnings and Outcomes
- Understanding data ingestion and processing pipelines.
- Hands-on experience with Google Cloud Platform tools.
- Integrating various services for real-time and batch data processing.
- Utilizing cloud services for scalable and efficient data storage and analysis.
- Visualizing data insights for better decision-making.
