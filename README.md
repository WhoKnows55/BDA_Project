# 📊 Big Data Analytics Project — DSAA 2024/2025

Welcome to our **Big Data Analytics (BDA)** project for the **NOVA IMS Master in Data Science & Advanced Analytics**!  
This repository contains the code, notebooks, and resources used to process, analyze, and visualize large datasets using Apache Spark on **Databricks Community Edition**.

---

## 📌 Project Guidelines

As part of the course deliverables, our project must follow these requirements:

### 📖 Requirements
- **Problem Definition:** Identify a relevant Big Data problem.
- **Data Collection & Preprocessing:** Obtain, clean, and preprocess large datasets.
- **Big Data Processing:** Use **Apache Spark Modules** (SQL, MLlib, or Streaming).
- **Data Analysis & Visualization:** Apply machine learning, statistics, or BI tools.
- **Results & Insights:** Present findings through dashboards, visualizations, or reports.
- **Project Presentation:** Deliver a 7–10 min presentation, followed by Q&A.

### 💡 Example Project Ideas
- 📈 Stock Market Prediction (Spark MLlib)
- 🔍 Fraud Detection with Real-time Streaming
- 🛍️ Customer Segmentation (Clustering)
- 🌍 Air Pollution Trend Analysis
- 📱 Twitter Sentiment Analysis (NLP)
- 📦 E-commerce Recommendation Systems
- 🐝 Biodiversity Monitoring with Satellite Data

> ⚠️ **Bonus:** Additional points available for integrating **Streaming** and **GraphX**

---

## 🛠️ Installation Guide

Follow these steps to set up your local development environment:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/BDA_Project.git
   cd BDA_Project
   ```

2. **Create a Python Virtual Environment**
   (from one folder up — outside the repo)
   ```bash
   python3.11 -m venv BDA_env
   source BDA_env/bin/activate
   ```

3. **Install Required Dependencies**
   ```bash
   pip install -r BDA_Project/requirements.txt
   ```

4. **Register Kernel**
```bash
BDA % python -m ipykernel install --user --name BDA_env --display-name "Python BDA_env"
```
5. **Open Jupyter Notebook**
   - Navigate to the `Notebooks` folder
   - Select **BDA_env** as the active kernel

**Note for Graph Analytics**
   - If using **GraphFrames** on Databricks:
     ```python
     spark.sparkContext.addPyFile("path_to_graphframes_package")
     ```


---

## 📝 Workflow Suggestion (a.k.a. Mr. Gigachad's Advice)

> For simplicity and efficiency:
- ✅ Develop and test simple transformations locally using **Jupyter + PySpark**.
- 🚀 Execute final data processing, MLlib models, and visualizations in **Databricks Notebooks** attached to your Databricks cluster.

---

## 📊 Deliverables

- 📓 **Technical Report** (3–5 pages)
- 📝 **Source Code (Databricks Notebook)**  
- 🎥 **Presentation (7–10 min)**

---

## 👥 Team Members Group 22

| Name              | Student Number | 
|:------------------|:----------------|
| Philippe Duntranoit | 20231234        | 
| Julia Karpienia   | 20235678        | 
| Daan Van Holten   | 20239876        | 
| Benedikt Ruggaber  | 20240500   | 
| Joshua Wehr  | 20240501   | 

---

## 📎 License

This project is part of the **NOVA IMS Big Data Analytics** course and is for academic use only.

---