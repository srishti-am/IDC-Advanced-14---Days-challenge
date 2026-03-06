End-to-End Machine Learning Lakehouse Pipeline (Databricks)
This repository contains a 14-day hands-on project where I built an end-to-end Machine Learning pipeline using the Databricks Lakehouse architecture.
The project demonstrates how raw data can be transformed into actionable predictions and recommendations using Spark, Delta Lake, and MLflow.
It covers the complete lifecycle:
Data ingestion
Feature engineering
Machine learning training
Experiment tracking
Batch inference
Recommendation systems
Performance optimization
Data versioning
Architecture design
The final result is a production-style ML pipeline built on top of a Lakehouse architecture.



Project Architecture
The system follows a Bronze → Silver → Gold Lakehouse architecture.
Raw Event Data
        ↓
Bronze Layer
events_delta (Delta Table)
        ↓
Silver Layer
user_features (Feature Engineering)
        ↓
ML Pipeline
Feature Vectorization
        ↓
Random Forest Model
        ↓
Gold Layer
Predictions + Recommendations
Parallel ML workflow:
User Interaction Data
        ↓
ALS Recommendation Model
        ↓
Top Product Recommendations
        ↓
Gold Recommendation Table



Technologies Used
Databricks
Apache Spark
PySpark
Delta Lake
Spark MLlib
MLflow
Unity Catalog
Serverless Databricks Environment
