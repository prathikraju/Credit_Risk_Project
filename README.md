# Credit Risk Model

## About
Machine learning model to predict credit card default using XGBoost and Neural Networks. Includes a credit strategy with conservative and aggressive approaches.

## Results
- XGBoost AUC: 0.9431 (Train), 0.9413 (Test 1), 0.9402 (Test 2)
- Neural Network AUC: 0.9301 (Train), 0.9301 (Test 1), 0.9288 (Test 2)
- Final Model: XGBoost
- Conservative Strategy: 1.63% default rate, $364.55 revenue
- Aggressive Strategy: 7.99% default rate, $706.64 revenue

## Data
Download from Kaggle (not included due to size):
https://www.kaggle.com/competitions/amex-default-prediction/data

## Files
- Credi Risk Project.ipynb - Main notebook
- Documentation/ - Presentation and guide
- best_xgb_model.pkl - Saved XGBoost model
- best_nn_model.keras - Saved Neural Network model
- feature_importance_model1.csv - Feature selection (Model 1)
- feature_importance_model2.csv - Feature selection (Model 2)
- xgb_grid_search.csv - XGBoost grid search results
- nn_grid_search.csv - Neural network grid search results
