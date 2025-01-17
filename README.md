# COVID-19 Data Engineering Project  

## Overview  
This project showcases a comprehensive **data engineering pipeline** designed to process, transform, and visualize COVID-19 data trends across regions. The pipeline automates data ingestion, distributed data processing, and transformation while enabling interactive reporting through integrated visualization tools.

## Features  
- **Data Pipeline**:  
  - Automated ingestion and transformation of real-world COVID-19 datasets using **Azure Data Factory**.  
  - Distributed data processing using **Azure HDInsight** and **Azure Databricks** for scalability and performance.  
  - Efficient data storage and querying with **Delta Lake**.  

- **Dashboards**:  
  - **Testing Trends Dashboard**: Displays COVID-19 testing data across the EU/EEA & UK, showing tests by country and comparing tests done vs confirmed cases over time.  
  - **Cases and Death Trends Dashboard**: Highlights total COVID-19 cases and death trends for the UK, France, and Germany.
  - **Cases Trends Dashboard**: COVID-19 dashboard for EU/EEA & UK shows cases, deaths, trends, and filters for date and country for detailed insights.

- **DevOps Integration**:  
  - CI/CD pipelines implemented using **Azure DevOps** to streamline deployment and project versioning.  

- **Visualization**:  
  - Interactive and dynamic dashboards created using **Power BI**, enabling actionable insights.  

## Technologies Used  
- **Azure Data Factory**: For data ingestion and orchestration.  
- **Azure HDInsight**: For distributed data processing using Apache Hadoop.  
- **Azure Databricks**: For distributed data transformation and analysis.  
- **Delta Lake**: For optimized data storage and querying.  
- **Power BI**: For visualization and reporting.  
- **Azure DevOps**: For CI/CD pipelines and version control.  

## Project Workflow  
1. **Data Ingestion**:  
   - Raw COVID-19 datasets were fetched from public sources and ingested into Azure Data Factory pipelines.  

2. **Data Processing**:  
   - Used **Azure HDInsight** for distributed processing of large-scale datasets with Apache Hadoop.  
   - Cleaned, transformed, and enriched the datasets using **Azure Databricks**.  
   - Implemented Delta Lake for efficient storage and querying.  

3. **Data Visualization**:  
   - Built interactive dashboards in Power BI to visualize trends such as testing rates, confirmed cases, and deaths by country.  

4. **Deployment**:  
   - Integrated Azure DevOps pipelines for seamless deployment and versioning of the project.  

## Key Deliverables  
- **Dashboard 1: Testing Trends**  
  ![Testing Trends](path/to/Testing.png)  
  - Testing data visualized across countries in the EU/EEA & UK.  
  - Comparison of tests done vs confirmed cases over time.  

- **Dashboard 2: Cases and Death Trends**  
  ![Cases and Death Trends](path/to/Trends-Country.png)  
  - Trends for total cases and deaths visualized for the UK, France, and Germany.  

## Dataset  
The project uses publicly available COVID-19 datasets, which include information on testing numbers, confirmed cases, and death rates.  

## Installation and Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/covid19-data-engineering.git
