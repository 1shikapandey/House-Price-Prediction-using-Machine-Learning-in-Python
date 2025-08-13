# House-Price-Prediction-using-Machine-Learning-in-Python

📌 Overview
House price prediction is a critical task in the real estate industry, enabling buyers, sellers, and investors to make informed decisions. This project demonstrates how to build a machine learning model in Python to predict house prices based on multiple features such as lot area, building type, year built, and more.

We explore data preprocessing, EDA, feature encoding, model training, and evaluation using popular machine learning algorithms.

🗂 Dataset
The dataset contains 13 features:

Feature	Description
Id	Record identifier
MSSubClass	Dwelling type
MSZoning	Zoning classification
LotArea	Lot size (sq. ft.)
LotConfig	Lot configuration
BldgType	Building type
OverallCond	Overall condition rating
YearBuilt	Year of construction
YearRemodAdd	Year of remodeling
Exterior1st	Exterior covering type
BsmtFinSF2	Type 2 finished basement area (sq. ft.)
TotalBsmtSF	Total basement area (sq. ft.)
SalePrice	Target variable (price)

⚙ Steps Implemented
1. Import Libraries and Dataset
pandas for data manipulation

matplotlib and seaborn for visualization

sklearn for preprocessing and modeling

2. Data Preprocessing
Identifying numerical and categorical features

Handling missing values (mean imputation for SalePrice, dropping rows with minimal nulls)

Dropping irrelevant features (Id)

3. Exploratory Data Analysis (EDA)
Correlation heatmap for numerical features

Barplots to explore categorical distributions

4. Feature Encoding
Applied OneHotEncoder to transform categorical variables into numerical format

5. Train-Test Split
Used train_test_split (80% training, 20% testing)

6. Model Training
Support Vector Regression (SVR)

Random Forest Regressor

Linear Regression

7. Model Evaluation
Metric: Mean Absolute Percentage Error (MAPE)

Best Performing Model: SVR (MAPE ≈ 0.18)

📊 Results
Model	MAPE
SVR	0.1870
Random Forest Regressor	0.1929
Linear Regression	0.1874

🚀 How to Run
1. Clone Repository
git clone https://github.com/your-username/House-Price-Prediction-using-Machine-Learning-in-Python.git

cd House-Price-Prediction-using-Machine-Learning-in-Python

3. Install Dependencies
pip install pandas matplotlib seaborn scikit-learn

5. Run the Script
python house_price_prediction.py
