# 📚 Amazon Books Data Pipeline

---

## 🚀 Project Overview
This project is a *data engineering pipeline* that collects, transforms, and analyzes data from Amazon Books.  
It enables insights into book pricing, reviews, and popularity trends by leveraging modern ETL workflows.

---

## 🛠️ Features
- 📥 *Data Ingestion* – Extracts book details from Amazon (title, author, rating, reviews, price).  
- 🔄 *Data Transformation* – Cleans, normalizes, and structures the raw data.  
- 🗄️ *Data Storage* – Stores processed data in a database for easy querying.  
- 📊 *Analytics* – Generates insights and visualizations for better decision-making.  
- ⚡ *Automation* – Fully automated ETL pipeline with scheduling support.

---

## 🏗️ Architecture
```mermaid
flowchart LR
    A[Amazon Books Data] -->|Scraper/API| B[Raw Data]
    B --> C[Data Cleaning & Transformation]
    C --> D[(Database)]
    D --> E[Analytics & Visualization]
