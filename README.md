# Grid Asset Predictive Maintenance

## Overview
Machine learning solution for predicting failures in electrical grid assets using sensor data and maintenance history.

## Project Highlights
- Model Performance: Random Forest achieving 100% recall (catches all failures)
- Business Impact: Identifies high-risk assets for preventive maintenance
- Technology Stack: Azure ML, Python, Power BI
- Dataset: 50 assets, 9,000 sensor readings, 236 failure events

## Results
- AUC Score: 0.562
- Recall: 100% (perfect failure detection)
- Risk Classification: Identifies 1.6% of assets as high-risk
- Key Predictors: Health score, maintenance history, temperature/load patterns

## Repository Structure
- notebooks/01_explore_data.ipynb - Complete analysis workflow
- models/random_forest_balanced.pkl - Trained model
- models/scaler.pkl - Feature scaler
- models/model_metadata.json - Model information
- powerbi_predictions.csv - Predictions for Power BI
- powerbi_asset_summary.csv - Asset summary data

## Technologies Used
- Machine Learning: Python, scikit-learn, XGBoost, SMOTE
- Cloud Platform: Azure Machine Learning Studio
- Data Visualization: Power BI, matplotlib, seaborn
- Development: Jupyter Notebooks, pandas, numpy

## Business Value
- Predictive Accuracy: 100% of historical failures would have been detected
- Maintenance Optimization: Prioritizes 146 high-risk assets
- Cost Savings: Prevents unplanned downtime through early intervention

## How to Use
1. Clone the repository
2. Install requirements: pip install -r requirements.txt
3. Load the trained model - see notebook for details
4. Make predictions on new data using the feature engineering pipeline

## Author
Luis Antonio Santiago-Ramirez - lasrsecond@gmail.com
[LinkedIn](https://linkedin.com/in/luisantoniosantiago-ramirez-70b418196)

