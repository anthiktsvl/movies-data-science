# movies-data-science

🎬 Predicting Movie Box Office Revenue with Data Science & AI
End-to-end machine learning project focused on predicting movie box office revenue and identifying the key drivers of financial success in the film industry.
This project demonstrates practical skills in data cleaning, feature engineering, exploratory analysis, machine learning, and model interpretation using real-world data.
🔍 Project Overview
Built a full data science pipeline using a large movie dataset (63,000+ entries)
Cleaned and engineered features to handle missing values, skewed distributions, and categorical data
Trained and evaluated multiple regression models
Selected and interpreted the best-performing AI model
📌 Goal: Predict movie revenue and understand what drives box office success.
📊 Dataset
Raw size: ~63,000 movies
Final modeling dataset: 8,698 movies
Features include:
Budget & revenue
Audience engagement (vote count, popularity)
Genre, language, runtime
Release timing
🧠 Machine Learning Approach
Problem Type: Supervised regression
Models Implemented:
Baseline (mean prediction)
Linear Regression
Decision Tree Regressor
Random Forest Regressor (best model)
Evaluation Metrics:
R²
MAE
RMSE
🏆 Best Performance:
Random Forest achieved R² ≈ 0.81 on unseen data.
🔑 Key Insights
Budget and audience engagement are the strongest predictors of revenue
Popularity and vote count outperform qualitative features like genre
High-performing genres (Animation, Adventure, Sci-Fi) benefit from scale
Ensemble models significantly outperform simpler baselines
📂 Project Structure
├── DataScienceMovies.ipynb     # Main analysis and ML pipeline
├── movies.csv                 # Raw dataset
├── cleaned_movies.csv         # Cleaned dataset
└── README.md                  # Project overview
🛠️ Tools & Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
scikit-learn
🚀 What This Project Demonstrates
✔ Real-world data cleaning & preprocessing
✔ Feature engineering & EDA
✔ Supervised machine learning
✔ Model comparison & evaluation
✔ Interpretability using feature importance
✔ Communication of insights
🔮 Future Improvements
Predict profitability instead of revenue
Add cast, director, and marketing spend features
Experiment with Gradient Boosting (XGBoost, LightGBM)
Time-based train/test splits for realistic forecasting
📌 About
This project was developed as part of a data science portfolio and is intended to showcase applied machine learning skills on real-world data.
