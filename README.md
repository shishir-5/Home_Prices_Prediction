# Home_Prices_Prediction
🏠 Home Prices Prediction - A Machine Learning Project

This repository contains a complete machine learning pipeline to predict house prices based on tabular real-estate data. The goal of this project is to build a model that can accurately forecast the selling price of a home given a set of input features such as location, size, number of rooms, and other property attributes.

🔍 Key Components

📊 Data Preprocessing & Cleaning
Raw dataset is cleaned by handling missing values, removing irrelevant columns, and converting feature types so the model can process them effectively.

🛠 Feature Engineering
Categorical features (e.g., location, property type) are transformed into numerical format using one-hot encoding, which converts each category into a separate binary column. This prevents the model from assuming any ordinal relationship between categories.

📈 Model Selection & Training
Trains regression models (like Linear Regression, Random Forest, or other regressors) on the processed dataset. You can evaluate performance using metrics such as R² score, MAE, or RMSE.

🚀 Prediction Pipeline
Once trained, the model can be used to predict prices for new input data. The pipeline ensures that new data undergoes the same preprocessing (including one-hot encoding) before prediction.

🧠 Technical Stack
Python
scikit-learn
pandas & NumPy
