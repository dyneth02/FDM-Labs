# Genomic Analysis & Predictive Modeling Framework

This repository contains a collection of Jupyter Notebooks focused on applying advanced Machine Learning (ML) techniques to genomic datasets. The primary objective is to classify genetic disorders and subclasses using state-of-the-art boosting algorithms and unsupervised learning methods.

## 🚀 Project Overview

The core of this project revolves around the **Genetic Disorder Dataset**, where multiple models were trained and evaluated to achieve high-precision classification. The workflow includes data preprocessing, feature engineering, hyperparameter tuning, and comparative model analysis.

## 🛠 Tech Stack
- **Languages:** Python
- **ML Frameworks:** Scikit-Learn, XGBoost, CatBoost, LightGBM
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## 📂 Codebase Breakdown

### 🧬 Genetic Disorder Classification (Supervised)
- **Model Training v3 & v4:** Implementation of **LightGBM** and **XGBoost** with GPU acceleration support for multi-output classification.
- **CatBoost Models:** High-performance gradient boosting optimized for categorical genomic features, including CPU and GPU training variants.
- **Random Forest (RFC):** A robust ensemble baseline for disorder classification using scikit-learn.

### 🔍 Discovery & Clustering (Unsupervised)
- **KMeans on Genomes:** Unsupervised clustering to identify patterns within encoded genomic data.
- **Apriori Algorithm:** Association rule mining to discover hidden relationships between specific genes and disorders.
- **Geographical KMeans:** A separate implementation focused on country-level geographical clustering.

### 📊 Exploratory & Lab Work
- **DS&A Lab05:** foundational regression analysis and data exploration techniques.

## 📈 Performance & Evaluation
Models are evaluated using:
- Stratified K-Fold Cross-Validation
- Confusion Matrices
- Macro-averaged F1-Scores
- ROC/AUC Curves

## 📋 How to Use
1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install xgboost catboost lightgbm scikit-learn pandas matplotlib`.
3. The datasets (e.g., `train_encoded.csv`) are expected in the path specified within the notebooks or can be updated to your local directory.
