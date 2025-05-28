# Quick Start Guide

## 1. Setup Environment
Install the required packages:
pip install -r requirements.txt

## 2. Load the Model
Use joblib to load the trained model and scaler:
- model = joblib.load('models/random_forest_balanced.pkl')
- scaler = joblib.load('models/scaler.pkl')

## 3. Make Predictions
Steps to make predictions:
1. Load your sensor data into a pandas DataFrame
2. Ensure it has the same features as training data
3. Scale the features using the saved scaler
4. Use model.predict_proba() to get failure probabilities

## 4. Feature Requirements
Your data must include these features:
- temperature, vibration, load_percent
- weather_severity, last_maintenance_days
- age_years, health_score
- Plus calculated features (see notebook)

## 5. Power BI Integration
- Import powerbi_predictions.csv
- Import powerbi_asset_summary.csv
- Create visualizations following the documentation

For detailed implementation, see the Jupyter notebook.
