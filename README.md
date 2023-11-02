# Anomaly Detection Weekly Project
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/lanru-fu-a55376162/)[![Instagram Badge](https://img.shields.io/badge/Instagram-Profile-informational?style=flat&logo=instagram&logoColor=white&color=1CA2F1)](https://www.instagram.com/rurus_memo/)


<img width="641" alt="Screenshot 2023-11-02 at 1 01 23 PM" src="https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/assets/38816901/55979cb9-4bbe-4377-bb11-8ce8516ee218">

## Introduction
Anomaly detection is the identification of rare events that significantly deviate from the norm. Such events, often termed as Outliers, Noises, Novelties, or Exceptions, don't conform to expected behavior. These anomalies can have adverse effects on business operations, potentially causing significant losses. Therefore, timely and accurate detection is crucial to mitigate future risks, making anomaly detection an essential facet of data science. Many data professionals engage in detecting and preventing fraud, and other forms of risk mitigation.

## About this Repository
This repository showcases a collection of projects I undertook during my course APAN 5420: Anomaly Detection in Summer 2023 at Columbia University. Throughout this course, I was extensively trained on pinpointing anomalies across vast datasets pertinent to various business scenarios. The industries in focus were **FINANCIAL, MORTGAGE, and HEALTHCARE.** Through this repository, I aim to share my explorations of industry-specific research and my understanding of a series of robust and transparent anomaly detection algorithms. 

## Environment Setup
Below are the open-source framework that I used in the projects and their documentation:
- [Scikit-Learn](https://scikit-learn.org/stable/install.html): A free software machine learning library for the Python programming language.
- [Tensorflow](https://www.tensorflow.org/install): An end-to-end platform for machine learning.
- [Python Outlier Detection(PyOD)](https://pyod.readthedocs.io/en/latest/install.html): The most comprehensive Python library for detecting outlying objects in multivariate data.
- [H2O.ai](https://h2o.ai/): An open source, in-memory, distributed, fast, and scalable machine learning and predictive analytics platform. 
- [SHAP](https://shap.readthedocs.io/en/latest/): A theoretic approach to explain the output of any machine learning model.

## Repository Breakdown

### Notebooks 02-04
Display of my exploration process and the evolving strategies I employed for **Exploratory Data Analysis** (EDA). Each industry requires a distinct approach to feature engineering, and the insights from the EDA phase served as crucial reference points for subsequent stages. For each dataset, I engineered 10-15 new features specifically aimed at detecting outliers. 
The professional methodologies for **feature engineering** tailored to anomaly detection in each industry that I worked on are:
- [Financial Sector](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/02.CreditCard%20EDA%2CFeature%20Engineering.ipynb): **R-F-M** principles.
- [Mortgage Sector](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/03.Mortgage%20EDA%2CFeature%20Engineering.ipynb): **Weight-of-Evidence(WOE)** 
- [Healthcare Sector](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/04.HealthCare%20EDA%2CFeature%20Engineering.ipynb): **F-W-A** method.

The efficacy of these features was later assessed during the modeling phase.

### Notebooks 05-11
Application of **11** distinct anomaly detection models on the refined datasets, encompassing both unsupervised and supervised machine learning techniques.
- **Unsupervised** Models(PyOD): [HBOS](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/05.HBOS%2CECODs.ipynb), [ECOD](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/05.HBOS%2CECODs.ipynb), [IsolationForest](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/07.AutoEncoder%2CIForest.ipynb), [KNN](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/06.PCA%2CKNN.ipynb), [PCA](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/06.PCA%2CKNN.ipynb), and [AutoEncoder](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/07.AutoEncoder%2CIForest.ipynb).
- **Supervised** Models(H2O.ai): Sampling Methods ([Undersampling](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/08.UnderSampling.ipynb), [Oversampling](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/09.OverSampling.ipynb)), [XGB](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/10.GBM%2CXGB%2CDeepLearning.ipynb) ([GBM](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/10.GBM%2CXGB%2CDeepLearning.ipynb), [GLM](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/11.GLM%2CAutoML.ipynb)), [Deep Learning](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/10.GBM%2CXGB%2CDeepLearning.ipynb), and [AutoML](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/11.GLM%2CAutoML.ipynb) (Ensembled).

### Notebook 12
Evaluation of Feature Contributions with [SHAP Values](https://github.com/Kaguya2906/Anomaly_Detection_Weekly_Project/blob/main/12.Random%20Forest%2CSHAP%20Values.ipynb), delving deeper into model interpretability, a critical aspect often overlooked in the complex landscape of machine learning.

## Code References
- [H2O Balance Classes](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/algo-params/balance_classes.html)
- [H2O XGB](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/xgboost.html?highlight=xgb)
- [H2O GBM](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/gbm.html)
- [H2O GLM](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/glm.html?highlight=glm)
- [H2O Deep Learning](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/deep-learning.html)
- [H2O AutoML](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html)
- [SHAP](https://shap.readthedocs.io/en/latest/)

## Find Me All Around the Web
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/braydon-coyer/)
