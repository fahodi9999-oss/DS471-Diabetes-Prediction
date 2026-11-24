# Diabetes Prediction Using Machine Learning

## Project Overview
This academic project was developed for the DS471 Machine Learning course at Saudi Electronic University (SEU).

The project investigates the effectiveness of machine learning algorithms in predicting diabetes status using demographic, lifestyle, and health-related indicators.

## Dataset
- Source: UCI Machine Learning Repository
- Dataset: CDC Diabetes Health Indicators
- Dataset ID: 891
- Original records: 253,680
- Input features: 21
- Target variable: Diabetes_binary

[Dataset Source](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators)

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Artificial Neural Network (ANN)

## Project Workflow
1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Data Splitting (70% Training, 15% Validation, 15% Testing)
4. Model Selection and Development
5. Model Training and Hyperparameter Optimization
6. Model Evaluation and Performance Comparison

## Model Performance

| Model | Accuracy | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.73 | 0.76 | 0.44 | 0.8216 |
| Random Forest | 0.77 | 0.71 | 0.46 | 0.8267 |
| Neural Network | 0.72 | 0.80 | 0.44 | 0.8297 |

Random Forest achieved the highest accuracy and F1-score, while the Artificial Neural Network achieved the highest recall and ROC-AUC.

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- UCI ML Repository

## How to Run
1. Download the Machine_Learning_DS471.ipynb file.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Run all notebook cells in sequential order.

## Project File
[Machine Learning Notebook](Machine_Learning_DS471.ipynb)

## Project Authors
- Fahad Al Malki
- Faris Al Shuaibi

## Academic Information
- University: Saudi Electronic University
- College: Computing and Informatics
- Program: Data Science
- Course: DS471 - Machine Learning
- Year: 2026

## Disclaimer
This project is intended for academic and research purposes only and is not a substitute for professional medical diagnosis.
