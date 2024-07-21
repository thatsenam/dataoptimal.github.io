---
title: "Insurance Fraud in Python"
date: 2020-11-28

header:
  image: "/images/scope2.jpg"
  teaser: "/images/air/Infographic.PNG"
excerpt: "Fraud Detection, Binary Classification, Imbalanced Target, Python"
mathjax: "true"
---

## Classification Prediction

### Summary

The goal of this project was to use Python to identify significant features in fraudulent insurance claim transactions and to design predictive classification models to predict whether fraud was reported on the insurance claim transaction. The project addressed the imbalanced target variable by weighting the classes. Logistic Regression, Support Vector Machine Classification, and Random Forest models were tested. The paper walks through the data understanding and preparation, different models tested, methodology, and evaluation of the project.

### Tools

* Scikit-learn
* Seaborn
* Matplotlib
* Yellowbrick
* Numpy
* Pandas
* Scipy
* Patsy
* Tabulate
* Counter

**Data:** [claims](https://www.kaggle.com/patilk1/fraudulentinsuranceclaim){:target="_blank"}

### Methodology

Compared multiple versions of models that varied techniques for data-splitting, the imbalanced target variable, and feature selection.

### Models / Methods / Metrics

* Random Forest
* Logistic Regression / LASSO Logistic Regression
* Support Vector Classification
* Principal Component Analysis
* Log-Transformation and Scaling
* GridSearch
* Recall


## Project Preview

### Exploratory Data Analysis

This project utilized the EDA from this Exploratory Data Analysis and Hypothesis Testing project: [EDA.](https://github.com/MaryDonovanMartello/EDA-and-Hypothesis-Testing){:target="_blank"}

### Principal Component Analysis

PCA was implemented because of multicollinearity between groups of input variables.

### Evaluation

![RESULTS1](/images/fraud/Results2.PNG)

### The Complete Project: [here](https://github.com/MaryDonovanMartello/Insurance-Fraud-in-Python){:target="_blank"}.
<!--   teaser: "/images/scope3.jpg" -->
