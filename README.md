# Automated End-to-End ETL Workflow for European Air Traffic Data Lake Creation Using FME

## Repository Overview

This repository hosts the complete automated ETL pipeline designed to collect, process, and maintain a comprehensive Europe-wide air traffic data lake using FME Desktop. The system ingests real-time flight arrival and departure data from all European airports via the Aviation Edge API and combines it with detailed geo-spatial information of airports.

## **Technologies Used**

![ETL Workflow](https://img.shields.io/badge/ETL_Workflow-007ACC?style=for-the-badge&logo=database&logoColor=white&labelColor=005A9C)
![Big Data Lake](https://img.shields.io/badge/Big_Data_Lake-1E90FF?style=for-the-badge&logo=database&logoColor=white)
![FME Desktop](https://img.shields.io/badge/FME-F36F21?style=for-the-badge&logo=FME&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C40?style=for-the-badge&logo=postman&logoColor=white)
![Aviation Edge API](https://img.shields.io/badge/Aviation_Edge_API-004E93?style=for-the-badge&logo=airplane&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-4CAF50?style=for-the-badge&logo=automation&logoColor=white)
![Windows Task Scheduler](https://img.shields.io/badge/Windows_Task_Scheduler-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![GeoJSON](https://img.shields.io/badge/GeoJSON-000000?style=for-the-badge&logo=geojson&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-F29111?style=for-the-badge&logo=json&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## **Introduction**

In today’s data-driven world, real-time integration and processing of vast amounts of information are critical for gaining timely insights and making informed decisions. This project focuses on building an end-to-end real-time big data pipeline for aviation data by leveraging API integration, JSON data formats, ETL process and FME Desktop for spatial data processing. Flight data from the Aviation Edge API is continuously ingested and transformed, enabling the creation of a comprehensive and scalable data lake. This big data lake serves as a centralized repository, allowing efficient storage, querying, and analysis of dynamic flight information. The workflow is automated using Windows Task Scheduler to ensure timely updates, facilitating real-time analytics and operational intelligence for the aviation industry.


## Objectives

- **Develop a robust pipeline for real-time ingestion of flight data** from the Aviation Edge API using API integration and JSON data formats.
- **Implement an ETL (Extract, Transform, Load) process** utilizing FME Desktop to efficiently process and transform raw spatial flight data for further analysis.
- **Design and build a scalable big data lake** to store and manage large volumes of dynamic aviation data, supporting efficient querying and analytics.
- **Automate the data ingestion and processing workflow** using Windows Task Scheduler to ensure continuous and timely updates of flight data.
- **Enable real-time analytics and operational insights** for aviation stakeholders by providing access to up-to-date, processed flight information.


## Data Sources

### 1. Aviation Edge API

[Aviation Edge API](https://aviation-edge.com/) supplies real-time flight schedule data, including arrivals and departures for airports globally. Using a secure API key, the project accesses endpoints to extract daily flight details for each EU airports.
  
### 2. OpenAIP

[OpenAIP](https://www.openaip.net/) provides detailed geographic and operational information about airports worldwide, including the European Union. For this project, GeoJSON file containing airport data was downloaded for all EU countries. 

### 3. OurAirports
[OurAirports](https://ourairports.com/) provides IATA codes for all airports globally.

## Workflow






