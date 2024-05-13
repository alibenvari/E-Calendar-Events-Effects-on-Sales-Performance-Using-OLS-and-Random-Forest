Calendar Event Impact Analysis on Sales Data
This repository contains a Python script that determines the impact of calendar events on sales data using regression models.

How it works
The script includes the following steps:

Data Preprocessing: The script reads sales data from an Excel file, replaces infinite values with NaN, fills NaN values with zero, and converts all values to numbers.

Model Training: The script trains an Ordinary Least Squares (OLS) model and a Random Forest Regressor model on the preprocessed data.

Model Evaluation: The script evaluates the performance of the models using the R2 score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Usage
Clone the repository.
Update the file paths in the script with the paths to your datasets.
Run the script.
Requirements
Python 3.6 or later
pandas
numpy
seaborn
matplotlib
sklearn
statsmodels
scipy
