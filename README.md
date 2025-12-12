Credit Card Fraud Detection
This project builds a machine learning model to detect fraudulent credit card transactions using a large simulated transaction dataset.​

Dataset
Simulated credit card transaction data from 2019‑01‑01 to 2020‑12‑31.​

Around 1.3M transactions for 1,000 customers and ~800 merchants.​

Features include transaction timestamp, amount, merchant, category, location, customer demographics, and a binary is_fraud label.​

All records are synthetic and used only for analytics and model development.​

Project goals
Explore transaction and customer behavior patterns.​

Engineer behavioral and geolocation features useful for fraud detection.​

Train and evaluate classification models to distinguish fraudulent vs legitimate transactions, with a focus on precision/recall.​

Methods
Data preprocessing and feature engineering with pandas and NumPy.​

Exploratory data analysis and visualizations with seaborn and matplotlib.​

Train–test split using train_test_split from scikit‑learn.​

Models: Random Forest (and Decision Tree as baseline).​

Evaluation metrics: accuracy, precision, recall, F1‑score, confusion matrix.​

Repository structure
CREDIT-CARD-FRAUD-DETECTION-1.ipynb: main notebook with EDA, feature engineering, model training, and evaluation.​

data/: folder for the transaction CSV file (not committed if large; can be downloaded from the original public source).​

How to run
Clone the repository and create a virtual environment.

Install dependencies:

pandas, numpy, scipy, scikit-learn, seaborn, matplotlib.​

Place the dataset CSV in data/ and update the notebook path, for example:

data = pd.read_csv("data/fraudTrain.csv").​

Run the notebook cells in order to reproduce the analysis and model results.​

Notes
This project was completed as part of an ML Engineer internship to demonstrate end‑to‑end fraud detection modelling, from raw transactions to evaluated models.​

No real customer or card details are used; all data is simulated for educational and research purposes.​
