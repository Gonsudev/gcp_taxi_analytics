# gcp_taxi_analytics
## This is a demonstrator project wherein im using combination of Google Cloud, Mage AI and Looker studio to execute a basic end to end data engineering project.
## Steps Taken:
1. Selecting the Data source (NYC Taxi)
2. Perform Data Modelliing  (ER Diagram)
3. Create a transformation code to convert raw data into fact and dimension tables to match the ER Diagram.
4. Create a Google Cloud account, wherein we will store our CSV data into buckets and make them accessible.
5. Create a new compute engine on which we will be running our Mage AI for ETL
6. Go to the VM, install necessary packages and initiate Mage AI
7. Perform ETL tasks on Mage AI
8. Export the transformed data to BigQuery to process data to gain insights to be used in Looker studio.
9. Connect Looker studio to BigQuery and perform visualizations.

![gcpproj](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/5c8dc1f2-83f7-4aaa-aee8-c023b4b5c80a)\

## Implementation
1. Select the data, analyze it and create a ER diagram to model our data.
   
   ![taxi_datamodel](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/e132cec9-6a1c-4221-bf43-5b24f8999151)
3. Create the transformation code in Jupyter Notebook, to be later used in our Mage AI transformer.
4. Store the data on Google Cloud Storage and make it accessible.
   
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/e40bdd7f-1f94-4c17-8819-333adb7ba57d)
5. Create a new compute engine and install all the necessary lbraries in it.
   
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/e26aa284-aa97-4e52-960a-0eb21e6823f3)
6. Execute the Mage AI command and start using Mage AI
   
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/b6d7df77-e96d-4ff4-9d39-708b570d14bd)
7. Once Logged in perform all the ETL using Data Loader, Transformer and Extractor to transform and load the data into GCP
   
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/35fbfbc0-c1ea-4153-b65e-64d3d51f9087)
9. Log in to BigQuery and process the data in SQL editor.
    
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/e2f87aed-a027-4c11-9044-e73c1de26c51)
11. Perform Data Visualization using Looker studio.
    
   ![image](https://github.com/Gonsudev/gcp_taxi_analytics/assets/34743726/af01838c-9684-4dbe-91c9-83e74408d4e6)



