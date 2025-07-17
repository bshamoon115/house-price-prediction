# 🏠 House Price Prediction using California Housing Data

This project builds a regression model to predict house prices based on features like average income, house age, population, and location data. It uses the California Housing dataset and applies a Linear Regression model for prediction.

## 📌 Objective
To predict median house prices in California districts using supervised machine learning (regression).

## 📊 Dataset
The dataset is built into `sklearn.datasets`:
- `fetch_california_housing()`

It contains:
- 20,640 entries
- 8 features:
  - Median income
  - House age
  - Average rooms
  - Population
  - Latitude/Longitude, etc.

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, train_test_split, metrics)

## 🧠 ML Workflow
1. Load and explore the dataset
2. Visualize relationships between features
3. Split data into train and test sets
4. Train Linear Regression model
5. Evaluate using R² score and Mean Squared Error

## 📈 Results
The model achieved an R² score of approximately **[insert score, e.g., 0.6–0.7]**, indicating decent performance for predicting housing prices.
