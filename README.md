# Customer-churn-Predictions

# 🚀 End-to-End MLOps Pipeline for Customer Churn Prediction

## 📌 Overview
This project demonstrates a complete **MLOps pipeline** for predicting customer churn using machine learning. It covers the full lifecycle from data preprocessing and model training to deployment and serving predictions via an API.

---

## 🎯 Objectives
- Build a predictive model for customer churn
- Track experiments and models using MLflow
- Deploy the model as a REST API using FastAPI
- Containerize the application using Docker

---

## 🧠 Problem Statement
Predict whether a customer will churn based on demographic and usage data.

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- MLflow
- FastAPI
- Docker
- Pandas, NumPy

---

## ⚙️ Project Workflow

```mermaid
graph TD;
    A[Data Collection] --> B[Data Preprocessing];
    B --> C[Model Training];
    C --> D[MLflow Tracking];
    D --> E[Model Registry];
    E --> F[FastAPI Deployment];
    F --> G[Docker Container];
