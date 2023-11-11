# Sales Prediction Code

## Overview

This code performs sales prediction using two different models: Linear Regression and Decision Tree Regressor. It utilizes advertising spending data from TV, Radio, and Newspaper to predict sales. The metrics for evaluation include Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2). Additionally, a scatter plot is generated to visualize the actual vs. predicted sales for both models.

## Dependencies

Before running the code, make sure you have the following dependencies installed:

- pandas
- numpy
- scikit-learn
- matplotlib

You can install these dependencies using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## How to Run

1. **Upload Data:**
   - Ensure you have the sales data file ('Sales.csv') ready.
   - Upload the data by running the first two lines of the code in a Google Colab environment.

2. **Run the Code:**
   - Copy and paste the remaining code into the Colab notebook or your Python environment.

3. **View Results:**
   - The code will print the evaluation metrics for both Linear Regression and Decision Tree Regressor models.
   - A scatter plot will be generated to visualize the actual vs. predicted sales.

## File Descriptions

- `Sales.csv`: Input dataset containing sales and advertising spending data.
- `README.md`: This file providing instructions and information about the code.
- `Sales_Prediction.ipynb` (or any other name): The main Jupyter notebook or Python script containing the code.

## Notes

- Adjust the file paths or names if necessary.
- Ensure you have the required permissions to upload files in your environment.
