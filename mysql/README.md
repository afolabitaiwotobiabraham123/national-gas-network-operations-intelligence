# MySQL Analysis

This folder contains the SQL scripts used to store, analyze, and calculate operational performance metrics from the prepared National Gas transmission dataset.

MySQL will be used to examine gas flow patterns, compare entry-point contributions, calculate operational KPIs, and investigate network performance.

## SQL Scripts

### 01_database_setup.sql
Creates the project database and the required tables for storing prepared operational data.

### 02_gas_flow_analysis.sql
Analyzes gas flow patterns across available transmission network sites, including flow rates and changes over time.

### 03_entry_point_analysis.sql
Examines gas supply contributions from different entry points and compares their flow patterns.

### 04_operational_kpi_calculations.sql
Calculates relevant operational KPIs based on the fields available in the collected dataset.

### 05_network_performance_analysis.sql
Investigates network performance, flow variations, and potential operational exceptions supported by the available data.

## Tools
- MySQL
- SQL

## Workflow
Prepared Dataset → MySQL Database → SQL Analysis → KPI Calculations → Operational Insights

**Note:** Analysis and KPI calculations will depend on the actual fields, measurement units, and operational information available in the collected dataset.
