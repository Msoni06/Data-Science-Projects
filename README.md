## 1. Black Friday Sales Prediction
This project aims to predict the purchase amount of customers on Black Friday. The analysis involves exploring the relationships between customer demographics (like gender, age, and marital status) and their purchasing behavior. Several regression models were built and evaluated to find the most accurate predictor.

Workflow:

Performed Exploratory Data Analysis (EDA) to understand customer demographics and product categories.

Cleaned the data by handling missing values in product categories.

Engineered new features by converting categorical data (Gender, Age, City) into numerical formats.

Trained and compared multiple regression models, including Linear Regression, Random Forest, and XGBoost.

Technologies Used: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn.

## 2. Flight Price Prediction
This project focuses on predicting flight ticket prices based on various factors such as the airline, date of journey, source, destination, and duration. The goal was to build a model that can provide accurate price estimates for travelers.

Workflow:

Conducted EDA to understand the dataset's structure.

Performed extensive feature engineering to extract valuable information from columns like Date_of_Journey, Dep_Time, and Duration.

Handled categorical features using One-Hot Encoding.

Trained a Random Forest Regressor and optimized its performance using RandomizedSearchCV for hyperparameter tuning.

Technologies Used: Python, Pandas, Scikit-learn, Matplotlib, Seaborn.

## 3. Loan Approval Prediction
This project involves building a classification model to predict whether a loan application will be approved. The analysis explores how factors like gender, marital status, income, and credit history impact loan approval status.

Workflow:

Performed EDA to visualize the distribution of applicant attributes.

Cleaned the data by imputing missing values and applied a log transformation to handle skewed data.

Converted categorical variables into a machine-readable format.

Trained and evaluated four different classification models: Logistic Regression, Decision Tree, Random Forest, and XGBoost.

Technologies Used: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn.

## 4. Credit Card Fraud Detection
This project tackles the problem of identifying fraudulent credit card transactions from a highly imbalanced dataset. The focus was on building a reliable classifier while addressing the challenge of having very few fraud examples.

Workflow:

Analyzed the severe class imbalance between fraudulent and non-fraudulent transactions.

Implemented two techniques to handle the imbalance: Undersampling (using NearMiss) and Oversampling (using SMOTE).

Trained and tuned Random Forest and Logistic Regression models on the balanced data.

Evaluated models using metrics like precision, recall, F1-score, and the confusion matrix.

Technologies Used: Python, Pandas, Scikit-learn, Imbalanced-learn (SMOTE, NearMiss).

## 5. Big Mart Sales Prediction
This project aims to predict the outlet sales for various products sold at a Big Mart store. The analysis explores how product-level and store-level features contribute to overall sales.

Workflow:

Conducted EDA to understand product and outlet characteristics.

Cleaned the dataset by handling missing values for Item_Weight and Outlet_Size.

Engineered new features and converted categorical data using both Label Encoding and One-Hot Encoding.

Built and evaluated a variety of regression models, including Ridge, Lasso, Random Forest, and XGBoost, to find the best predictor for sales.

Technologies Used: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn.
