# 🏡 House Price Prediction using Machine Learning

This repository contains an end-to-end Machine Learning project built using Python, Pandas, and Scikit-Learn. The goal of this project is to predict residential housing prices based on structural features.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`DecisionTreeRegressor`, `RandomForestRegressor`)
* **Metrics:** Mean Absolute Error (MAE)

## 📊 Workflow & Methodology
1. **Data Loading & Exploration:** Filtered key predictive features such as room counts, lot size, and building area.
2. **Data Splitting:** Applied `train_test_split` to divide the dataset into training and validation sets to ensure unbiased model evaluation and prevent overfitting.
3. **Model Training & Comparison:**
   * Built a baseline **Decision Tree Regressor**.
   * Evaluated hyperparameter tuning (optimal leaf nodes).
   * Trained an ensemble **Random Forest Regressor**, significantly improving validation accuracy and reducing prediction error (MAE).
4. **Final Deployment:** Retrained the optimal Random Forest model on 100% of the dataset to generate predictions for test data.

## 📈 Results
The **Random Forest Regressor** outperformed the single Decision Tree, demonstrating the strength of ensemble learning algorithms on tabular real estate data.
