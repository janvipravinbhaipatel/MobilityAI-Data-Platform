# MobilityAI Data Platform

An end-to-end AI-ready global employee mobility data platform
designed to demonstrate modern data engineering practices.

## Project Objective

MobilityAI simulates the data environment of a global employee
relocation organization.

The platform consolidates employee, relocation, vendor,
service, cost, and survey data into reliable analytics-ready
and AI-ready datasets.

## Business Use Cases

The platform supports analysis of:

- Global employee relocations
- Relocation costs
- Vendor performance
- Service delivery
- Employee satisfaction
- Survey feedback
- SLA and completion performance

## Technology Stack

The project will use:

- Microsoft Azure
- Azure Data Lake Storage Gen2
- Azure Databricks
- Delta Lake
- Python
- PySpark
- SQL
- T-SQL
- Power BI
- Git
- GitHub
- CI/CD
- Generative AI

## Data Architecture

The project follows a Medallion Architecture:

Data Sources
→ Bronze
→ Silver
→ Gold
→ Analytics / Power BI / AI

### Bronze

Raw source data with minimal transformations.

### Silver

Cleaned, validated, standardized, and integrated data.

### Gold

Business-ready datasets optimized for reporting,
analytics, and AI applications.

## Primary Data Domains

- Employees
- Relocations
- Vendors
- Services
- Relocation Costs
- Employee Surveys

## Project Status

🚧 Under active development.

## Disclaimer

This is an independent portfolio project using synthetic data.

It is not affiliated with Graebel or any other relocation
company and does not use proprietary company data.