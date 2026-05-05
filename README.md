# 🏡 Boston Housing Price Prediction

## 📌 Project Overview
This repository contains a Machine Learning project that predicts the median value of owner-occupied homes in Boston based on various structural and neighborhood features. 

The primary goal of this project is to demonstrate an end-to-end machine learning workflow, including **data exploratory analysis**, **data preprocessing**, and building regression models using **Scikit-Learn**.

## 📊 Dataset
The dataset used is the famous **Boston House Prices Dataset**, sourced from [Kaggle](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices). 
It contains 506 samples and 14 features, including:
* `RM`: Average number of rooms per dwelling
* `CRIM`: Per capita crime rate by town
* `LSTAT`: Percentage of lower status of the population
* `MEDV`: Median value of owner-occupied homes in $1000s (Target Variable)

## 🛠️ Technologies & Tools Used
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Linear Regression, Random Forest Regressor)

## ⚙️ Project Workflow
1. **Data Loading & Inspection:** Understanding the shape and statistical summary of the data.
2. **Exploratory Data Analysis (EDA):** Visualizing correlations using heatmaps and scatter plots to identify the most important features (e.g., `RM` and `LSTAT`).
3. **Data Preprocessing:** Handling missing values, feature scaling (StandardScaler), and splitting the data into training and testing sets (80/20 split).
4. **Model Training:** Training multiple regression models to compare performance.
5. **Model Evaluation:** Evaluating the models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).

## 📈 Results
* **Linear Regression:** Achieved an R² score of `[Insert Score, e.g., 0.72]` and a Mean Absolute Error of `[Insert MAE, e.g., $3,400]`.
* **Random Forest Regressor:** Achieved an R² score of `[Insert Score, e.g., 0.85]` and a Mean Absolute Error of `[Insert MAE, e.g., $2,100]`.

*Conclusion:* The `[Insert best model]` performed the best, capturing the non-linear relationships in the data more effectively.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/boston-housing-prediction.git](https://github.com/yourusername/boston-housing-prediction.git)
