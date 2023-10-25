# Credit Card Fraud Detection using Scikit-Learn and Snap ML

This project is a practical exercise in building machine learning models for credit card fraud detection. It leverages Scikit-Learn and Snap ML to train classification models that identify fraudulent credit card transactions.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Features](#features)
- [Data Set Analysis](#data-set-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Training Speedup Comparison](#training-speedup-comparison)
- [Model Evaluation](#model-evaluation)
- [Hinge Loss Metric](#hinge-loss-metric)
- [Compatibility with Scikit-Learn](#compatibility-with-scikit-learn)
- [Exploring Snap ML](#exploring-snap-ml)
- [Credits](#credits)
- [License](#license)

## Introduction

In this project, we use two popular classification models: Decision Tree and Support Vector Machine (SVM) to identify fraudulent credit card transactions. The dataset used is from credit card transactions made by European cardholders in September 2013. We aim to build models to assess whether a credit card transaction is legitimate or fraudulent.

The project is divided into sections to cover essential tasks, including data preprocessing, model training, and evaluation. Scikit-Learn and Snap ML Python APIs are used for model development, providing efficient solutions for both CPU and GPU implementations.

## Getting Started

To run the project, you can follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/AmalSatheesan/Credit-Card-Fraud-Detection

2. Install the required libraries and dependencies:
    
    * pip install opendatasets
    * pip install snapml

    
3. Run the Jupyter Notebook:
    jupyter notebook credit_card_fraud_detection.ipynb

4. Follow the code and comments in the notebook to understand the process and results.

## Project Structure

The project directory is structured as follows:

- `credit-card-fraud-detection/`
  - `credit_card_fraud_detection.ipynb`
  - `data/`
    - `creditcard.csv`
  - `README.md`
  - `.gitignore`


## Features
Data preprocessing, including scaling and normalization.
Model training using Scikit-Learn and Snap ML.
Comparison of training speedup between Scikit-Learn and Snap ML.
Model evaluation using ROC-AUC and hinge loss metrics.
Compatibility with Scikit-Learn metrics and data preprocessors.
Data Set Analysis
The project begins with an analysis of the credit card fraud dataset. It includes insights into the dataset's structure, class distribution, and challenges associated with imbalanced data.

## Data Preprocessing
Data preprocessing tasks are performed to prepare the dataset for modeling. This includes feature scaling and normalization.

## Model Training
Two classification models, Decision Tree and Support Vector Machine (SVM), are trained using both Scikit-Learn and Snap ML. The training process is assessed for efficiency and speed.

## Training Speedup Comparison
The training speedup between Snap ML and Scikit-Learn models is compared, highlighting the advantage of accelerated training with Snap ML.

## Model Evaluation
The models are evaluated using ROC-AUC scores to measure classification performance on the test data.

## Hinge Loss Metric
Hinge loss metrics are calculated for both Scikit-Learn and Snap ML models. The hinge loss measures the margin between predicted scores and true labels, providing insights into classification performance.

## Compatibility with Scikit-Learn
The project demonstrates that Snap ML seamlessly accelerates Scikit-Learn applications while maintaining compatibility with Scikit-Learn metrics and data preprocessors.

## Exploring Snap ML
For further examples and exploration of Snap ML's capabilities, you can visit the Snap ML Examples page. Snap ML offers a powerful toolkit for efficient and high-performance machine learning, making it a valuable addition to your data science toolkit.

## Credits
The dataset used in this project is from Kaggle: Credit Card Fraud Detection.
