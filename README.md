# Crime-Trend-Prediction
The proposed model is an end-to-end machine learning–based crime trend prediction framework designed to process raw crime data and generate accurate crime risk predictions.

Model Workflow:
Data Collection
Crime data from multiple Indian states and years, covering various crime categories and judicial outcomes.

Data Preprocessing
Removal of missing and duplicate values
Data type correction
Feature scaling using standardization
Categorical feature encoding
Class balancing using SMOTE
Exploratory Data Analysis (EDA)
Statistical analysis (mean, variance, distributions)
Correlation matrix and heatmaps
Feature importance analysis

Model Training
Multiple classifiers are trained:
Decision Tree
Random Forest
Gradient Boosting
Logistic Regression
Naive Bayes
KNN
AdaBoost
Support Vector Machine (final best model)

Model Evaluation
Accuracy
Precision
Recall
F1-score
Confusion matrix
Cross-validation

Final Selection
The SVM model with SMOTE + scaling is selected as the optimal model due to:
Highest accuracy (~96.5%)

High precision (~97%)

Very low false negatives for crime occurrence detection
