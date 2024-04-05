# tokyo-olympic-azure-data-engineering-end-to-end-project

Beginning with the 2021 Olympics data stored in GitHub’s CSV files (accessible here: Alpha-Leporis/tokyo-olympic-azure-data-engineering-end-to-end-project/tree/main/raw-data (github.com)),
This project employs Azure Data Factory (ADF) to smoothly bring this information into the raw layer of Azure Data Lake Storage (ADLS). Moving forward, Azure Databricks takes the lead, refining the dataset and storing the processed data in ADLS’s transformed layer. Azure Synapse Analytics steps in, primarily for robust data warehousing and detailed analysis, allowing deeper exploration and insights. Finally, Power BI visualizes these insights, marking the completion of a step-by-step process and providing a rich and comprehensive view of the 2021 Olympics dataset.

Here’s the diagram which shows the workflow of the project

![alt text](https://raw.githubusercontent.com/Alpha-Leporis/tokyo-olympic-azure-data-engineering-end-to-end-project/main/data-flow/data%20engineering%20project%20diagram.webp)
