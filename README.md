# Azure_Olympic_DataEngineeringProject

1. Data Ingestion with Azure Data Factory (ADF):
Objective: Move data from source to staging area.

Data Source: Azure Blob storage
ADF Pipeline:
Create an ADF pipeline to copy data from the source to a staging area in Azure Storage (e.g., Azure Data Lake Storage Gen2).
Using ADF's data movement activities or copy data tool to define the data movement.

2. Data Transformation with Azure Databricks:
Objective: Perform data transformation using Azure Databricks.

Databricks Notebook:
Create a Databricks notebook to perform the required transformations on the data.
Utilizing PySpark or Spark SQL in the notebook for data manipulations.
We can read data from the staging area, perform transformations, and write the transformed data back to another storage location (e.g., another folder in Azure Data Lake Storage Gen2).

3. Data Loading into Azure Synapse Analytics:
Objective: Load transformed data into Synapse Analytics.

Synapse Workspace:
Set up a Synapse Analytics workspace and define the required databases and tables.
Azure Synapse Copy Activity in ADF:
Use Azure Data Factory to create a pipeline with a Copy Activity.
Configure the Copy Activity to move data from the transformed data location in Azure Data Lake Storage Gen2 to the appropriate tables in Synapse Analytics.

4. Power BI Visualization:
Objective: Visualize data using Power BI.

Power BI Desktop:

Connect Power BI Desktop to your Synapse Analytics data warehouse.
Import or establish a live connection to the required tables/views.
Create reports and dashboards using Power BI Desktop.
Power BI Service:

Publish your Power BI Desktop file to the Power BI service.
Schedule refresh if your data is regularly updated.
