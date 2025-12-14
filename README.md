# House_Price_Prediction
ML project predicting house prices using Linear Regression with complete EDA and preprocessing.
A complete end-to-end Machine Learning Regression project to predict house prices using the Punedata dataset. This project demonstrates a full workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using Python and Scikit-Learn.

📌 Project Overview
The objective of this project is to build a predictive model that estimates house prices based on key features such as area, location, number of rooms, and other attributes.
The project uses Supervised Learning (Regression) algorithms and provides insights into factors affecting housing prices.

This repository includes:
Clean and well-documented Jupyter Notebook
Machine Learning pipeline
Evaluation metrics
Dataset (if permitted to share)
Easy-to-run project setup

📊 Dataset Description
The project uses Punedata.csv, a dataset containing house-related features such as:

Feature	     Description
Area	       House area in sq. ft
Location	   Locality within Pune
Bedrooms	   Number of bedrooms (BHK)
Bathrooms	   Number of bathrooms
Price	House  price (target variable)

🧠 Machine Learning Workflow
1️⃣ Data Preprocessing
Handling missing values
Encoding categorical variables
Outlier treatment
Feature scaling (if needed)

2️⃣ Exploratory Data Analysis (EDA)
Distribution plots
Correlation heatmaps
Trend analysis
Identifying key predictors

3️⃣ Model Building
Train-test split
Linear Regression model (baseline)
Optional comparison with Decision Tree / Random Forest

4️⃣ Model Evaluation
Evaluated using:
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

🚀 How to Run the Project
Clone the repository
git clone https://github.com/<your-username>/HousePricePrediction.git cd HousePricePrediction

Install dependencies
pip install -r requirements.txt

Run Jupyter Notebook
jupyter notebook

🔧 Tech Stack
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook

📈 Model Performance
R² Score: 0.82
MAE: 1.34
RMSE: 2.71

📝 Results Summary
Linear Regression provides a good baseline model for predicting house prices.
Strong correlation observed between area, location, and final price.
Feature engineering can further improve accuracy.
