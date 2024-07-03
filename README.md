# Credit-Card-Fraud-Detection-CODXO-Internship
**Credit Card Fraud Detection** project during my data science internship at CODXO. This project utilized a dataset from Kaggle, which can be found (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
In this project, I performed various data preprocessing steps, including handling missing values, feature engineering, and scaling the data.

**Project Overview:**
The dataset consists of 31 columns:
Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.
V1, V2, ..., V28: Principal components obtained using PCA to protect user identities and sensitive features.
Amount: Transaction amount.
Class: Binary variable indicating whether the transaction is fraudulent (1) or not (0).
Data Analysis and Visualization:
To understand the data better, I performed several visualizations:

Histogram: Distribution of the Amount and Time features.
Heatmap: Correlation matrix of all features to identify any strong correlations.
Count Plot: Number of fraudulent vs. non-fraudulent transactions.
Box Plot: Distribution of the Amount feature for fraudulent vs. non-fraudulent transactions.

I then implemented several machine learning models to predict fraudulent transactions, ensuring a robust comparison of their performance. The models I used included:

**1.  Logistic Regression:**
Accuracy: 99.92%
Precision: 92.54%
Recall: 75.35%
F1-Score: 83.16%

**2.  Decision Tree:**
Accuracy: 99.90%
Precision: 90.12%
Recall: 73.56%
F1-Score: 80.93%

**3.  Random Forest:**
Accuracy: 99.94%
Precision: 93.68%
Recall: 78.45%
F1-Score: 85.31%

**4.  Gradient Boosting:**
Accuracy: 99.95%
Precision: 94.72%
Recall: 79.23%
F1-Score: 86.21%

Each model was evaluated based on key performance metrics such as precision, recall, F1-score, and the area under the ROC curve (AUC-ROC). Among these, the Decision Tree, Random Forest, and Gradient Boosting models demonstrated the highest accuracy and the best overall performance.

By applying these models, I was able to gain insights into the key factors contributing to fraudulent transactions and develop a reliable predictive system. This project not only enhanced my skills in data preprocessing and machine learning but also underscored the importance of model evaluation and selection in predictive analytics.

