# MIT807 – A Risk‑Based Analytical Framework for Preventive Controls in Financial Transaction Systems Using Machine Learning


This repository contains the research work for the MIT807 mini‑dissertation at the University of Pretoria.

**Title:**  
A Risk‑Based Analytical Framework for Preventive Controls in Financial Transaction Systems Using Machine Learning

**Author:** Muphulusi Dzivhani (u18069682)  
**Course:** MIT807 Research Project  
**Institution:** University of Pretoria  
**Year:** 2026

---

## Overview

Financial fraud remains a major challenge for banks and digital payment platforms.  
This project investigates how machine learning models can be used as *preventive controls* in financial transaction systems by identifying high‑risk transactions before financial loss occurs.

The study focuses on transactional data and evaluates how different models behave under extreme class imbalance, which is typical in real‑world fraud scenarios. Emphasis is placed on risk‑based decision‑making rather than accuracy alone.

---

## Dataset

The experiments use the **Credit Card Fraud Detection** dataset obtained from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset consists of anonymised credit card transactions labelled as legitimate or fraudulent.  
No proprietary, institutional, or employer data is used in this study.

---

## Methodology

The experimental work follows a standard machine learning workflow:

1. Data preprocessing and exploration  
2. Train–test splitting and/or cross‑validation  
3. Model training  
4. Model evaluation using metrics suitable for imbalanced data  
5. Interpretation of results in the context of preventive financial controls  

Baseline and comparative models include:
- Logistic Regression (interpretable baseline)
- Tree‑based and ensemble models for comparison

Model performance is evaluated using:
- Precision
- Recall
- F1‑score
- ROC‑AUC / PR‑AUC  

Overall accuracy is not treated as the primary performance indicator due to the imbalanced nature of fraud data.

---

## Research Focus

The study addresses the following themes:

- Risk‑based fraud scoring in financial transactions  
- Impact of class imbalance on model behaviour  
- Trade‑offs between false positives and false negatives  
- Use of machine learning as a preventive control mechanism  

The goal is to develop an analytical framework that supports early intervention rather than post‑event detection.

---

## Repository Structure
