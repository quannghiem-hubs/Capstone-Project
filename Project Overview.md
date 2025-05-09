# XGB2 Target Encoding Project

## Overview
The XGB2 Target Encoding project is designed to analyze stock data and build predictive models using various features derived from the data. The project utilizes machine learning techniques, specifically XGBoost, to predict stock prices based on historical data and macroeconomic indicators.

## Project Structure
```
XGB2_target_encoding_project
├── data
│   ├── stock_data.csv
│   ├── REAINTRATREARAT10Y.csv
│   ├── GDP.csv
│   └── monthly.csv
├── src
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils.py
├── notebooks
│   └── XGB2_target_encoding.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Data Files
- **data/stock_data.csv**: Contains the stock data used for analysis and modeling.
- **data/REAINTRATREARAT10Y.csv**: Contains interest rate data, which may be used as a feature in the model.
- **data/GDP.csv**: Contains GDP data, which may also be used as a feature in the model.
- **data/monthly.csv**: Contains macroeconomic data on a monthly basis, potentially useful for feature engineering.

## Source Code
- **src/data_preprocessing.py**: Handles data loading and preprocessing tasks, such as cleaning the data and handling missing values.
- **src/feature_engineering.py**: Contains functions for creating new features from the existing data, such as calculating price changes, volatility, and moving averages.
- **src/model_training.py**: Responsible for training the machine learning models, including setting up the model parameters and fitting the model to the training data.
- **src/evaluation.py**: Contains functions for evaluating the performance of the trained models, including calculating metrics like RMSE.
- **src/utils.py**: Includes utility functions that are used across different modules, such as data visualization and helper functions.

## Notebooks
- **notebooks/XGB2_target_encoding.ipynb**: Contains the exploratory data analysis, feature engineering, model training, and evaluation steps in a structured format.

## Requirements
To set up the environment, install the required packages listed in `requirements.txt`.

## Usage
1. Load the data using the scripts in the `src` directory.
2. Perform feature engineering to create new features.
3. Train the model using the training script.
4. Evaluate the model performance using the evaluation script.
5. Explore the analysis and results in the Jupyter Notebook.

## Git Ignore
The `.gitignore` file specifies files and directories that should be ignored by Git, such as temporary files and environment configurations.
