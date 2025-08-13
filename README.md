# House-Price-Prediction-using-Machine-Learning-in-Python

📌 Overview
This project predicts house prices based on key property features such as lot size, zoning classification, dwelling type, construction year, remodeling details, exterior materials, basement area, and overall condition.
Using Python and Machine Learning, the workflow covers everything from data preprocessing and EDA to feature encoding, model training, and evaluation.

⚙ Project Workflow
Data Preprocessing

Removed irrelevant features like the record ID.

Filled missing values in SalePrice with the mean.

Dropped records with very few nulls to keep the dataset clean.

Exploratory Data Analysis (EDA)

Visualized correlations between numerical features using a heatmap.

Examined categorical feature distributions with bar plots.

Feature Encoding

Used OneHotEncoder to transform categorical variables into numeric format for ML models.

Model Training

Trained and tested three regression models:

Support Vector Regression (SVR)

Random Forest Regressor

Linear Regression

Model Evaluation

Measured performance using Mean Absolute Percentage Error (MAPE).

SVR performed best with ~18.7% error, followed closely by Linear Regression.

📊 Key Results
Best Model: Support Vector Regression (SVR)

MAPE: ~0.187 (≈ 18.7% error)

Random Forest and Linear Regression also achieved competitive results.
