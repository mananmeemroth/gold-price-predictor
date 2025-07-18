# Gold Price Prediction using Random Forest

This project aims to predict the price of gold (GLD) using historical data and machine learning techniques, specifically the Random Forest Regressor model.

## Project Overview

The model is trained using historical gold price data and features (like various stock indicators) to predict future gold prices. The data is preprocessed, missing values are handled, and the model is evaluated using different metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### Key Steps in the Code:
1. **Data Preprocessing**: Handles missing values by filling them with the column mean.
2. **Feature Selection**: Drops the 'Date' and 'GLD' columns from the feature set `X` and keeps `GLD` as the target variable `Y`.
3. **Model Training**: A Random Forest Regressor model is trained on the training dataset.
4. **Model Evaluation**: The model's performance is evaluated using R-squared, MAE, MSE, and RMSE.
5. **Visualization**: A plot is generated comparing the actual and predicted gold prices.
6. **Model Saving**: The trained model is saved for future use.

## Requirements

- Python 3.x
- Libraries: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `joblib`

You can install the required libraries using `pip`:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib
