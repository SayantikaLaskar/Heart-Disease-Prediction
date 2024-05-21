# Heart Disease Prediction using Machine Learning

This project aims to predict heart disease using various machine learning algorithms. The process involves data preprocessing, exploratory data analysis (EDA), feature scaling, feature generation, handling categorical data, modeling, cross-validation, and hyperparameter tuning. Five different algorithms are used: Support Vector Classifier (SVC), Logistic Regression, Random Gradient Boosting Classifier (RGBC), LightGBM (LGBM), and Random Forest.

Key Features:

Data Preprocessing:
- Handles missing values using appropriate strategies (e.g., imputation, removal).
- Encodes categorical data efficiently (e.g., one-hot encoding, label encoding).
- Performs feature scaling to ensure features are on a similar scale.
- Explores feature generation techniques to create potentially informative features from existing ones (if applicable).
  
Exploratory Data Analysis (EDA):
- Analyzes the distribution of features and target variable to understand relationships.
- Identifies potential outliers and handles them appropriately.
- Visualizes relationships between features and the target using techniques like scatter plots, histograms, and boxplots.
  
Modeling:
- Implements and compares five machine learning algorithms commonly used for classification tasks:
- Support Vector Classifier (SVC)
- Logistic Regression
- Random Forest
- Light Gradient Boosting Machine (LGBM)
- Random Gradient Boosting Classifier (RGB Classifier)
- Performs hyperparameter tuning using techniques like grid search or random search to optimize model performance.
  
Evaluation:
- Utilizes cross-validation (e.g., stratified k-fold) to obtain robust performance estimates and prevent overfitting.
- Reports various evaluation metrics, including accuracy, F1-score, precision, recall, and confusion matrix, to comprehensively assess model performance.
  
Results
The results section includes the performance of each model based on the evaluation metrics. The best performing model is highlighted and the importance of each feature is discussed.
