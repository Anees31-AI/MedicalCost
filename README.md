# 🩺 Medical Cost Prediction: A Machine Learning Regression Project

Welcome to my project on predicting individual medical costs using various regression algorithms and techniques. The goal is to identify the best model that can accurately predict medical charges based on features like age, BMI, smoking status, and more.

---

## 🚀 Project Overview

In this project, I:
- Explored a real-world **medical insurance cost dataset**.
- Cleaned and preprocessed the data (scaling, handling outliers, feature engineering).
- Trained and compared several regression algorithms.
- Tuned the best models to improve predictive performance.
- Visualized and compared model performance metrics.

---

## 📦 Dataset

The dataset includes:
- **Features**: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, etc.
- **Target**: `charges` (medical costs).

Source: [Kaggle Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## 🧩 Models Explored

I implemented and compared the following models:

✅ Linear Regression  
✅ Ridge Regression  
✅ Lasso Regression  
✅ ElasticNet  
✅ KNN Regression  
✅ Decision Tree Regressor  
✅ Random Forest Regressor  
✅ Gradient Boosting Regressor  
✅ XGBoost  
✅ LightGBM  
✅ CatBoost  
✅ Bayesian Ridge Regression  
✅ Support Vector Regression  
✅ Neural Network Regression (Keras)

---

## 🏆 Best Model

After evaluating models using **R² score** and **Mean Squared Error (MSE)**, **CatBoost Regressor** emerged as the top performer with an R² of **0.92** on the test set.

---

## ⚙️ Hyperparameter Tuning

To optimize performance, I applied **GridSearchCV** to the top models (like CatBoost, Random Forest, and XGBoost), tuning hyperparameters such as:
- **learning_rate**
- **max_depth**
- **iterations/estimators**

---

## 📊 Visualizations

I visualized:
- Feature importance from the best models  
- R² score comparison across all models  
- Actual vs. predicted costs for the top model  

---

## 💡 Key Takeaways

- **Proper preprocessing and scaling** are crucial for accurate predictions.  
- **Ensemble models (Random Forest, XGBoost, CatBoost)** performed better than linear models on this dataset.  
- **Tuning hyperparameters** provided a significant boost in accuracy.  

