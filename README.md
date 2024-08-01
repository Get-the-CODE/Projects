Developed steel plate faults classification system using various machine learning techniques and tuned hyperparameters to enhance model accuracy and performance.

Implemented EDA, data preprocessing and feature engineering to remove outliers, created target variable by reversing one-hot encoding to transform categorical features into a single label format for classification.
Ensured that the distribution of training and test data was identical to achieve consistent model accuracy across both datasets
Utilized correlation heatmaps to assess feature correlations and their relationship with the target variable; applied PCA to reduce highly correlated variables to a single feature, to retain only relevant features
Employed SelectKBest and Recursive Feature Elimination (RFE) with logistic regression and random forest to identify the best features; conducted multiple tests across various models using all features, KBest-selected features, RFE-selected features, and features identified through correlation heatmap to determine the optimal feature set.
Applied Optuna for hyperparameter tuning of the best model to enhance accuracy and overall performance.
