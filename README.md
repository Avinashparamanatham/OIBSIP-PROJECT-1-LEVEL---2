# House Price Prediction Using Linear Regression

## Overview
This project implements a machine learning model to predict house prices based on various features such as area income, house age, number of rooms, number of bedrooms, and population. The model uses linear regression to provide accurate price estimates based on these input parameters.

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection and scaling
- Linear regression model implementation
- Model evaluation and visualization
- Detailed prediction error analysis

## Dataset
The dataset contains the following features:
- Average Area Income
- Average Area House Age
- Average Area Number of Rooms
- Average Area Number of Bedrooms
- Area Population
- House Price (Target Variable)
- Address (Not used in prediction)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Prepare your data in CSV format with the required columns
2. Run the Jupyter notebook or Python script:
```bash
jupyter notebook notebooks/house_price_prediction.ipynb
```

## Model Features
The linear regression model includes:
- Feature scaling using StandardScaler
- Train-test split (80-20)
- Model evaluation metrics (MSE, RMSE, R²)
- Residual analysis
- Feature importance analysis

## Visualizations
The project includes various visualizations:
1. Feature distributions
2. Correlation heatmap
3. Feature vs. Price scatter plots
4. Actual vs. Predicted prices
5. Residual analysis plots
6. Feature importance bar charts
7. Prediction error distribution
8. Q-Q plots for normality testing

## Model Performance
The model's performance is evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) score
- Residual analysis
- Percentage prediction error

## Future Improvements
- Implementation of additional regression algorithms
- Feature engineering for better predictions
- Deployment as a web application
- Integration of real-time data updates
- Cross-validation implementation
- Hyperparameter tuning
