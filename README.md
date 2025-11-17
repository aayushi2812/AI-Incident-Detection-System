# AI Incident Detection System

*A Deep Learning Approach to Predicting AI Failures Using Code
Vulnerability + Data Quality Analysis*

## Contributers
- Aayushi Chintan Parekh - https://github.com/aayushi2812
- Manmeet Kaur - https://github.com/ManMeet1812

## 📌 Project Overview

AI incidents often occur due to **software vulnerabilities** or **data
issues**.\
This project introduces a **multi-model Deep Learning system** that
predicts the likelihood of an AI incident by analyzing both code risks
and data-quality risks.

## 🔥 Key Features

-   **Model A -- Code Vulnerability Detection**
-   **Model B -- Data Quality Anomaly Detection**
-   **Model C -- Incident Risk Meta-Classifier**

## 🧠 Project Architecture

    Code Dataset → Model A → Code Risk
    Data Dataset → Model B → Data Risk
    Both Risks → Model C → Incident Prediction

## 📂 Folder Structure

    AI-Incident-Detection-System/
    ├── data/
    ├── models/
    ├── notebooks/
    ├── training/
    ├── utils/
    ├── results/
    └── README.md

## 📥 Datasets Used

-   CodeXGLUE / Big-Vul / SARD
-   Credit Card Fraud / UCI Anomaly / Synthetic noisy dataset

## 🤖 Models Used

-   **CodeBERT / DistilBERT / BiLSTM**
-   **Autoencoder / Variational Autoencoder**
-   **Meta-classifier (MLP/Logistic Regression)**

## ⚙️ Training Pipeline

1.  Train Code Model\
2.  Train Data Quality Model\
3.  Train Meta Incident Classifier

## 📊 Results

Outputs probability scores and final incident risk classification.

## 🎯 Novelty & Contribution

-   Integrates **code-level + data-level** risks\
-   Predicts **AI incidents** instead of isolated issues\
-   Introduces unified **AI Incident Risk Score**

## 🧪 How to Run

    pip install -r requirements.txt
    python training/train_code_model.py
    python training/train_data_quality_model.py
    python training/train_incident_classifier.py

## 📘 License

Academic use only.