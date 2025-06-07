# 📌 NeuraRec — AI-Powered Recommendation System

**Tech Stack:** `XGBoost`, `Scikit-Learn`, `Surprise`, `Pandas`, `NumPy`, `FuzzyWuzzy`, `Seaborn`

## 📈 Overview

**NeuraRec** is an intelligent hybrid recommendation system designed to deliver highly accurate, personalized content recommendations. It combines collaborative filtering algorithms with machine learning models to enhance prediction accuracy and recommendation relevance.

---

## 🚀 Features

- ✅ Achieved **85% accuracy** in personalized recommendations using algorithms like `SVD`, `KNNBaseline`, and `SlopeOne`.
- 🧠 Built a **hybrid recommendation engine** with `XGBoost`, `Scikit-Learn`, and `Surprise`.
- 📊 Handled and analyzed over **500,000+ data points** using `Pandas`, `NumPy`, and `Seaborn`.
- 🔍 Optimized models via `GridSearchCV`, reducing **RMSE by 12%**.
- 🤖 Integrated `FuzzyWuzzy` for intelligent data matching, improving recommendation relevance by **25%**.

---

## 📂 Project Structure

NeuraRec/
├── data/ # Raw and processed dataset files
├── models/ # Trained models and serialized pickles
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── src/ # Core source code (model training, preprocessing)
│ ├── preprocessing.py
│ ├── recommenders.py
│ └── utils.py
├── results/ # Visualizations, performance metrics
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🛠 How It Works

### 🔹 Data Preprocessing

- Cleaned and normalized large-scale data using `Pandas` and `NumPy`.
- Handled missing values and outliers to improve model input quality.

### 🔹 Modeling

- Applied collaborative filtering models like `SVD`, `SlopeOne`, `KNNBaseline` using `Surprise`.
- Built an ensemble hybrid model incorporating `XGBoost` for refined prediction.

### 🔹 Evaluation

- Evaluated using **RMSE**, **MAE**, and **Top-N Precision**.
- Performed hyperparameter tuning using `GridSearchCV`.

### 🔹 Post-Processing

- Used `FuzzyWuzzy` for better string matching and boosting recommendation ranking quality.

---

## 📊 Results

- **RMSE:** Reduced by **12%** with hyperparameter optimization.
- **Recommendation Relevance:** Improved by **25%** after FuzzyWuzzy integration.
- **Accuracy:** Achieved **85%** accuracy in personalized recommendations.

---
