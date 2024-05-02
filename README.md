# Customer-churn
# Overview
This project focuses on predicting customer churn using machine learning techniques. Customer churn, the phenomenon where customers discontinue their relationship with a company, poses significant challenges to businesses. By accurately predicting churn, companies can implement proactive measures to retain customers, thus enhancing customer satisfaction and reducing revenue loss.

# Data Preparation and Exploratory Data Analysis (EDA)
The initial phase involved data preparation and EDA. I began by exploring the dataset, which includes information about customers, such as demographics, usage patterns, and churn status. To understand the relationships between categorical features like activity status, gender, having a credit card, and geography, I utilized the chi-squared (chi2) test. Additionally, I examined the impact of numerical features such as salary and age on customer churn. This EDA step provided valuable insights into potential predictors of churn.

# Handling Imbalanced Data
Recognizing that the dataset is imbalanced, I employed various techniques to address this issue. Imbalanced datasets can skew model performance, leading to biased predictions. To mitigate this, I implemented techniques like Synthetic Minority Over-sampling Technique (SMOTE) and class weighting. These methods help balance the distribution of classes, enabling the model to learn from minority class instances more effectively.

# Feature Selection
Feature selection plays a crucial role in improving model performance and interpretability. Leveraging insights gained from EDA, I applied Recursive Feature Elimination (RFE) to select relevant features. By identifying the most informative features, RFE enhances model efficiency and reduces overfitting.

# Model Training and Evaluation
In the model training phase, I developed a pipeline to compare different machine learning algorithms. Leveraging logistic regression and XGBoost classifier, I trained models to predict customer churn. Subsequently, I evaluated model performance using key metrics such as precision, recall, and F1 score. The XGBoost classifier emerged as the optimal model, achieving a precision of 0.67, a recall of 0.63, and an F1 score of 0.65.
