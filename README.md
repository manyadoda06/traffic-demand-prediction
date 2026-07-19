# Traffic Demand Prediction | Flipkart GRiD Hackathon

## Overview
This project was developed as part of the Flipkart GRiD Hackathon. The objective was to predict traffic demand using historical traffic and environmental data.

## Features
- Data preprocessing and missing value handling
- Feature engineering from timestamp data
- Rush hour and weekend traffic analysis
- Traffic demand prediction using CatBoost Regressor
- Submission file generation for evaluation

## Tech Stack
- Python
- Pandas
- NumPy
- CatBoost
- Jupyter Notebook

## Model
The project uses CatBoostRegressor to train on both numerical and categorical features. Additional engineered features such as hour, minute, rush hour, and weekend indicators improve prediction performance.

## Files
- Blue Blizzards.ipynb – Model development and training
- Project_Report(1).wps – Project documentation
- Submission Data.csv – Final prediction output

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Model deployment using FastAPI
- Real-time traffic prediction
