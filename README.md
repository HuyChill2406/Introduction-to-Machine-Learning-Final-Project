# Introduction-to-Machine-Learning-Final-Project
This repository contains my final project for the course Introduction to Machine Learning. It covers three parts:
## Q1 – Optimization methods (from scratch + comparison).
Implemented Gradient Descent variants (Batch, SGD, Mini-batch) and adaptive methods (Momentum, Adagrad, RMSProp, Adam). Evaluated them on a tabular dataset (Obesity dataset) to predict Weight, comparing MSE and convergence speed.

## Q2 – Stock opening-price prediction (AAPL).
Collected Apple stock data (2020–2024) with yfinance; engineered time features; and trained multiple models: Linear Regression, Decision Tree, Random Forest, SVM, FFNN, and RNN. Included anti-overfitting techniques (cross-validation, L2 regularization, early stopping/dropout) and plotted training/validation results, then compared model performance.

## Q3 – Deep Learning study: CNN classifier.
Built a Convolutional Neural Network with TensorFlow/Keras and trained it on CIFAR-10. The notebook covers data loading/preprocessing, model design (conv base + dense head), training, evaluation, and result visualizations.

## Repository contents

- Final Project.docx – official final assignment prompt (requirements for Q1–Q3 and submission notes).

- Huy_522h0131_Final.ipynb – main notebook with all implementations, experiments, and plots.

- ObesityDataSet_raw_and_data_sinthetic.csv – dataset used in Q1.

## Tech stack
Python, NumPy, pandas, scikit-learn, TensorFlow/Keras, matplotlib/seaborn; plus yfinance (and fredapi optionally) for financial data.
