# 🧠 Mental Health Signal — Student Wellness Analytics

[![Live Demo](https://img.shields.io/badge/Render-Live%20Demo-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://mental-health-score-predictor-1-b72d.onrender.com)

A full-stack Machine Learning application designed to predict and analyze a student's mental health score based on their daily habits, digital screen usage, academic workload, and lifestyle factors.

🔗 **Live Deployment:** [https://mental-health-score-predictor-1-b72d.onrender.com](https://mental-health-score-predictor-1-b72d.onrender.com)

---

## 📌 Project Overview

**Mental Health Signal** provides real-time insights into how daily lifestyle choices impact mental wellness. By running user-inputted metrics through a trained Machine Learning pipeline, the system estimates a predicted mental health score on a scale of 0 to 10.

---

## 🛠️ Tech Stack & Architecture

### **Frontend**
* **HTML5 & CSS3**: Modern layout, modern typography, and clean custom styling (`style.css`).
* **JavaScript (Vanilla ES6+)**: Asynchronous API call handling (`fetch`), dynamic UI updates, custom segmented button handling, and form validation (`script.js`).

### **Backend & Machine Learning**
* **Python**: Core language used for model building, preprocessing, and API backend.
* **Jupyter Notebook (`ML_Project.ipynb`)**: Data preprocessing, feature engineering, exploratory data analysis (EDA), model training, and evaluation.
* **FastAPI**: Lightweight, high-performance web framework for serving the ML model API (`main.py`).
* **Pandas & Scikit-Learn**: Data structures, data transformation pipelines, and predictive modeling.
* **Joblib**: Model serialization (`Mental_Health_Model.pkl`).
* **Uvicorn**: ASGI server interface for serving FastAPI locally and in production.

---

## 📁 Repository Structure

```text
├── ML_Project.ipynb          # Jupyter Notebook for Data Analysis & Model Training
├── Mental_Health_Model.pkl   # Serialized Trained Machine Learning Model
├── main.py                   # FastAPI REST API Endpoints
├── index.html                # Frontend User Interface
├── style.css                 # Custom Styling and Gauge UI Component
├── script.js                 # Client-side Logic & API Fetching
├── requirements.txt          # Python Dependency List
└── README.md                 # Project Documentation
