
# ETL - Data Pipeline using Databricks with Snowflake and AWS
This project demonstrates an ETL (Extract, Transform, Load) pipeline for processing data sourced from ```Kaggle```, filtering it in Databricks, and loading it into Snowflake.

## Architecture

![Architecture-Diagram](https://github.com/AliMuhammad229/ETL-Kaggle-Databricks-Snwoflake/assets/47716529/b9e87575-f07a-4976-ad40-02224d0bdeaa)


## Overview
This ETL pipeline involves three main stages:

- Data Extraction: Data is sourced from Kaggle using the Kaggle API.
- Data Transformation: The data is filtered in Databricks to focus on product data related to iPhones and AirPods headphones.
- Data Loading: The filtered data is loaded into Snowflake.
Setup
To set up the project, follow these general steps:

## Setup
### 1. Install Dependencies: 
Ensure you have the necessary tools and libraries installed, including ``PySpark``, the ``Kaggle`` library, and the snowflake-connector-python.

### 2. Configure Kaggle API: 
Obtain API credentials from Kaggle and configure the Kaggle API to access datasets programmatically.

### 3. Set up Databricks: 
Create a Databricks workspace and configure FileStore to serve as the bronze layer for data storage.

### 4. Set up Snowflake: 
Create a Snowflake account and configure it to accept data from Databricks using the snowflake-connector-python.

## Usage

#### 1. Data Extraction: 
Use the Kaggle API to download the dataset from Kaggle and store it in Databricks.
#### 2. Data Transformation: 
Filter the dataset in Databricks, selecting only the product data related to iPhones and AirPods headphones.
#### 3. Data Loading: 
Establish a connection to Snowflake and load the filtered dataset into Snowflake.
