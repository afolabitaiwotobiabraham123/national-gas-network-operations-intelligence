# National Gas Network Operations Intelligence System

##  Project Status

**Project in Progress**

This project is part of my **Energy, Supply Chain & Operations Analytics Portfolio**.

The project uses publicly accessible National Gas operational data to explore gas-network flow patterns, linepack conditions, and operational performance.

---

## 🇬🇧 Project Context

**National Gas** operates Great Britain's gas transmission network.

This project focuses on using operational data to understand:

* Gas flow
* Entry-point supply
* Linepack
* Time-based operational patterns
* Flow anomalies
* Network conditions

---

##  Problem Statement

Gas transmission networks must continuously balance gas entering the network with gas leaving the network while maintaining appropriate network conditions.

Operational data can provide valuable information about changes in supply, flow, and linepack.

The analytical question for this project is:

**Can operational gas-flow data be analysed to identify unusual flow patterns and periods requiring operational attention?**

---

##  Proposed Solution

I plan to build a:

### **National Gas Network Operations Intelligence System**

The project will use operational API data to develop an analytical workflow covering:

REST API
   ↓
JSON Response
   ↓
Python
   ↓
Pandas
   ↓
Data Structure Assessment
   ↓
Data Quality Assessment
   ↓
Data Cleaning
   ↓
MySQL
   ↓
Operational Analysis
   ↓
Power BI

---

##  Data Source

The project uses the **National Gas operational data API**.

The initial API endpoint being explored provides instantaneous flow information by site.

The response contains information related to:

* Publication time
* Current gas day
* Site
* Flow rate
* Applicable time
* Quality indicator
* Schedule time

---

##  Key Analytical Questions

1. How does gas flow vary by entry site?
2. What are the highest and lowest flow periods?
3. How does flow change throughout the gas day?
4. What patterns can be observed across sites?
5. Are there unusual flow observations?
6. How does actual flow compare with scheduled flow where the required data is available?
7. How does linepack change over time?
8. Can operational KPIs provide early visibility into unusual network conditions?

---

##  Data Engineering Process

### 1. API Data Collection

Retrieve operational data programmatically using Python.

### 2. JSON Exploration

Understand the structure of the API response.

### 3. JSON Flattening

Use Pandas techniques such as: 
pd.json_normalize() to convert nested JSON into tabular data.

### 4. Data Structure Assessment

Examine:

* Columns
* Data types
* Nested structures
* Record counts
* Relationships
* Timestamp fields

### 5. Data Quality Assessment

Check for:

* Missing values
* Duplicate records
* Invalid timestamps
* Unexpected values
* Inconsistent categories
* Data-type problems

### 6. Data Cleaning

Clean and transform the dataset for analysis.

### 7. MySQL Storage

Store the cleaned operational data in a relational database.

### 8. Analysis

Use SQL and Python to investigate operational patterns.

### 9. Visualization

Develop a Power BI operational dashboard.

---

##  Planned KPIs

Potential KPIs include:

* Total Gas Flow
* Average Flow Rate
* Maximum Flow Rate
* Minimum Flow Rate
* Flow by Entry Site
* Flow Variability
* Scheduled vs Actual Flow
* Linepack Level
* Linepack Change
* Operational Exception Count

---

##  Technologies

* REST API
* Python
* Requests
* JSON
* Pandas
* NumPy
* MySQL
* SQL
* Power BI
* Data Quality Assessment
* Data Cleaning
* Operations Analytics
* Supply Chain Analytics

---

##  Planned Project Structure

national-gas-network-operations-intelligence/
│
├── data/
│
├── api/
│   └── national_gas_api.py
│
├── python/
│   ├── 01_api_data_collection.py
│   ├── 02_json_exploration.py
│   ├── 03_json_flattening.py
│   ├── 04_data_structure_assessment.py
│   ├── 05_data_quality_assessment.py
│   ├── 06_data_cleaning.py
│   └── 07_operational_analysis.py
│
├── sql/
│   ├── 01_data_exploration.sql
│   ├── 02_data_quality.sql
│   ├── 03_data_cleaning.sql
│   └── 04_operational_analysis.sql
│
├── powerbi/
│
├── visuals/
│
└── README.md

---

##  Project Roadmap

*  Identify National Gas API
*  Understand API endpoint
*  Test API request
*  Retrieve JSON response
*  Explore nested JSON structure
*  Flatten JSON using Pandas
*  Perform data structure assessment
*  Perform data quality assessment
*  Clean the dataset
*  Store data in MySQL
*  Perform operational analysis
*  Develop operational KPIs
*  Build Power BI dashboard
*  Document findings
*  Publish final portfolio project

---

##  Skills Demonstrated

### API & Data Engineering

* REST APIs
* API data extraction
* JSON processing
* Data transformation
* Pandas
* MySQL

### Data Analytics

* Exploratory Data Analysis
* Data Quality Assessment
* Data Cleaning
* Time-series analysis
* KPI development

### Energy & Operations Analytics

* Gas-flow analysis
* Network operations
* Linepack monitoring
* Operational exception analysis
* Energy supply-chain analytics

---

##  Disclaimer

This is an independent educational portfolio project using publicly accessible operational data.

It is not an official National Gas system and does not represent National Gas's internal operational processes, systems, forecasts, or management decisions.
