# Cybersecurity-Threat-Detection-using-Big-Data-Analytics
This project aims to develop a machine learning-based classification system that can automatically analyze network traffic data and accurately identify different types of cyber threats.
The system will process network flow features from the CIC-IDS2017 dataset and classify each instance into multiple categories such as Benign, DDoS, Brute Force, Port Scan, Botnet, and Web Attacks.

Features
Multi-class classification of network traffic
Detects attacks like:
DDoS
Brute Force
Port Scan
Botnet
Web Attacks
Data preprocessing:
Missing value handling
Feature normalization
Exploratory Data Analysis (EDA):
Class distribution
Correlation analysis
Machine Learning models:
Random Forest
XGBoost
Model evaluation:
Confusion Matrix

Tech Stack

Language:
Python

Libraries:
pandas: data handling
numpy: numerical operations
matplotlib, seaborn: visualization
scikit-learn: ML models & evaluation
xgboost: advanced boosting model
shap: model explainability

Tools:
Google Colab / Jupyter Notebook
GitHub (for version control)

Dataset:
CIC-IDS2017 (network intrusion dataset)
Precision, Recall, F1-score
Handles class imbalance (class weights / SMOTE)
Model explainability using SHAP

Project structure:
project/
│── data/
│── notebooks/
│── models/
│── README.md

Installation guide
1. close repository
   git clone https://github.com/harshitaduggal/Cybersecurity-Threat-Detection-using-Big-Data-Analytics.git
2. Install dependencies
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap jupyter
3.Run jupyter
   jupyter notebook
