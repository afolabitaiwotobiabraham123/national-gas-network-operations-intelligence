# National Gas Network Operations Intelligence System

**Energy, Supply Chain & Operations Analytics Portfolio Project**

**Project Status:** In Progress

## 1. Project Overview

The National Gas Network Operations Intelligence System is an independent analytics project focused on understanding gas transmission network performance using publicly accessible operational data from National Gas.

The project will examine gas flow patterns, entry-point supply, linepack conditions, network performance, and operational variations over time.

Using Python, Jupyter Notebook, Pandas, MySQL, and Power BI, the project aims to transform operational data into meaningful insights that support gas network monitoring and operational decision-making.

**Industry Context:** National Gas operates Great Britain's gas transmission network. This project uses its publicly accessible operational data as the basis for an independent energy and operations analytics case study.

**Disclaimer:** This is an independent portfolio project. It is not affiliated with National Gas and does not represent its internal operational systems or official business decisions.

## 2. Business Problem

Gas transmission networks must maintain a continuous balance between gas entering and leaving the network while managing network conditions and available transportation capacity.

Changes in gas flows, entry-point supply, and linepack can provide important information about network performance and operational conditions.

Without effective analysis of operational data, it can be difficult to identify:

- Significant changes in gas flow across entry points.
- Variations in supply patterns throughout the gas day.
- Periods of unusual flow behaviour.
- Differences between actual and scheduled flows, where data is available.
- Changes in linepack and network balancing conditions.
- Operational periods that may require further investigation.

This project explores how data analytics can improve visibility into gas transmission operations and support data-driven operational monitoring.

**Main Business Question:**

Can publicly accessible gas transmission operational data be analysed to identify unusual flow patterns, monitor network performance, and provide useful operational insights?

## 3. Project Objectives

The objectives are to:

1. Retrieve operational data from the National Gas API.
2. Understand and process API responses in JSON format.
3. Explore gas flow patterns across available sites and operational periods.
4. Assess the quality and consistency of the collected data.
5. Clean and prepare operational datasets using Python and Pandas.
6. Store prepared datasets in MySQL.
7. Analyse gas flows and operational performance using SQL.
8. Develop relevant gas transmission operational KPIs.
9. Build an interactive Power BI dashboard.
10. Communicate findings and data-driven operational recommendations.

## 4. Scope of Analysis

### Gas Flow Analysis

- Gas flow patterns across available entry points.
- Flow variations over time.
- Highest and lowest recorded flow rates.
- Average flow rates.
- Gas supply patterns across sites.

### Entry-Point Supply Analysis

- Gas supply by entry site.
- Contribution of individual entry points to recorded flows.
- Changes in supply patterns.
- Comparisons between entry points.

### Linepack and Network Balancing

- Linepack levels and changes, where supported by the available data.
- Relationship between gas entering and leaving the network.
- Network balancing patterns.
- Periods requiring further investigation.

### Operational Performance Monitoring

- Flow variability.
- Actual versus scheduled flow, where the necessary data is available.
- Operational exceptions.
- Time-based performance patterns.
- Network performance indicators.

## 5. Data Sources

The project uses the publicly accessible **National Gas Operational Data API**.

API base URL:

`https://api.nationalgas.com/operationaldata/v1`

The initial endpoint explored is the Instantaneous Flow endpoint, which provides operational flow information across available sites.

The API data being explored includes fields relating to:

- Publication time.
- Current gas day.
- Operational category.
- Site name.
- Flow rate.
- Quality indicator.
- Schedule time.

The exact fields, availability, units, and limitations will be documented after examining the retrieved datasets.

Data collection and analysis will respect the API's documentation, access requirements, and historical data limitations.

## 6. Tools and Technologies

| Tool | Purpose |
|---|---|
| REST API | Access operational data |
| Python | API data acquisition and analysis |
| Requests | Send API requests |
| JSON | Handle API responses |
| Jupyter Notebook | Document and execute analytical workflows |
| Pandas | Flatten, manipulate, assess, and clean datasets |
| MySQL | Structured data storage and SQL analysis |
| Power BI | Interactive dashboards and visualizations |
| GitHub | Documentation and version control |

## 7. Key Performance Indicators (KPIs)

The project will investigate the following potential KPIs, depending on the actual data fields and measurements available.

| KPI | Description |
|---|---|
| Total Gas Flow | Total recorded gas flow over a defined period |
| Average Flow Rate | Average recorded flow rate |
| Maximum Flow Rate | Highest recorded flow rate |
| Minimum Flow Rate | Lowest recorded flow rate |
| Flow by Entry Site | Recorded flow grouped by entry site |
| Flow Variability | Changes in flow over time |
| Scheduled vs Actual Flow | Difference between scheduled and actual flow, where available |
| Linepack Level | Recorded network linepack level, where available |
| Linepack Change | Change in linepack over a defined period |
| Operational Exception Count | Number of observations meeting documented exception criteria |

KPI definitions, formulas, units, assumptions, and limitations will be documented before calculations are performed.

## 8. Project Workflow

The project will follow this analytical workflow:

1. Identify and understand the National Gas API.
2. Retrieve operational data using Python and Requests.
3. Explore API responses and JSON structures.
4. Perform exploratory data analysis using Python and Jupyter Notebook.
5. Assess data quality using Python and Jupyter Notebook.
6. Clean and prepare the operational datasets using Python and Pandas.
7. Store prepared datasets in MySQL.
8. Perform gas flow and network operations analysis using SQL.
9. Calculate relevant operational KPIs.
10. Develop an interactive Power BI dashboard.
11. Document analytical findings and operational recommendations.

## 9. Repository Structure

```text
national-gas-network-operations-intelligence-system/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── python/
│   ├── 01_data_acquisition.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_quality_assessment.ipynb
│   └── 04_data_cleaning_and_preparation.ipynb
│
├── mysql/
│   ├── 01_database_setup.sql
│   ├── 02_gas_flow_analysis.sql
│   ├── 03_entry_point_analysis.sql
│   ├── 04_operational_kpi_calculations.sql
│   └── 05_network_performance_analysis.sql
│
├── power_bi/
│   ├── dashboard/
│   └── screenshots/
│
├── reports/
│   ├── data_quality_report.md
│   ├── gas_flow_analysis.md
│   ├── entry_point_analysis.md
│   └── operational_insights.md
│
├── docs/
│   ├── data_sources.md
│   ├── data_dictionary.md
│   └── kpi_definitions.md
│
├── requirements.txt
│
└── .gitignore
```

## 10. Expected Deliverables

- Documented National Gas API data source.
- Collected raw operational datasets.
- Processed and validated datasets.
- Python/Jupyter data acquisition and preparation notebooks.
- MySQL database and SQL analysis scripts.
- Gas transmission operational KPI calculations.
- Interactive Power BI dashboard.
- Data quality and analytical reports.
- Operational insights and recommendations.

## 11. Business Value

This project demonstrates how supply chain and operations analytics can support gas transmission network monitoring and performance analysis.

The intended business value includes:

- Improved visibility into gas flow patterns.
- Better understanding of entry-point supply performance.
- Monitoring of network balancing indicators.
- Identification of unusual operational patterns.
- Improved understanding of time-based network performance.
- Data-driven support for operational investigation and decision-making.

## 12. Project Disclaimer

This is an independent educational and professional portfolio project developed using publicly accessible operational data.

It does not represent National Gas's internal systems, confidential operational information, official forecasts, or management recommendations.

---

**Focus Areas:** Supply Chain Analytics | Operations Analytics | Gas Transmission | Network Performance | Gas Flow Analysis | Energy Analytics | Oil & Gas
