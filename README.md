# ENERGYZEROETL
A complete ETL pipeline for energy price data. It connects to the EnergyZero API, processes data with Pandas by splitting dates and adding 21% VAT, and stores results in Parquet format. The workflow is containerized with Docker and automated using Apache Airflow for scheduling and orchestration.
