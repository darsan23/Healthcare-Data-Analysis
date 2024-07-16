# Healthcare Insurance Analysis Project

## Project Overview

A Health Care insurance company is facing challenges in enhancing its revenue and understanding its customers. To address this, the company aims to leverage the Big Data Ecosystem to analyze competitors' company data received from various sources, including scraping and third-party sources. This analysis will help the company track customer behavior and conditions to customize offers, calculate royalties for past customers, and ultimately enhance revenue.

## Project Goals

The primary goal of this project is to create data pipelines that will allow the Health Care insurance company to:
1. Analyze customer behavior.
2. Develop appropriate business strategies.
3. Enhance revenue by sending customized offers and royalties to customers.

## List of Requirements

1. Identify the disease with the maximum number of claims.
2. Find subscribers younger than 30 who subscribe to any subgroup.
3. Determine which group has the maximum subgroups.
4. Identify the hospital that serves the most patients.
5. Find the subgroup subscribed to the most times.
6. Calculate the total number of rejected claims.
7. Determine the city from which most claims originate.
8. Identify whether subscribers mostly opt for government or private policy groups.
9. Calculate the average monthly premium paid by subscribers.
10. Determine the most profitable group.
11. List patients below the age of 18 admitted for cancer.
12. List patients with cashless insurance and total charges of Rs. 50,000 or more.
13. List female patients over the age of 40 who have undergone knee surgery in the past year.

## Environment

- **Databricks**
- **GitHub**

## Dataset Description

The following datasets are used in this project:

- `claims.json`: Contains information about insurance claims.
- `disease.csv`: Contains details about diseases.
- `group.csv`: Contains details about policy groups.
- `grpsubgrp.csv`: Contains mapping between groups and subgroups.
- `hospital.csv`: Contains information about hospitals.
- `Patient_records.csv`: Contains records of patients.
- `subgroup.csv`: Contains details about subgroups.
- `subscriber.csv`: Contains details about subscribers.

## Dataset Creation

1. Upload the provided sample data files to your Databricks environment or the designated folder in your project.

## Data Cleaning

Data cleaning involves fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. This is crucial because combining multiple data sources can lead to data duplication or mislabeling, resulting in unreliable outcomes and algorithms.

### Cleaning Activities

1. Check for null values in the dataset.
2. Count the total null values for each column.
3. Replace null values for specific columns with "NA".
4. Check for duplicate records and drop duplicates if found.

### Datasets to Clean

- Patients
- Subscriber
- Claims
- Group_subgroup

### Post-Cleaning Steps

1. Upload cleaned data for each dataset into the target tables in your Databricks environment.
2. Create a schema design document for target tables.

## How to Run the Project

1. Set up your environment with Databricks and connect it to your GitHub repository.
2. Ensure the input data is uploaded to the designated folder as specified.
3. Follow the data cleaning procedures outlined above.
4. Upload the cleaned data to the specified tables in Databricks.
5. Use the schema design document to understand the structure of the target tables.

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes relevant documentation.
