![image](https://github.com/rileha/tokyo_2021_olympics_data_engineering_project/assets/170321721/dac537e9-09e4-4157-aad6-f103ae33bdc5)

Firstly, we will take the following data about the 2021 Olympic Games from Kaggle, which contains the details of over 11,000 athletes, with 47 disciplines, along with 743 teams taking part in the 2021(2020) Tokyo Olympics.

https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

The first step is to download the data as a CSV file and use Azure Data Factory to Ingest the raw data before storing it in a Data Lake using a Storage Account. Then, using Apache Spark in Databricks the data endures a very basic transformation before the Transformed Data is once again stored in a Data Lake. Azure Synapse Analytics is used to execute simple SQL queries on the data before beig Visualized in a Dashboard.

The pupose of this project was to understand the basic mechanics of ETL pipelines in Azure and get exposure to a variety of different Azure services. I understand that most of this process can be done using only one of the services like Synapse although I wanted to experiment! 
