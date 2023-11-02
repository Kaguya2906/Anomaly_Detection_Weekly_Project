# Anomaly Detection Weekly Project

## Introduction
Anomaly detection is the identification of rare events that significantly deviate from the norm. Such events, often termed as Outliers, Noises, Novelties, or Exceptions, don't conform to expected behavior. These anomalies can have adverse effects on business operations, potentially causing significant losses. Therefore, timely and accurate detection is crucial to mitigate future risks, making anomaly detection an essential facet of data science. Many data professionals engage in detecting and preventing fraud, and other forms of risk mitigation.

## About this Repository
This repository showcases a collection of projects I undertook during my course APAN 5420: Anomaly Detection in Summer 2023 at Columbia University. Throughout this course, I was extensively trained on pinpointing anomalies across vast datasets pertinent to various business scenarios. The industries in focus were **FINANCIAL, MORTGAGE, and HEALTHCARE.** Through this repository, I aim to share my explorations of industry-specific research and my understanding of a series of robust and transparent anomaly detection algorithms. 

## Environment Setup
Below are the open-source framework that I used in the projects and their documentation:
- Scikit-Learn: https://scikit-learn.org/stable/install.html
- Tensorflow: https://www.tensorflow.org/install
- PyOD: https://pyod.readthedocs.io/en/latest/install.html
- H2O.ai: https://h2o.ai/
- SHAP: https://shap.readthedocs.io/en/latest/

## Repository Breakdown

### Notebooks 02-04
Display of my exploration process and the evolving strategies I employed for **Exploratory Data Analysis** (EDA). Each industry requires a distinct approach to feature engineering, and the insights from the EDA phase served as crucial reference points for subsequent stages. For each dataset, I engineered 10-15 new features specifically aimed at detecting outliers. 
The professional methodologies for **feature engineering** tailored to anomaly detection in each industry that I worked on are:
- Financial Sector: **R-F-M** principles.
- Mortgage Sector: **Weight-of-Evidence(WOE)** 
- Healthcare Sector: **F-W-A** method.

The efficacy of these features was later assessed during the modeling phase.

### Notebooks 05-11
Application of **11** distinct anomaly detection models on the refined datasets, encompassing both unsupervised and supervised machine learning techniques.
- **Unsupervised** Models: HBOS, ECOD, IsolationForest, KNN, PCA, and AutoEncoder.
- **Supervised** Models: Sampling Methods (Undersampling, Oversampling), XGB (GBM, GLM), Deep Learning, and AutoML (Ensembled).

### Notebook 12
Evaluation of Feature Contributions with SHAP Values, delving deeper into model interpretability, a critical aspect often overlooked in the complex landscape of machine learning.

## Code References
- H2O Balance Classes: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/algo-params/balance_classes.html
- H2O XGB: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/xgboost.html?highlight=xgb
- H2O GBM: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/gbm.html
- H2O GLM: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/glm.html?highlight=glm
- H2O Deep Learning: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/deep-learning.html
- H2O AutoML: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html
- SHAP: https://shap.readthedocs.io/en/latest/
