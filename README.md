# GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project
This repo contains details about end to end implementation of the GCP GCS to BQ pipeline using CI/CD leveraging Airflow DEV and PROD Environments, Thanks

**Data Flow Details:**

Created Data Pipeline to load flight booking CSV file in GCS bucket and using Github Actions yml file- deployed Pyspark/Python files, required variables in Json file, leveraged Serverless Dataproc Cluster, Loaded the data into corresponding DEV/PROD BigQuery tables and implemented Looker Dashboard on PROD BQ Table

**Deepwiki documentation URL:** https://deepwiki.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_to_Looker_End_to_End_Project


[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_to_Looker_End_to_End_Project)



**Project Details:**
1. Implemented Connections to my Github in VS Code, created a repo and activated the connections
2. Implemented Pyspark script to read the flight_booking.CSV file from GCS bucket and performed transformations and loaded into Stgaing and final tables in Big Query
3. Utilized Serverless Dataproc Cluster concepts inside Airflow Script and Deployed the code
4. Created Github YML file which performs actions to Authenticate the GCS Account and through Actions, uploaded Airflow Job, Spark job and Variables information into GCS bucket
5. Implemented required variables for DEV and PROD using Json files and uploaded in to GCS bucket folders as needed using YML files
6. In Github once DEV Airflow DAG ran to success, created Pull request for PROD and PROD airflow DAG ran to success
7. Created Looker Dashboard on the top of the PROD final Table transformed_flight_data_prod

**Source Flight Booking CSV File URL:**

https://github.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project/blob/main/flight_booking.csv

**Airflow DAG File URL:**

https://github.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project/blob/main/airflow_job/airflow_job.py

**Pyspark File URL:**

https://github.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project/blob/main/spark_job/spark_transformation_job.py

**DEV Variables JSON File Details:**

https://github.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project/blob/main/variables/dev/variables.json

**PROD Variables JSON File Details:**

https://github.com/ViinayKumaarMamidi/GCP_Flight_Booking_Airflow_GCS_to_BQ_End_to_End_Project/blob/main/variables/prod/variables.json


**Source GCS Bucket Files:**

<img width="1912" height="646" alt="image" src="https://github.com/user-attachments/assets/c7b5646b-5d8f-4c3c-a109-2d8395fc03c3" />

**DEV Airflow DAG Details:**

<img width="1377" height="621" alt="image" src="https://github.com/user-attachments/assets/6bc75789-673c-47f5-b2f6-4ee46227ec7d" />

**PROD Airflow DAG Details:**

<img width="1398" height="552" alt="image" src="https://github.com/user-attachments/assets/389c77dc-4eac-4542-a633-1545fe052793" />

**Composer Airflow Dev and Prod Details:**

<img width="1918" height="328" alt="image" src="https://github.com/user-attachments/assets/4a1e43d4-7a6c-416d-a0de-37dd93f67987" />


**DEV Serverless Dataproc Cluster Log Details:**

<img width="1380" height="642" alt="image" src="https://github.com/user-attachments/assets/7b504007-395f-4847-bff7-fb092e030be9" />

**PROD Serverless Dataproc Cluster Log Details:**

<img width="1400" height="642" alt="image" src="https://github.com/user-attachments/assets/64138d90-dfbd-4472-ac52-8a5fae49c4e9" />


**DEV Github Deployment Details:**

<img width="1364" height="549" alt="image" src="https://github.com/user-attachments/assets/2018666f-b2d2-4090-a281-6cac853e0ea0" />


**PROD Github Deployment Details:**

<img width="1395" height="584" alt="image" src="https://github.com/user-attachments/assets/809bfffa-1c8f-46f6-b6f4-1f17ebe98851" />


**DEV BigQuery Tables Details:**

<img width="1379" height="622" alt="image" src="https://github.com/user-attachments/assets/d07f3723-4581-4f28-9bb4-b4b05c13271b" />


**PROD BigQuery Tables Details:**

<img width="1403" height="621" alt="image" src="https://github.com/user-attachments/assets/cb1d113a-5b87-4799-b13b-018b64d0097a" />



**Looker Dashboard Details:**

<img width="1383" height="649" alt="image" src="https://github.com/user-attachments/assets/8b7cc8bd-7961-4ee8-b386-920ddc3add91" />



