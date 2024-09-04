# Azure_data_Engineering
Contains all project implemented using Azure services
dataset folder contains all dataset required to create data pipelines in ADF
linkedService contains all linked services i.e Azure databricks and data lake required for transformation and storage in ADF pipelines
pipeline folder contains all the pipelines i.e ingestion one and transformation . Main pipeline is used to execute both pipelines one after the other.
Tumbing window trigger is used to load all the historical data after the certain interval of time.
Formula1.dbc contain all the databricks notebooks used for transformation from raw bucket to processed -> presentation layer following mandalion architacture.


