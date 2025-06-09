# store-visitor-analytics-pipeline
A real-time data pipeline project with Airflow, Python, PostgreSQL and dashboard integration
# Store Visitor Analytics Pipeline

This is a real-time data pipeline project designed to simulate the collection, transformation, storage, and analysis of visitor traffic data from retail stores.

##  Project Overview

This project includes:
- Data ingestion from an external REST API (simulated)
- ETL orchestration using Apache Airflow
- Data transformation with Python (pandas)
- Storage in PostgreSQL (or optionally Redshift)
- Dashboard with Streamlit or Power BI

##  Tech Stack

- Python 3.x
- Apache Airflow
- Docker
- PostgreSQL / Amazon Redshift
- Pandas
- Streamlit (for visualization)

##  Sample Data Structure

```json
{
  "timestamp": "2025-06-10T14:00:00",
  "store_id": "BEY001",
  "location": "Istanbul Kanyon",
  "visitor_count": 126,
  "female_count": 72,
  "male_count": 54,
  "average_age": 32.6
}

##  Project Structure (Planned)
store-visitor-analytics-pipeline/
│
├── dags/                → Airflow DAGs
├── etl/                 → Data processing scripts
├── data/                → Sample JSON & parquet files
├── dwh/                 → PostgreSQL init scripts
├── dashboard/           → Streamlit app
└── README.md

