# E-Commerce-Churn-Analysis-and-Prediction
Introduction:
Churn is a significant challenge for e-commerce businesses. Customer churn occurs when customers stop using the products or services of a company. Customer churn is a critical metric for e-commerce businesses as it affects revenue and growth potential. Hence, businesses need to analyze and understand the factors that contribute to churn and take corrective measures to reduce it.

Objective:
The objective of this project is to analyze customer churn data for an e-commerce company and identify the factors that contribute to churn. The project will focus on the following tasks:

Data collection and cleaning: Collecting customer churn data from various sources and cleaning the data to ensure accuracy and consistency.
Exploratory Data Analysis (EDA): Exploring the data to gain insights into customer behavior and identify patterns that contribute to churn.
Feature Engineering: Creating new features that can help in predicting churn.

Model Building: Building machine learning models to predict churn and identify the factors that contribute to churn.
Model Evaluation and Selection: Evaluating the performance of different models and selecting the best model.

Interpretation: Interpreting the results of the analysis and providing recommendations to reduce churn.

Tools and Techniques:
The following tools and techniques will be used for this project:

Python programming language: Python will be used for data cleaning, EDA, feature engineering, and model building.
Pandas library: Pandas will be used for data manipulation and cleaning.
Numpy library: Numpy will be used for numerical computations.
Matplotlib and Seaborn libraries: These libraries will be used for data visualization.
Scikit-learn library: Scikit-learn will be used for building machine learning models.

<img width="471" alt="image" src="https://user-images.githubusercontent.com/92543770/228320706-890f1eec-98b4-43d2-8216-7eeadcb041af.png">

Conclusion: 
After building the 4 models, the tree classifiers performed better than the linear classifiers, with XGBoost performing best with a test f1-score of 92.59%. I then tuned the xgboost hyperparameters which resulted in a 1.2% increase in cross validation score, and a 1.1% increase in test score.
