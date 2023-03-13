# Github-Activity Data Pipeline On GCP
## Architecture

![Untitled Diagram](https://user-images.githubusercontent.com/102229086/204534347-1607a5cf-9589-46e0-a6ef-666cb8ff3888.jpg)

## Technologies
* Docker for Containerisation.
* Cloud- Google Cloud Platform.
* Terraform - Infrastructure-as-Code.
* Apache Airflow - Workflow Orchestration.
* Google Cloud Storage - DataLake.
* Google BigQuery - Data Warehouse.
* Google DataProc - Batch Processing.
* Looker Studio - Data Visualization.

## Brief Summary of the project
- Github Archive data from [GH Archive](https://www.gharchive.org/) is ingested into GCS.
- A PySpark job is run on GCS using Google DataProc and the results written to tables in Google BigQuery.
- Data is loaded onto Looker Studio from Google Bigquery for Visualization.

## Looker Studio Dashboard

![developer report](https://user-images.githubusercontent.com/102229086/204535973-35588fa5-e0d3-4912-8840-26667d9142a0.PNG)
