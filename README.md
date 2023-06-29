# Uber Data Analytics: End-to-End Data Engineering Project

![Carpool-rafiki](https://github.com/MerwinRoy/Uber-Data-Analytics--End-to-End-Data-Engineering-Project/assets/46862684/dea84d67-1ba1-457f-bf54-3dfd2f8dfb50)

-----
## Index
  - [Abstract](#abstract)
  - [Tools and Technology](#tools-and-technology)
  - [Dataset](#dataset)
  - [Architecture](#architecture)
  - [Data Model](#data-model)
  - [Mage AI](#mage-ai)
  - [Uber Analytics Dashboard](#uber-analytics-dashboard)
----- 

## Abstract
End-to-End Data Engineering Project to extract Uber trip data from GCP cloud storage, transform data and load it into GCP BigQuery data warehouse to then perform data analysis using Looker Studio. ETL Process implemented using Mage AI running on GCP Compute Engine.

## Tools and Technology
- Programming Language - Python (ETL Scripting) <br>
- [Mage AI](https://www.mage.ai/) - Modern Data Pipeine Tool -  <br>
- Google Cloud Platform (Cloud Service)<br>

  > Google Storage (GCP Cloud Storage) <br>
  > Compute Instance (GCP Compute Engine) <br>
  > BigQuery (GCP Data Warehouse) <br>
  > Looker Studio (Data Analytics and Visualization) <br>
  
## Dataset
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

More info about the dataset can be found here:

[Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) <br>
[Data Dictionary/Document](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf) <br>

## Architecture

<img width="603" alt="Architecture" src="https://github.com/MerwinRoy/Uber-Data-Analytics--End-to-End-Data-Engineering-Project/assets/46862684/9d349257-1fa0-4ba8-9701-4523ecf4eb84">

## Data Model

### Dimension and Fact tables
<img width="719" alt="Data Model" src="https://github.com/MerwinRoy/Uber-Data-Analytics--End-to-End-Data-Engineering-Project/assets/46862684/22af841d-1e2c-46b0-bd8a-70ada72ec7bf">

## Mage AI
It is an open-source modern data pipeline tool used for transforming and integrating data. In this project, 3 python scripts were created for the following `ETL (Extract, Transform, Load)` Task.

> `Data Loader` - For extracting data from GCP cloud storage to Mage running on GCP Compute Engine instance. <br>

> `Data Transformer` - For transforming data. <br>

> `Data Exporter` - For loading processed data into GCP Big Query for data analysis. <br>
 
### Data Pipeline ETL Tree

<img width="367" alt="Mage Data Pipeline Tree" src="https://github.com/MerwinRoy/Uber-Data-Analytics--End-to-End-Data-Engineering-Project/assets/46862684/b32182e6-f6b3-42b1-ade8-53a004b25b30">

## Uber Analytics Dashboard

### Looker Studio Dashboard
<img width="1440" alt="Uber Dashboard" src="https://github.com/MerwinRoy/Uber-Data-Analytics--End-to-End-Data-Engineering-Project/assets/46862684/9f29c566-2c9d-4017-8690-370d706db9e1">


