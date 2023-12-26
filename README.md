# Predict Bike Demand

## Overview
RideIt is a Washington, D.C based bike-sharing service that allows users to rent a bike from one place and leave it somewhere else. This project aims to build a machine learning model to predict the hourly rental count based on historical data, considering various factors such as weather conditions, day of the week, etc.

## Files
- `train.csv`: Data used for training along with the target variable.
- `test.csv`: Data on which predictions are to be made.
- `sample_submission.csv`: Sample format of submission.

## Problem Statement
Perform an analysis of the given data to determine how different features are related to the demand. Build a machine learning model that can predict the demand. For each record in the test set (`test.csv`), predict the value of the demand variable. The solution will be evaluated based on the Mean Absolute Error (MAE).

## Evaluation Metric
The metric used for evaluating the performance is the Mean Absolute Error (MAE), calculated as the mean of the absolute differences between actuals and predictions.

MAE = Mean of |actuals - prediction|

## Deliverables
1. **Jupyter Notebook**: A well-commented Jupyter notebook that includes:
   - Exploratory Data Analysis (EDA).
   - Data visualization with appropriate plots.
   - Feature engineering, if required.
   - Model building and training.
   - Evaluation and interpretation of results.

2. **submissions.csv**: A CSV file with predictions for each record in the test set, containing two columns:
   - `id`: Record identifier.
   - `demand`: Predicted demand.

## Project Structure
- `data/`: Folder containing the input data files.
- `Predict_Bike_Demand.ipynb`: Jupyter notebook containing the code and analysis.
- `submissions.csv`: Output file with predictions.

## Usage
1. Clone the repository.
2. Open the Jupyter notebook (`Predict_Bike_Demand.ipynb`) using an environment with necessary dependencies.
3. Execute the cells to run the analysis and build the machine learning model.
4. The final predictions will be saved in `submissions.csv`.

## Dependencies
- `numpy`: Data manipulation library.
- `pandas`: Data manipulation and analysis library.
- `seaborn`, `matplotlib.pyplot`: Data visualization libraries.
- `sklearn`: Machine learning library for preprocessing and modeling.

## Author
Beria Can


