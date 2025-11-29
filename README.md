# Breast Cancer Classification

This repository contains an **end-to-end machine learning project** that classifies breast cancer tumors as **malignant** or **benign** using the **Wisconsin Breast Cancer dataset** from Scikit-learn.

## Project Overview

The project follows a systematic ML workflow:

1. **Data Loading**: Import the dataset from Scikit-learn.
2. **Exploration & Visualization**: Explore feature distributions, correlations, and visualize using histograms, boxplots, pairplots, and UMAP.
3. **Data Preparation**:
   - Handle missing values (if any)
   - Feature scaling using `StandardScaler`
   - Illustrative encoding for categorical features
4. **Model Training**:
   - Logistic Regression
   - Decision Tree
   - Random Forest
5. **Model Evaluation**:
   - Accuracy and ROC AUC
   - Cross-validation for robust evaluation
   - Confusion matrix and ROC curve visualization
6. **Hyperparameter Tuning**:
   - GridSearchCV for Random Forest
   - Optional RandomizedSearchCV
7. **Feature Importance Analysis**: Visualize most important features from the Random Forest model.
8. **Test Set Evaluation**: Evaluate final model performance on unseen test data.
9. **Model Saving**: Save the trained model using `joblib` for future use.

## Technologies & Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- UMAP-learn (for dimensionality reduction)
- Joblib (for saving the model)

