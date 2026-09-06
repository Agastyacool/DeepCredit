# 💳 DeepCredit
## Explainable Deep Learning Credit Risk Prediction System

DeepCredit is a FinTech machine learning project that uses a Deep Neural Network to estimate the probability of credit card default.

The project combines predictive modeling with Explainable AI to understand which financial characteristics influence model predictions.

## 🎯 Project Objective

The objective is to build a deep learning system that can:

- Predict credit default probability
- Handle class imbalance
- Engineer meaningful financial risk features
- Optimize the classification threshold
- Explain predictions using SHAP
- Simulate how financial changes can affect predicted risk

## 🧠 Machine Learning Approach

The project uses a TensorFlow/Keras Deep Neural Network with:

- Dense neural network layers
- ReLU activation
- Dropout regularization
- Sigmoid output layer
- Adam optimizer
- Binary cross-entropy loss
- Class weighting
- Early stopping

## 🔍 Explainable AI

SHAP (SHapley Additive exPlanations) is used to:

- Identify important features
- Understand model behavior
- Explain individual customer predictions

## 🔄 What-If Credit Risk Simulator

The project includes a simulation that changes customer financial characteristics and observes how the predicted default probability changes.

## 📊 Feature Engineering

Additional financial risk features include:

- Average Bill
- Average Payment
- Credit Utilization
- Payment-to-Bill Ratio
- Delayed Months
- Maximum Delay
- Average Delay

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- SHAP
- Jupyter Notebook

## 📁 Project Files

- `DeepCredit_Deep_Learning_Model.ipynb` — Complete project notebook
- `DeepCredit_model.keras` — Trained neural network
- `DeepCredit_scaler.pkl` — Feature scaling model

## ⚠️ Disclaimer

This project is intended for educational and portfolio purposes.

It is not intended for real-world lending decisions. Production credit-risk systems require additional validation, fairness testing, privacy protection, regulatory compliance, monitoring, and human oversight.

## 🚀 Future Improvements

- Compare against XGBoost and other ML models
- Hyperparameter optimization
- Fairness and bias analysis
- Model deployment through an API or web application
- Continuous model monitoring
