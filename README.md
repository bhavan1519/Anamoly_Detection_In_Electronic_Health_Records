# Anomaly Detection in Electronic Health Records

## Project Overview

Electronic Health Records (EHR) contain highly sensitive patient information and are frequently targeted by unauthorized access, insider threats, and fraudulent activities. Traditional rule-based monitoring systems often struggle to identify complex behavioral patterns and evolving security threats.

This project presents a Machine Learning–based anomaly detection framework that analyzes EHR access logs and identifies suspicious user behavior. The system leverages multiple Machine Learning techniques to learn normal access patterns and detect anomalous activities that may indicate security risks.

---

## Objectives

* Detect anomalous behavior in EHR access logs.
* Identify suspicious access attempts and insider threats.
* Improve healthcare data security through automated monitoring.
* Compare multiple Machine Learning models for anomaly detection.
* Evaluate model performance using standard classification metrics.

---

## Dataset Description

The project utilizes a synthetic Electronic Health Record (EHR) access log dataset containing user activity information.

### Features

* Login Frequency
* Failed Login Attempts
* Access Time
* Session Duration
* After-Hours Access
* User Activity Patterns
* Behavioral Security Indicators

### Target Variable

* **0** → Normal Activity
* **1** → Anomalous Activity

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Feature Engineering
4. Feature Selection
5. Train-Test Splitting
6. Model Training
7. Performance Evaluation
8. Anomaly Detection Results

---

## Machine Learning Models Used

### 1. Isolation Forest

An unsupervised anomaly detection algorithm that isolates abnormal observations based on random partitioning.

### 2. Random Forest

A supervised ensemble learning algorithm used for classification and anomaly prediction.

### 3. XGBoost

A gradient boosting algorithm that enhances predictive performance through optimized decision trees.

### 4. Autoencoder

A deep learning model trained to reconstruct normal behavioral patterns and detect anomalies using reconstruction error.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Matplotlib
* Jupyter Notebook

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Key Features

1. EHR Access Log Analysis

2. Healthcare Cybersecurity Monitoring

3. Insider Threat Detection

4. Data Preprocessing and Feature Engineering

5. Multi-Model Performance Comparison

6. Visualization of Results

7. Automated Security Monitoring

---

## Repository Structure

```text
Anamoly_Detection_In_Electronic_Health_Records
│
├── EHR_Anamoly_Detection.ipynb
├── README.md
├── dataset.csv
├── preprocessed_dataset.csv
│
├── Outputs
│   ├── feature_importance.csv
│   ├── feature_importance.png
│   ├── model_comparison.csv
│   └── model_comparison.png
│
└── .gitignore
```

---

## Future Enhancements

* Real-time EHR access monitoring
* Explainable AI (SHAP, LIME)
* Interactive security dashboard
* Cloud deployment
* Advanced deep learning architectures
* Healthcare security system integration

---

## Sustainable Development Goal (SDG)

### SDG 9 – Industry, Innovation and Infrastructure

This project contributes to SDG 9 by improving the security, reliability, and resilience of healthcare information systems through intelligent anomaly detection and automated cybersecurity monitoring.

---

## Author

**Bhavanika T**

Mini Project – ML-Based Fraud and Anomaly Detection in Electronic Health Records (EHR)

---

## License

This project is developed for academic and educational purposes.
