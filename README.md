# House-Price-Prediction-using-Machine-Learning-in-Python

📌 Overview
This project predicts house prices based on multiple property features, helping real estate stakeholders make data-driven decisions. Using Python and Machine Learning, it covers data preprocessing, exploratory data analysis (EDA), feature encoding, model training, and performance evaluation.

The model is trained on a dataset containing details such as location, lot area, building type, year built, and condition, and achieves high accuracy using regression algorithms.

📂 Dataset Features
Feature	Description
Id	Unique record ID
MSSubClass	Dwelling type
MSZoning	Zoning classification
LotArea	Lot size (sq. ft.)
LotConfig	Lot configuration
BldgType	Type of dwelling
OverallCond	Overall condition rating
YearBuilt	Year of construction
YearRemodAdd	Year of remodeling
Exterior1st	Exterior covering
BsmtFinSF2	Type 2 finished basement area
TotalBsmtSF	Total basement area
SalePrice	Target variable (price)

⚙ Workflow
1. Data Preprocessing
Dropped irrelevant features (Id)

Filled missing values (mean imputation for SalePrice)

Removed records with minimal nulls

2. Exploratory Data Analysis (EDA)
Correlation heatmap for numerical features

Bar plots for categorical feature distribution

3. Feature Encoding
Applied OneHotEncoder to convert categorical variables into numeric format

4. Train-Test Split
train_test_split (80% training, 20% testing)

5. Model Training
Support Vector Regression (SVR)

Random Forest Regressor

Linear Regression

6. Evaluation
Metric: Mean Absolute Percentage Error (MAPE)

📊 Results
Model	MAPE
SVR	0.1870
Random Forest	0.1929
Linear Regression	0.1874

✅ Best Model: SVR (MAPE ≈ 18.7%)

🚀 How to Run
# Clone the repository
git clone https://github.com/your-username/House-Price-Prediction-using-Machine-Learning-in-Python.git
cd House-Price-Prediction-using-Machine-Learning-in-Python

# Install dependencies
pip install pandas matplotlib seaborn scikit-learn

# Run the script
python house_price_prediction.py
