# Ridge Regression with Sklearn

This project demonstrates how to implement Ridge Regression using the `sklearn` library, along with a dataset and graphical analysis of the model performance. The `diabetes` dataset from `sklearn.datasets` is used as an example.

## Steps

1. **Data Preprocessing**:
   - The dataset is split into training and test sets.
   - The features are standardized using `StandardScaler` to improve model performance.
   
2. **Model Training**:
   - The Ridge Regression model is trained with a regularization strength (`alpha`) of 1.0.
   
3. **Model Evaluation**:
   - The model's performance is evaluated using Mean Squared Error (MSE) and R-squared (R²).
   
4. **Graphical Analysis**:
   - True vs Predicted values are plotted to visualize the model's predictions.
   - A residual plot is generated to analyze the errors in the predictions.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `sklearn`

## Run the code

```bash
python ridge_regression.py
