# Explainable-ML-Based-Predictive-System-for-Chronic-Diseases

**LifeCare Watch** is a scalable, explainable, and user-friendly ML-based predictive system for early detection of chronic diseases including **Diabetes**, **Heart Disease**, and **Parkinson’s Disease**. It combines machine learning (ML) with explainable AI (XAI) methods to empower healthcare professionals and patients with accurate, interpretable disease risk assessments through an interactive web interface.

---

## 🧠 Key Features

- Multi-disease prediction (Diabetes, Heart, Parkinson’s)
- Real-time risk assessments via a web-based interface
- Integration of XAI techniques like **SHAP** and **LIME** for interpretability
- Visual analytics and feature importance insights

---

## 🏗️ System Architecture

The architecture consists of four main modules:

A. Data Collection & Preprocessing

- **Datasets Used**:
  - *Diabetes Dataset:* 769 records, 9 features
  - *Heart Dataset:* 304 records, 14 features
  - *Parkinson’s Dataset:* 195 records, 24 features

B. Machine Learning Models

Four ML algorithms were used and evaluated:

1. Support Vector Machine (SVM)

2. Decision Tree (DT)

3. Gradient Boosting (GB)

4. Logistic Regression (LR)

C. Explainable AI (XAI) Integration
To ensure transparency and user trust, the system integrates:

1. SHAP: For global and local feature contributions

2. LIME: For local explanations of individual predictions

These help clinicians and patients understand the why behind every prediction.

D. Deployment via Streamlit
User input forms for health parameters

Real-time predictions and risk scores

Interactive plots: heatmaps, bar charts, SHAP value plots

Backend uses Pickle for ML model serialization


