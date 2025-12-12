# Credit Card Fraud Detection 💳🔍  

This project demonstrates an end-to-end **machine learning pipeline for credit card fraud detection** using a large simulated transaction dataset.  
The focus is on data exploration, feature engineering, model training, and evaluation for highly imbalanced classification problems.

---

## 📊 Dataset (Not Included)

- Simulated credit card transaction data  
- Time period: **2019-01-01 to 2020-12-31**  
- ~**1.3 million transactions**  
- **1,000 customers** and ~**800 merchants**  
- Features include:
  - Transaction timestamp  
  - Transaction amount  
  - Merchant and category  
  - Location information  
  - Customer demographics  
  - Target label: **`is_fraud` (binary)**  

> ⚠️ The dataset is **not included in this repository**.  
> All records are **synthetic** and were used only for analytics and model development during the project.

---

## 🎯 Project Goals

- Explore transaction and customer behavior patterns  
- Engineer **behavioral and geolocation features** useful for fraud detection  
- Train and evaluate classification models to distinguish fraudulent vs legitimate transactions  
- Emphasize **precision, recall, and F1-score**, which are critical for imbalanced fraud datasets  

---

## 🧪 Methods & Approach

- Data preprocessing & feature engineering using **Pandas** and **NumPy**  
- Exploratory Data Analysis (EDA) with **Seaborn** and **Matplotlib**  
- Train–test split using `train_test_split` from **scikit-learn**  
- Models implemented:
  - **Decision Tree** (baseline)  
  - **Random Forest** (primary model)  
- Evaluation metrics:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  

---

## 📁 Repository Contents

- `CREDIT-CARD-FRAUD-DETECTION-1.ipynb`  
  - Main notebook containing:
    - EDA  
    - Feature engineering  
    - Model training  
    - Model evaluation  

> This notebook is intended to showcase the **approach, methodology, and analysis**, even without direct access to the dataset.

---

## ▶️ How to Use This Repository

- Review the notebook to understand the **fraud detection workflow**
- Examine feature engineering strategies and evaluation metrics
- Use the notebook as a **reference template** for similar fraud detection problems
- The code can be adapted to other public or proprietary transaction datasets

---

## 📝 Notes

- This project was completed as part of an **ML Engineer internship**  
- No real customer or card details are used  
- All data referenced is **synthetic** and for educational or research purposes only  

---
