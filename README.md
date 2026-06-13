# Earthquake Alert Prediction using Explainable Machine Learning

![Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Supervised-green)
![XAI](https://img.shields.io/badge/Explainable%20AI-SHAP-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)

## Overview

Earthquake Alert Prediction is an Explainable Artificial Intelligence (XAI) and Supervised Machine Learning project developed to predict earthquake alert levels using historical seismic activity data.

Unlike traditional classification projects that focus solely on prediction accuracy, this project emphasizes both predictive performance and model interpretability through Explainable AI techniques.

The project incorporates:

* Supervised Machine Learning
* Class Imbalance Handling using SMOTE
* Multi-Model Benchmarking
* Explainable AI using SHAP
* Feature Importance Analysis
* Decision Rule Extraction
* Disaster Analytics

The objective is to build a reliable earthquake alert prediction system while ensuring that model decisions remain transparent and understandable.

---

# Problem Statement

Earthquakes are among the most destructive natural disasters and can significantly impact human life, infrastructure, and economic stability.

Although seismic monitoring systems continuously collect large amounts of earthquake-related data, manually analyzing these datasets is difficult and time-consuming.

The goal of this project is to leverage Machine Learning techniques to predict earthquake alert categories based on seismic characteristics while also providing interpretable explanations for model predictions.

---

# Objectives

* Analyze earthquake datasets
* Perform data cleaning and preprocessing
* Address class imbalance problems
* Build supervised learning models
* Compare multiple machine learning algorithms
* Improve minority class detection
* Implement Explainable AI techniques
* Extract interpretable decision rules
* Evaluate model performance comprehensively

---

# Dataset Description

The dataset contains earthquake-related seismic measurements and geographical information used for alert prediction.

Key features include:

* Magnitude
* Depth
* Latitude
* Longitude
* SIG (Significance)
* MMI (Modified Mercalli Intensity)
* CDI (Community Damage Index)
* Other seismic indicators

These attributes are used to predict earthquake alert levels.

---

# Project Workflow

## 1. Data Collection

* Load earthquake dataset
* Explore data structure
* Understand feature distributions

## 2. Data Cleaning

* Handle missing values
* Remove inconsistencies
* Validate feature formats

## 3. Exploratory Data Analysis (EDA)

* Statistical analysis
* Correlation analysis
* Distribution analysis
* Pattern discovery

## 4. Feature Engineering

* Feature selection
* Data transformation
* Preparation for modeling

## 5. Class Imbalance Handling

The dataset exhibited class imbalance issues.

SMOTE (Synthetic Minority Oversampling Technique) was used to:

* Balance class distribution
* Improve minority class learning
* Enhance model fairness

## 6. Model Development

Multiple machine learning models were trained and evaluated.

## 7. Explainable AI Analysis

SHAP and Feature Importance analysis were applied to explain model behavior.

## 8. Rule Extraction

Decision rules were extracted to improve interpretability and transparency.

---

# Machine Learning Models Evaluated

The following supervised learning algorithms were compared:

## Random Forest

* Ensemble learning approach
* Strong baseline performance

## Random Forest + SMOTE

* Class-balanced training
* Improved minority class detection
* Best overall performance

## XGBoost

* Gradient boosting framework
* High predictive capability

## Logistic Regression

* Linear baseline classifier
* Interpretable model

## Decision Tree

* Rule-based classifier
* Human-readable decision paths

---

# Explainable AI (XAI)

One of the key goals of this project was to make model decisions interpretable.

## SHAP Analysis

SHAP (SHapley Additive Explanations) was used to:

* Explain individual predictions
* Measure feature contributions
* Improve model transparency
* Identify influential variables

## Feature Importance Analysis

Feature importance rankings revealed the strongest predictors of earthquake alert levels.

Top Predictive Features:

* SIG (Significance)
* MMI (Modified Mercalli Intensity)
* CDI (Community Damage Index)
* Latitude
* Longitude
* Depth

## Rule Extraction

Decision Tree Rule Extraction was implemented to:

* Generate interpretable decision paths
* Explain alert classifications
* Improve stakeholder understanding
* Increase trust in model predictions

---

# Results

## Best Performing Model

### Random Forest + SMOTE

| Metric            | Value  |
| ----------------- | ------ |
| Training Accuracy | 100.0% |
| Testing Accuracy  | 84.8%  |
| Macro Recall      | 0.758  |
| Macro F1 Score    | 0.734  |

---

## Performance Comparison

| Model                 | Test Accuracy |
| --------------------- | ------------- |
| Random Forest + SMOTE | 84.8%         |
| Random Forest         | 83.2%         |
| Logistic Regression   | 82.4%         |
| XGBoost               | 80.8%         |
| Decision Tree         | 75.2%         |

---

## Key Findings

* Random Forest with SMOTE achieved the best overall performance.
* SMOTE significantly improved minority class detection.
* Class 3 Recall improved substantially compared to baseline Random Forest.
* Feature importance analysis identified SIG, MMI, CDI, Latitude, and Longitude as the most influential predictors.
* SHAP explanations improved transparency and interpretability.
* Rule extraction provided understandable decision-making pathways.

The results demonstrate that combining class balancing techniques with ensemble learning and Explainable AI can improve both model performance and trustworthiness.

---

# Technologies Used

## Programming

* Python

## Data Processing

* Pandas
* NumPy

## Machine Learning

* Scikit-Learn
* Random Forest
* Logistic Regression
* Decision Tree
* XGBoost
* SMOTE

## Explainable AI

* SHAP

## Visualization

* Matplotlib
* Seaborn

## Development Environment

* Jupyter Notebook

---

# Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Supervised Machine Learning
* Ensemble Learning
* Class Imbalance Handling
* SMOTE
* Explainable AI (XAI)
* SHAP Analysis
* Rule Extraction
* Model Evaluation
* Comparative Model Benchmarking
* Data Visualization
* Disaster Analytics

---

# Challenges Faced

* Handling class imbalance
* Improving minority class detection
* Preventing model overfitting
* Interpreting complex model decisions
* Comparing multiple algorithms fairly
* Extracting meaningful insights from seismic data

---

# Future Improvements

* Hyperparameter Optimization
* Ensemble Model Stacking
* Deep Learning Approaches
* Real-Time Earthquake Monitoring Integration
* Explainable Dashboard Development
* Deployment as a Web Application

---

# Repository Structure

```bash
Earthquake-Alert-Prediction/
│
├── Earthquake_alert_prediction.ipynb
├── README.md
└── dataset/
```

---

# Learning Outcomes

This project strengthened my practical understanding of:

* Supervised Machine Learning
* Explainable AI
* SHAP Analysis
* Class Imbalance Handling
* SMOTE
* Model Evaluation
* Feature Importance Analysis
* Predictive Analytics
* Real-World Disaster Data Applications

---

# Author

## Nandana Vinothkumar

Integrated M.Tech CSE (Data Science)
VIT Vellore

### Areas of Interest

* Data Science
* Machine Learning
* Artificial Intelligence
* Explainable AI
* Predictive Analytics
* Data Analytics

---

# License

This project is developed for educational, research, learning, and portfolio purposes.
