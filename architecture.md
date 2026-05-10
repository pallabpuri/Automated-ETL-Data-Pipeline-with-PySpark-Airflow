# Pipeline Architecture

Source API / CSV / Database
        ↓
Raw Ingestion Layer
        ↓
PySpark Transformation Layer
        ↓
Validation & Cleaning Layer
        ↓
Processed Data Storage
        ↓
Analytics / Reporting Layer

Workflow orchestration handled using Apache Airflow.
