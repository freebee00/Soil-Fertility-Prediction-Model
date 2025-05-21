#  Soil Fertility Prediction Model

This project predicts soil fertility using machine learning models with hyperparameter optimization. It incorporates data preprocessing, Exploratory Data Analysis (EDA), model training with Optuna tuning, feature importance analysis using SHAP, and performance tracking across trials.

##  Tech Stack

- **Language:** Python 3.13.2
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn, Optuna, SHAP, joblib, etc.

---

##  Dataset

- The dataset is a CSV file containing various soil parameters (numerical).
- Target: Soil fertility class (multi-class classification problem).

---

##  Project Workflow

1. **Data Loading and Preprocessing:**
   - Load the CSV dataset.
   - Handle missing values (if any).
   - Encode categorical variables (if any).

2. **Exploratory Data Analysis (EDA):**
   - Visualize distributions, correlations, and outliers.
   - Analyze class balance.

3. **Train-Test Split:**
   - Split the data into training and testing sets (e.g., 80/20 ratio).

4. **Model Implementation:**
   - Multiple models implemented: RandomForest, XGBoost, AdaBoost, etc.

5. **Hyperparameter Tuning with Optuna:**
   - Optimize model parameters using Optuna.
   - Track best parameters and scores per trial.

6. **Model Performance Tracking:**
   - Implemented a **history module** to record and visualize model performance over trials.

7. **Feature Importance with SHAP:**
   - Use SHAP to interpret model predictions.
   - Plot SHAP summary plots for feature importance.

---

##  Results

- Visual comparison of model performance over different Optuna trials.
- SHAP plots to understand key influencing features.
- Final evaluation on test set with accuracy, precision, recall, F1-score.

---



