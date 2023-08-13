# tokyo-olympic-data-pipeline-azure

The goal of this project was to create a simple Data Pipeline using a Tokyo Olympics Dataset, originally available at: https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

Data was loaded onto Data Factory with the creation of ingestion functions from a HTTP end point. This raw data was then stored in Azure's Data Lake. Various transformations were applied to this raw data using the Azure Databricks service, harnessing the power of Spark. Then this transformed data was loaded back on the Data Lake, and finally Azure's Synapse was used to perform various analytics on this data.

# Microsoft Azure Services used:
1. Azure Data Factory (Data Ingestion)
2. Azure Data Lake Gen 2 (Raw/Transformed Data Store)
3. Azure Databricks (Transformation)
4. Azure Synapse Analytics (Analytics)



![pipeline](https://github.com/AbhimanyuW/tokyo-olympic-data-pipeline-azure/assets/63635609/b1e08b9e-7748-46b8-8656-5fdd0a805212)
