# ML-Based Predictive Maintenance Using IoT

An end-to-end Predictive Maintenance project that combines **Machine Learning**, **Deep Learning (LSTM)**, **IoT sensor data**, and **Power BI dashboards** to predict machine failures and estimate Remaining Useful Life (RUL).

---

# Project Overview

This project demonstrates how Machine Learning and Business Intelligence can be integrated to build an intelligent predictive maintenance system.

The project predicts machine failures using the AI4I 2020 dataset and estimates Remaining Useful Life (RUL) using the NASA C-MAPSS FD001 dataset. Interactive Power BI dashboards provide insights into machine health, failure risks, model performance, explainability, and maintenance planning.

---

# Objectives

- Predict machine failures before they occur.
- Estimate Remaining Useful Life (RUL) using LSTM.
- Explain predictions using SHAP Explainability.
- Build interactive Power BI dashboards.
- Support proactive maintenance decisions.

---

# Datasets

## AI4I 2020 Predictive Maintenance Dataset

Used for Machine Failure Prediction.

### Features

- Air Temperature
- Process Temperature
- Rotational Speed
- Torque
- Tool Wear
- Machine Type

### Target

- Machine Failure

---

## NASA C-MAPSS FD001 Dataset

Used for Remaining Useful Life Prediction.

Includes:

- Train Dataset
- Test Dataset
- Ground Truth RUL

---

# 🛠 Technologies Used

### Programming

- Python

### Machine Learning

- XGBoost
- Random Forest
- Logistic Regression

### Deep Learning

- TensorFlow
- Keras (LSTM)

### Data Processing

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn
- SHAP

### Business Intelligence

- Microsoft Power BI

---

# 🔄 Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Machine Failure Prediction
5. Model Evaluation
6. SHAP Explainability
7. Remaining Useful Life Prediction
8. Power BI Dashboard Development

---

# Power BI Dashboards

## Dashboard 01 – Executive Overview

- Overall Machine Health
- Failure Prediction Summary
- Maintenance KPIs
- Sensor Overview

---

## Dashboard 02 – Machine Health Monitoring

- Machine Health Score
- Failure Probability
- Risk Distribution
- Machine Status Monitoring

---

## Dashboard 03 – SHAP Explainability

- Global Feature Importance
- Local Feature Impact
- Model Explainability

---

## Dashboard 04 – Model Performance Analysis

- Model Comparison
- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- Confusion Matrix

---

## Dashboard 05 – Live Prediction Monitoring

- Live Prediction Monitoring
- Failure Probability
- Sensor Comparison
- Risk Distribution
- Real-Time Alerts

---

## Dashboard 06 – Remaining Useful Life Prediction

- Actual vs Predicted RUL
- Prediction Error
- RUL Distribution
- Critical Machines
- Latest RUL Predictions

---

# Repository Structure

```text
ML-Based-Predictive-Maintenance-Using-IoT
│
├── data/
├── notebooks/
├── powerbi/
├── screenshots/
├── requirements.txt
├── README.md
└── LICENSE
```

---

# Dashboard Screenshots

## Dashboard 01

![Dashboard 01](screenshots/dashboard01_executive.png)

---

## Dashboard 02

![Dashboard 02](screenshots/dashboard02_machine_health.png)

---

## Dashboard 03

![Dashboard 03](screenshots/dashboard03_shap.png)

---

## Dashboard 04

![Dashboard 04](screenshots/dashboard04_model_performance.png)

---

## Dashboard 05

![Dashboard 05](screenshots/dashboard05_live_monitoring.png)

---

## Dashboard 06

![Dashboard 06](screenshots/dashboard06_rul_prediction.png)

---

# Project Results

- Successfully predicted machine failures using XGBoost.
- Predicted Remaining Useful Life using LSTM.
- Applied SHAP Explainability for model interpretation.
- Built six interactive Power BI dashboards.
- Automated dashboard dataset generation using Python.

---

# Future Improvements

- Real-time IoT sensor integration
- Azure/AWS cloud deployment
- Email and SMS maintenance alerts
- REST API for live predictions
- Automated Power BI refresh

---

# Author

**Arushana Ganesh**

- MSc in Data Science & Artificial Intelligence
- Former Web Developer transitioning into Data Analytics
- Passionate about Machine Learning, Power BI, and Predictive Analytics

---

## ⭐ If you found this project helpful, please consider giving it a star!