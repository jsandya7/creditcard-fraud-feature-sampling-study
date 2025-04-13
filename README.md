# A Machine Learning Based Framework for Credit Card Fraud Detection: Comparative Study of Resampling and Classification Techniques
**Dataset:** [Kaggle - Credit Card Transactions Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

This repository presents a comprehensive and explainable machine learning pipeline for detecting fraudulent credit card transactions. Developed using the CRISP-DM methodology, this project systematically explores the impact of feature engineering and various sampling techniques on classification performance across multiple models.

##  Project Overview

Credit card fraud poses a major challenge to financial institutions due to its rarity, evolving patterns, and high business impact. This project addresses:

- **Severe class imbalance** in fraud datasets  
- **False positives and false negatives** in fraud detection  

We evaluate several supervised classifiers across three resampling strategies and a suite of engineered features derived from behavioral, statistical, and temporal dimensions.

## Methodology

- **Framework:** CRISP-DM (Cross-Industry Standard Process for Data Mining)
- **Dataset:** [Kaggle - Credit Card Transactions Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- **Resampling Techniques:**  
  - SMOTE (Synthetic Minority Oversampling Technique)  
  - ADASYN (Adaptive Synthetic Sampling)  
  - Random Undersampling (RUS)
- **Models Evaluated:**  
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
  - K-Nearest Neighbors (KNN)

## Key Features Engineered

- **Statistical Metrics:** Average, standard deviation, Z-score of amount per card  
- **Behavioral Patterns:** Daily, weekly, monthly transaction frequency  
- **Time-based Features:** Hour of transaction, day of week, time since last transaction  
- **Rolling Windows:** 7-day rolling sums and counts  
- **Location-based:** Distance between cardholder and merchant  
- **Risk Encodings:** Fraud rate by region and occupation  

##  Results Summary

- **XGBoost + SMOTE** achieved the highest F1-score of **0.90** on the test set  
- Feature engineering significantly boosted performance across all models  
- ROC AUC scores and confusion matrices used for additional evaluation  


## Contact

For any queries or collaborations, reach out via:

- sandya.jaleshkumar2@mail.dcu.ie  
- ashwanth.sathish2@mail.dcu.ie  
- chandana.daggupati2@mail.dcu.ie  
- vengavamsikrishna.maanam2@mail.dcu.ie  

---

> This project was developed as part of the MSc in Computing (AI/Data Analytics), Dublin City University.


