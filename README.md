# ✈️ Flight Delay Prediction using PySpark & Spark MLlib

## 📌 Project Overview
This project builds a **large-scale flight delay prediction system** using **distributed computing with PySpark**. Millions of historical U.S. airline records were processed to identify key operational factors influencing **arrival delays > 15 minutes**. The pipeline includes full data preprocessing, feature engineering, model training, and evaluation using **Spark MLlib**.

---

## 🚀 Key Features
- End-to-end **ETL + ML pipeline** built entirely on **PySpark**.
- Distributed processing of **millions of flight records**.
- Automatic **categorical encoding**, feature assembly, and ML pipeline creation.
- **Random Forest classifier** for scalable delay prediction.
- Interpretable feature importance to understand delay drivers.

---

## 🧠 Machine Learning Workflow
- **Data Cleaning:** Handling missing values, type casting, filtering invalid records.
- **Feature Engineering:**
  - Route
  - Departure hour
  - Weekend flag
  - Departure time bucket (Morning/Afternoon/Evening/Night)
  - Departure delay bucket
- **Modeling:**
  - Spark MLlib Pipeline (StringIndexer → OneHotEncoder → VectorAssembler → RandomForestClassifier)
- **Evaluation Metrics:**  
  - **F1-score:** 0.82  
  - **Precision:** 0.86  
  - **Recall:** 0.85  

---

## 📊 Results & Insights
- Achieved **F1-score = 0.82** in predicting whether a flight will be delayed (>15 min).
- Key influencing factors:
  - **Departure delay**
  - **Time-of-day patterns**
  - **Route-level congestion**
- Insights help enhance **airline scheduling**, **resource planning**, and **delay mitigation strategies**.

---

## 🛠️ Tech Stack
- **PySpark**, **Spark SQL**, **Spark MLlib**
- **HDFS**, **Parquet**
- **Feature Engineering at scale**
- **Distributed Machine Learning**

---

## 🌟 Why This Project Matters
Flight delays cost airlines millions and inconvenience passengers daily. By leveraging **big data + distributed ML**, this project demonstrates:
- How to scale ML pipelines on large datasets
- Operational insights from flight patterns
- Practical use of Spark in real-world data engineering & data science workflows

---


---
