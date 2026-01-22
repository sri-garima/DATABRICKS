# DATABRICKS
This repository is maintained to contain each and every file during my Databrick AI 14 days Challenge.

**The challenge is in 2 phases:-**
**Phase I: LEARNING AND SHARING(14 DAYS)**
**Phase II: PROJECT(7 DAYS)**

## This phase is divided further into 4 phases-
**Phase 1: FOUNDATION(DAY1,2,3,4)**
         
          1-Platform Setup
          2-Apache Spark Basics
          3-Pyspark deep Dive
          4-Delta Lake Basic
**Phase 2: DATA ENGINEERING(DAY 5,6,7,8)**
         
          5-Delta Lake Advance
          6-Medallion Architecture
          7-Workflows & Job Orchestration
          8-Unity Catalog Governance
**Phase 3:- Advanced Analytics(Day 9,10,11)**
          
          9-SQL Analytics & Dashboards
          10-Performance Optimization
          11-satistical Analysis & ML Prep
**Phase4:-  AI &ML(Day 12,13,14)**
          
          12-MLflow Basics
          13-Model Comparison & Feature Engineering
          14- AI Powered Analytics:-Genie & Mosaic AI
# 🚀 End-to-End Data Engineering, ML & AI Analytics using Databricks

## 📌 Project Overview

This project demonstrates a **complete end-to-end analytics and AI pipeline** built on **Databricks**, starting from raw data ingestion to machine learning and AI-powered analytics.

The goal of this project is to learn and showcase:

* How raw data flows through **Medallion Architecture (Bronze → Silver → Gold)**
* How analytics and dashboards are built on curated data
* How machine learning models are trained, tracked, and compared using **MLflow**
* How **AI-powered analytics** works using **Databricks Genie** and **Mosaic AI**

This project is designed from a **beginner-friendly perspective**, while following **real-world industry best practices**.

---

## 🧱 Architecture Overview

```
Raw Data
   ↓
Bronze Layer (Raw, Immutable)
   ↓
Silver Layer (Cleaned & Enriched)
   ↓
Gold Layer (Business Aggregates)
   ↓
SQL Analytics & Dashboards
   ↓
MLflow (ML Models)
   ↓
AI-Powered Analytics (Genie & Mosaic AI)
```

---

## 🗂️ Project Structure

```
databricks-e2e-analytics-ai/
│
├── README.md
├── data/
│   └── sample_events.csv
│
├── notebooks/
│   ├── 01_bronze_ingestion.ipynb
│   ├── 02_silver_cleaning.ipynb
│   ├── 03_gold_aggregation.ipynb
│   ├── 04_sql_analytics.sql
│   ├── 05_dashboards.md
│   ├── 06_workflows_jobs.ipynb
│   ├── 07_mlflow_basics.ipynb
│   ├── 08_model_comparison.ipynb
│   ├── 09_genie_ai_analytics.md
│   └── 10_sentiment_analysis.ipynb
│
├── sql/
│   ├── funnel_analysis.sql
│   └── gold_metrics.sql
│
└── images/
    ├── architecture.png
    ├── mlflow_ui.png
    └── genie_queries.png
```

---

## 📅 Project Breakdown (Day-wise)

### ✅ Day 1–3: Bronze Layer – Raw Data Ingestion

**Objective:** Store raw, immutable data exactly as received.

* Read raw CSV/JSON data
* Add metadata like ingestion timestamp
* Store data in Delta format

📌 Bronze layer acts as the **single source of truth**.

---

### ✅ Day 4–6: Silver Layer – Cleaning & Enrichment

**Objective:** Prepare clean and trustworthy data.

* Filter valid event types (`view`, `cart`, `purchase`)
* Handle nulls and bad records
* Standardize column formats

📌 Silver layer ensures **data quality and consistency**.

---

### ✅ Day 7–8: Gold Layer – Business Aggregations

**Objective:** Create business-ready datasets.

Aggregations created:

* `views`
* `cart_adds`
* `purchases`

📌 Gold layer is optimized for **analytics and ML use cases**.

---

### ✅ Day 9–10: SQL Analytics & Dashboards

**Objective:** Generate insights using SQL.

Examples:

* Revenue by category
* Conversion funnel analysis
* Daily purchase trends

📌 Dashboards help translate data into **business insights**.

---

### ✅ Day 11: Workflows & Job Orchestration

**Objective:** Automate the pipeline.

* Parameterized notebooks
* Bronze → Silver → Gold workflow
* Scheduled Databricks jobs

📌 Demonstrates **production-style orchestration**.

---

### ✅ Day 12: MLflow Basics

**Objective:** Track machine learning experiments.

* Train regression model on Gold data
* Log parameters, metrics, and models
* Explore MLflow UI

📊 Achieved **R² score ~0.91**, indicating strong predictive power.

---

### ✅ Day 13: Model Comparison & Feature Engineering

**Objective:** Select the best model.

* Feature engineering using conversion rates
* Train multiple models:

  * Linear Regression
  * Random Forest
  * Gradient Boosted Trees
* Compare metrics in MLflow
* Use Spark ML Pipelines

📌 Focus on **model selection, not just training**.

---

### ✅ Day 14: AI-Powered Analytics (Genie & Mosaic AI)

**Objective:** Explore AI-driven analytics.

* Used **Databricks Genie** to query data using natural language (ChatGPT-like experience)
* Converted business questions directly into SQL and visualizations
* Explored **Mosaic AI** concepts
* Performed **Sentiment Analysis using DistilBERT**

📌 This day highlighted how **AI is transforming analytics into a conversational experience**.

---

## 🧠 Key Learnings

* Medallion Architecture fundamentals
* Data engineering best practices
* SQL analytics and dashboards
* MLflow experiment tracking
* Feature engineering and model comparison
* Spark ML Pipelines
* AI-powered analytics using Genie
* NLP and sentiment analysis using DistilBERT

---

## 🛠️ Tools & Technologies Used

* Databricks
* Apache Spark (PySpark, Spark SQL)
* Delta Lake
* MLflow
* Spark ML
* Databricks Genie
* Mosaic AI
* DistilBERT (Sentiment Analysis)

---

## 🎯 Who Is This Project For?

* Beginners in Data Engineering
* Aspiring ML / MLOps engineers
* Anyone learning Databricks end-to-end
* Professionals looking for a hands-on portfolio project

---

## 🚀 Future Enhancements

* MLflow Model Registry (Staging → Production)
* Batch inference pipelines
* Data quality checks
* Model monitoring and drift detection
* GenAI-powered dashboards

---

## 📌 Final Note

This project helped me connect **data engineering, machine learning, and AI analytics** into one cohesive workflow.

⭐ If you find this project useful, feel free to star the repository and share feedback!
