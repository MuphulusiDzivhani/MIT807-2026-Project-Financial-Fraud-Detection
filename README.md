# Risk-Based Preventive Controls for Financial Transactions

This repository contains the code and analysis for my MIT 807 mini‑dissertation titled:

**“A Risk‑Based Analytical Framework for Preventive Controls in Financial Transaction Systems Using Machine Learning.”**

The aim of this project is to investigate how machine learning models can be used as *preventive controls* in financial transaction systems by identifying high‑risk transactions before financial loss occurs.

---

## Project Overview

Financial institutions rely on risk‑based controls to prevent fraud while minimising unnecessary disruption to legitimate customers.  
This study evaluates different machine learning models on transactional data and analyses how their outputs can support preventive decision‑making.

The focus is not only on prediction accuracy, but on:
- risk scoring,
- trade‑offs between false positives and false negatives,
- and model behaviour in highly imbalanced datasets.

---

## Dataset

The experiments use a publicly available credit card fraud dataset obtained from Kaggle.

The dataset consists of anonymised transaction records, where each transaction is labelled as either legitimate or fraudulent.  
No proprietary, employer, or sensitive personal data is used in this project.

---

## Methodology

The experimental work follows a standard machine learning workflow:

1. Data loading and preprocessing  
2. Train‑test split and/or cross‑validation  
3. Model training  
4. Model evaluation using appropriate metrics for imbalanced data  
5. Interpretation of results in the context of preventive financial controls  

Baseline and comparative models include:
- Logistic Regression (interpretable baseline)
- Tree‑based or ensemble models (for comparison)

Evaluation focuses on metrics such as:
- Precision
- Recall
- ROC‑AUC / PR‑AUC
rather than overall accuracy.

---

## Repository Structure
