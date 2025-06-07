📌 NeuraRec — AI-Powered Recommendation System
Tech Stack: XGBoost, Scikit-Learn, Surprise, Pandas, NumPy, FuzzyWuzzy, Seaborn

📈 Overview
NeuraRec is an intelligent hybrid recommendation system designed to deliver highly accurate, personalized content recommendations. It combines collaborative filtering algorithms with machine learning models to enhance prediction accuracy and recommendation relevance.

🚀 Features
✅ Achieved 85% accuracy in personalized recommendations using algorithms like SVD, KNNBaseline, and SlopeOne.

🧠 Built a hybrid recommendation engine with XGBoost, Scikit-Learn, and Surprise.

📊 Handled and analyzed over 500,000+ data points using Pandas, NumPy, and Seaborn.

🔍 Optimized models via GridSearchCV, reducing RMSE by 12%.

🤖 Integrated FuzzyWuzzy for intelligent data matching, improving recommendation relevance by 25%.

📂 Project Structure
bash
Copy
Edit
NeuraRec/
├── data/                  # Raw and processed dataset files
├── models/                # Trained models and serialized pickles
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── src/                   # Core source code (model training, preprocessing)
│   ├── preprocessing.py
│   ├── recommenders.py
│   └── utils.py
├── results/               # Visualizations, performance metrics
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
🛠 How It Works
Data Preprocessing

Cleaned and normalized large-scale data using Pandas and NumPy.

Handled missing data and outliers to improve model input quality.

Modeling

Applied various Surprise algorithms like SVD, SlopeOne, KNNBaseline.

Developed hybrid ensemble using XGBoost for improved collaborative predictions.

Evaluation

Used metrics such as RMSE, MAE, and Top-N Precision.

Grid search tuning for model selection and performance optimization.

Post-processing

FuzzyWuzzy used to enhance string matching and ranking of recommendations.

📊 Results
RMSE: Reduced by 12% after hyperparameter tuning.

Recommendation Relevance: Improved by 25% post FuzzyWuzzy integration.

Accuracy: Reached 85% for top-n personalized recommendations.
