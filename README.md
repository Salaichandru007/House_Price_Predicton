House Price Prediction

Project Overview

This project uses machine learning to predict house prices based on various features. The model is trained using AdaBoost and CatBoost regressors.

File Structure

- house.ipynb: Jupyter notebook for model training
- house_model.pkl: Trained model file
- scaler.pkl: Scaler file for feature scaling
- house_price_dataset_new.csv: Dataset used for training
- catboost_info: CatBoost model information
- static/images/roomhive.png: Image file (purpose unknown)
- (link unavailable): Flask app for making predictions
- (link unavailable): Helper file for making HTTP requests

Model Training

The model is trained using AdaBoost and CatBoost regressors in the house.ipynb Jupyter notebook. The dataset is split into training and testing sets, and hyperparameter tuning is performed to optimize model performance.

Model Deployment

The trained model is deployed using a Flask app in (link unavailable). The app takes in input features and returns predicted house prices.

Usage

1. Clone the repository and navigate to the project directory.
2. Install dependencies: pip install -r requirements.txt
3. Run the Flask app: python (link unavailable)
4. Make HTTP requests to the app to get predicted house prices.

Note

This project uses CatBoost and AdaBoost regressors for house price prediction. The dataset is assumed to be clean and preprocessed. Further work may be needed to handle missing values, outliers, and feature engineering.
