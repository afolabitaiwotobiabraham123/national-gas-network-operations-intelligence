# Python Analysis

This folder contains the Jupyter Notebooks used for National Gas API data acquisition, exploratory data analysis, data quality assessment, and data cleaning and preparation.

Python, Requests, Jupyter Notebook, and Pandas will be used to retrieve, explore, transform, and prepare operational data for further analysis in MySQL and Power BI.

## Notebooks

### 01_data_acquisition.ipynb

Connects to the National Gas Operational Data API, retrieves operational data, and preserves the original API responses in the raw data folder.

### 02_exploratory_data_analysis.ipynb

Explores the collected dataset to understand its structure, variables, distributions, gas flow patterns, and available operational information.

### 03_data_quality_assessment.ipynb

Assesses the dataset for missing values, duplicate records, invalid timestamps, inconsistent categories, unexpected values, and data-type problems.

### 04_data_cleaning_and_preparation.ipynb

Flattens JSON data where necessary, cleans and transforms the dataset, documents preparation decisions, and produces structured data for MySQL analysis.

## Tools

- Python
- Requests
- Jupyter Notebook
- Pandas

## Workflow

API Data Acquisition → JSON Exploration and Flattening → Exploratory Data Analysis → Data Quality Assessment → Data Cleaning and Preparation
