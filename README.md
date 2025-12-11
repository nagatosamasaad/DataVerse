# Smart City Energy Optimization Platform

This project is an end-to-end Azure-based data engineering and machine learning solution
for forecasting energy consumption, analyzing weather & traffic impact, and generating
optimization recommendations for smart city energy management.

---

## 🌍 Project Architecture
![Architecture](SmartCity-Energy-Optimization/architecture
/system_architecture.png)

### Components:
- Azure Data Factory (Raw → Bronze)
- Azure Databricks (Silver cleaning + feature engineering)
- Azure Machine Learning Designer (Forecasting)
- Azure Synapse Analytics (Gold SQL views)
- Power BI Dashboard (Visualization)

---

## 📁 Project Structure

- `/adf` — All ADF pipelines, triggers, REST configs  
- `/databricks` — Notebooks for cleaning, feature engineering, and joining  
- `/gold` — ML pipeline outputs + optimization logic  
- `/dashboard` — Power BI file  
- `/documentation` — Final report + slides + data dictionary  
- `/sample_data` — Example files for testing  
- `/architecture` — System diagrams  

---

## 🚀 Features
- Hourly energy forecasting using Prophet / ARIMA  
- Weather & traffic integration  
- Risk zone classification  
- Load shifting optimization recommendations  
- Power BI dashboard with trends, forecasts, and heatmaps 

---

## 👥 Team Members
1. nagat osama 
2. Ebrahim Ateff
3. Abdullah Mohamed
4. Merna Sameh
