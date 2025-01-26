# etl-project-01
## Audi Car Data ETL Pipeline
##### This repository contains an ETL (Extract, Transform, Load) pipeline to scrape detailed specifications of Audi cars from PakWheels. The pipeline extracts data from a given URL, transforms it by categorizing fuel efficiency, and then loads the transformed data into a CSV file.

## Project Overview
##### This project scrapes data about Audi cars from the PakWheels website. The ETL pipeline consists of three main stages:

- Extract: Extracts URLs of individual car models from the main Audi page.
- Transform: Scrapes detailed specifications of each car, including categorizing fuel efficiency based on mileage.
- Load: Saves the transformed data into a CSV file for further analysis.
#### The pipeline is designed to handle a static set of car data (not dynamic or real-time data).

## Prerequisites
- To run this project, you'll need the following installed on your system:

### Libraries:
- requests
- beautifulsoup4
- pandas

## File Descriptions
#### etl_pipeline.py: The main script containing the ETL pipeline logic.
- ./logs/code_logs.txt: A log file where the pipeline process is logged.
- ./output/Audi-data.csv: The output CSV file that contains the transformed car data.