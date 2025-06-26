# Retail_Data_Engineering_Pipeline

A complete Bronze-Silver-Gold data pipeline built with Azure Blob Storage and Python pandas, converting raw retail data into business intelligence insights.

## 🎯 Project Overview
This project demonstrates a modern data engineering pipeline that processes retail transaction data through three layers:

🥉 Bronze Layer: Raw data ingestion from multiple sources
🥈 Silver Layer: Data cleaning, validation, and integration
🥇 Gold Layer: Business metrics and analytics-ready datasets

## 🏗️ Architecture
Raw Data Sources → Bronze Layer → Silver Layer → Gold Layer → Power BI Dashboard
     
![image](https://github.com/user-attachments/assets/d190107e-ac1d-429c-8aeb-b26898750953)

     
## 📊 Data Sources

Customers: Customer profiles and registration data
Products: Product catalog with categories and pricing
Stores: Store locations and details
Transactions: Daily transaction records

## 🛠️ Tech Stack

Cloud Storage: Azure Blob Storage
Processing: Python pandas
Data Format: Parquet files
Visualization: Power BI
Development: Databricks/Jupyter Notebooks

📈 Key Metrics Generated

Daily sales by product and store
Total quantity sold per product
Revenue analysis by category
Average transaction values
Store performance metrics
Customer transaction patterns
