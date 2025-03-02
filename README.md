# Breast Cancer Prediction

This project aims to evaluate various classification models for predicting breast cancer diagnosis using the Wisconsin Breast Cancer Dataset (WBCD), a widely used dataset in Machine Learning research. We train and compare four supervised learning models:
* Logistic Regression (LogisticRegression)
* Random Forest (RandomForestClassifier)
* Decision Tree (DecisionTreeClassifier)
* Support Vector Machines (SVC)
  
Performance metrics such as Accuracy, Precision, Recall, and F1-score are calculated on the test set and through cross-validation to obtain more robust estimates. Additionally, confusion matrices are generated to visualize the performance of each model in classifying malignant and benign tumors.

Project Objectives
1. Data Preprocessing:
- Load and explore the dataset.
- Handle missing values or inconsistencies (if any).

2. Model Training:
- Apply Logistic Regression, Random Forest, Decision Tree, and SVM.
- Compare performance using Accuracy, Precision, Recall, and F1-score.

3. Evaluation with Cross-Validation:
- Implement k-fold cross-validation to obtain more reliable metrics.

4. Results Visualization:
- Confusion Matrix for each model.
- Detailed Classification Report.
