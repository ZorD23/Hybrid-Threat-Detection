# Hybrid-Threat-Detection

## Overview

This project presents a Hybrid AI-based Intrusion Detection System (IDS) that combines supervised and unsupervised machine learning techniques to improve cyber threat detection. The system analyzes multiple cybersecurity datasets and integrates their predictions using a weighted ensemble scoring approach.

## Features

- Hybrid detection using Random Forest and Isolation Forest
- Multi-source cybersecurity dataset analysis
- Automated data preprocessing and feature engineering
- Adaptive threshold optimization
- Weighted ensemble scoring
- Model persistence using Joblib

## Datasets

The project uses the following publicly available datasets:

- CICIDS2017
- CERT Insider Threat Dataset
- HDFS Log Dataset

> Note: Due to dataset licensing and size limitations, the datasets are not included in this repository.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Machine Learning Models

- Random Forest Classifier
- Isolation Forest

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Workflow

1. Data Preprocessing
2. Feature Engineering
3. Train-Test-Validation Split
4. Random Forest Training
5. Isolation Forest Training
6. Threshold Optimization
7. Hybrid Score Fusion
8. Global Ensemble Scoring
9. Model Evaluation
10. Save Trained Models

## Repository Structure


Hybrid-AI-Cyber-Threat-Detection/
│
├── Hybrid_AI_IDS.ipynb
├── README.md




## Results

The hybrid model combines supervised and unsupervised learning to improve threat detection performance across multiple cybersecurity datasets.

## Author

Aman Raj
