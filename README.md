# MIT807 – Challenges and Opportunities in the Digital Transformation of Public Sector Service Delivery in South Africa

This repository contains the research work for the MIT807 mini‑dissertation at the University of Pretoria.

**Title:**  
Challenges and Opportunities in the Digital Transformation of Public Sector Service Delivery in South Africa

**Author:** Muphulusi Dzivhani (u18069682)  
**Course:** MIT807 Research Project  
**Institution:** University of Pretoria  
**Year:** 2026

---

## Overview

Digital transformation is a key priority for public sector organisations, yet service delivery often remains fragmented, slow, and difficult for citizens to navigate. This project investigates how **data-driven analysis** can support public sector digital transformation by improving visibility into service delivery patterns and performance.

The study focuses on **public service request and complaint data** and demonstrates how an interpretable probabilistic model (**Multinomial Naïve Bayes**) can be used to:

- classify and organise service requests into meaningful categories,
- reveal trends in citizen service demand over time,
- analyse resolution/response patterns (where available),
- generate evidence-based insights that support service improvement initiatives.

> **Important:** This research is not implementing a government platform. It provides analytical evidence that can inform digital transformation decisions.

---

## Research Focus

The dissertation explores:

- Challenges affecting digital public service delivery (fragmentation, inconsistent responsiveness, limited performance visibility)
- Opportunities for improved service delivery using service request analytics
- Interpretable classification using Naïve Bayes to support transparency and accountability
- Practical, reproducible analysis using open data and Python

---

## Datasets (Public / Open)

This project uses **publicly available** datasets suitable for reproducible research and Python-based analysis.

Primary quantitative datasets include:

1. **Service Request / Complaint Data (Benchmark)**
   - Example: Kaggle municipal 311-style service request datasets  
   - Used to model high-volume service request classification and trend analysis

2. **Municipal Open Data (Supplementary)**
   - Example: City of Cape Town Open Data Portal datasets (where applicable)
   - Used for contextual service delivery indicators

3. **Benchmarking Indicators (Context)**
   - United Nations E-Government Survey / eGov Knowledgebase indicators

Policy and regulatory documents (e.g., Government Gazettes, DPSA standards) are used for **contextual grounding**, not quantitative modelling.

---

## Methodology (High Level)

The workflow follows a standard data science pipeline:

1. Data ingestion and cleaning  
2. Exploratory data analysis (EDA)  
3. Text preprocessing:
   - tokenisation, stopword removal, normalisation (where relevant)
   - TF‑IDF vectorisation
4. Classification using **Multinomial Naïve Bayes**
5. Evaluation:
   - accuracy, precision, recall, F1-score
   - confusion matrix
6. Visualisation:
   - trends over time, category frequencies, and performance indicators

---

## Ethics and Data Protection

- Only publicly available and/or anonymised datasets are used.
- No confidential, taxpayer, or employer-proprietary data is included.
- Analysis is performed at aggregate level and presented in a non-attributable manner.
- The project follows responsible data use principles: transparency, proportionality, and accountability.

---

## Repository Structure

```text
.
├── data/
│   ├── raw/                 # Original downloaded datasets (do not modify)
│   ├── processed/           # Cleaned/processed datasets for modelling
│
├── notebooks/
│   ├── 01_eda.ipynb         # Exploratory data analysis
│   ├── 02_preprocessing.ipynb
│   ├── 03_naive_bayes.ipynb # Model training + evaluation
│
├── src/
│   ├── preprocessing.py     # Text cleaning + TF-IDF functions
│   ├── model.py             # Naïve Bayes training + evaluation utilities
│
├── reports/
│   ├── figures/             # Saved charts and plots for the dissertation
│   ├── proposal/            # Proposal drafts (LaTeX/PDF)
│
├── README.md
└── requirements.txt
