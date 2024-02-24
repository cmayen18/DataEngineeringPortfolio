# Building Real-Time Delta Live Tables Pipeline in Azure Databricks for Streamlined Data Processing and Visualization

## Objective
The objective of this project is to implement a real-time analytics pipeline using Delta Live Tables in Azure Databricks. The pipeline will process both streaming and batch data from different sources, applying various transformations and storing the cleaned data in a Delta Live Tables pipeline. The final step involves visualizing the data using Power BI.

## Tools
- **Languages:** SQL, Spark, Python
- **Services:** Azure Event Hub, Azure Data Lake Storage, Azure Databricks, Delta Live Tables, Power BI

## Implementation
1. **Setting Up Azure Infrastructure:**
   - Created an Azure Resource Group.
   - Created an Azure Data Lake Storage account and uploaded batch data into a container.
   - Set up an Azure Event Hub and ingested streaming data into it using a Python script.

2. **Configuring Azure Databricks:**
   - Created an Azure Databricks workspace.
   - Set up a computing cluster within the Databricks workspace.

3. **Loading and Processing Data in Databricks:**
   - Loaded batch data from Azure Data Lake Storage into Databricks tables.
   - Loaded streaming data from Event Hub into Databricks file storage.

4. **Implementing Delta Live Tables Pipeline:**
   - Created a Delta Live Tables pipeline to process both streaming and batch data.
   - Applied transformations on tables stored in Bronze and Silver layers.
   - Stored cleaned data in the Gold layer of the Delta Live Tables pipeline.

5. **Visualizing Data in Power BI:**
   - Loaded data from Gold layer tables into Power BI.
   - Created visualizations in Power BI to analyze and gain insights from the processed data.

## Key Learnings and Outcomes
- Understanding of real-time analytics and its importance in gaining insights quickly.
- Hands-on experience with Azure services like Event Hub, Data Lake Storage, and Databricks for building real-time data pipelines.
- Proficiency in using Delta Live Tables to orchestrate and manage data processing pipelines.
- Ability to visualize processed data effectively using Power BI for analysis and decision-making.

