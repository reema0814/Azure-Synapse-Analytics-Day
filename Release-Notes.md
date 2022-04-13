# Release Notes

### 11 March 2022

* Major updates in Lab.
  * **Exercise 1: Explore the data lake with Azure Synapse Serverless SQL Pool and Azure Synapse Spark**  No changes
  * **Exercise 2: Working with Azure Synapse Pipelines**   No changes
  * **Exercise 3: High Performance Analysis with Azure Synapse Dedicated SQL Pools** 
    - This exercise was Exercise 4 and Exercise 3 has been moved to Exercise 7
  * **Exercise 4: Lake Databases and Database templates**    
    
    This is a newly added exercise. It includes concepts of lake database and helps you learn learn how to use readily available database templates for lake databases.
   It includes following tasks:
     - Task 1 - Create and configure a lake database
     - Task 2 - Create a lake database table from data lake storage
     - Task 3 - Create a custom lake database table and map data into it
     - Task 4 - Create a complex lake database using database templates
  * **Exercise 5: Log and telemetry analytics**

    This is a newly added exercise. This exercise helps you explore the capabilities of the newly integrared Data Explorer runtime in Synapse Analytics.
    It includes following tasks:
     - Task 1 - Create a table for data ingestion in Data Explorer database
     - Task 2 - Perform manual data ingestion using a Synapse Pipeline
     - Task 3 - Run KQL queries from Synapse Studio
     - Task 4 - Load Data Explorer data into a Spark dataframe
  * **Exercise 6: Data governance with Azure Purview** 
    This is a newly added exercise.  This exercise helps you to use several of the capabilities provided by the integration between Azure Synapse Analytics and Azure Purview   workspaces.
    It includes following tasks
     - Task 1 - Explore the integration of Azure Purview into the Azure Synapse Analytics workspace
     - Task 2 - Trigger automatic data lineage tracking when executing a Synapse Pipeline
     - Task 3 - Discover data assets using Azure Purview powered search
     - Task 4 - Explore the results of scaning an Azure Synapse Analytics workspace from Azure Purview
     - Task 5 - Explore the results of data lineage tracking for Synapse Pipelines

  * **Exercise 7: Power BI integration**
    - This exercise was Exercise 3
  

  * **Exercise 8: Data Science with Spark (optional)**
      This exercise was Exercise 5, the content has beeen completly replace.  This  execise helps you to train a machine learning models using AutoML with Spark compute. You will use the model registered in Azure Machine Learning to make predictions using the T-SQL Predict statement.
     It includes following tasks
      - Task 1 - Training and registering models with AutoML
      - Task 2 - Using registered models in Synapse Analytics

### 17 August 2021
 - Minor update in the Lab Guide.
   - A note has been added to the 01-explore-data-lake.md file to assist users in skipping MFA when logging into the Azure Portal.

### 10 August 2021
 * Major changes in the Lab Guide.
   * Exercise 1:
	 - In Task 1, New SQL scripts are added to query the delta lake to calculate the quarterly sales and to export the CSV files to datalake.
	 - In Task 2, SQL scripts are added to query the datalake.
* Exercise 2:
   - In Task 2, steps are updated for pipeline implementations.
     - Bonus Task is added to explore sentiment data.
* Exercise 5:
   - In Task 2, new steps are added to run notebook which handles trains, converts, and uploads ONYX models to Azure storage.
   - Task 3 is added which implements sentiment analysis in synapse without writing any code.
