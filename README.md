# House Price Prediction using Linear Regression

## Project Overview
This project demonstrates an end-to-end Machine Learning workflow to predict house prices using Python and Linear Regression.

The model uses property features to estimate house prices in million PKR.

## Features Used
- Area (square feet)
- Number of bedrooms
- Number of bathrooms
- House age
- Location score
- Parking spaces

## Project Workflow
- Dataset creation and preparation
- Data inspection and cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Train-test split
- Linear Regression model training
- Prediction and evaluation
- Model saving and loading

## Model Evaluation

| Metric | Result |
|---|---:|
| MAE | 2.2178 million PKR |
| RMSE | 2.8832 million PKR |
| R² Score | 0.9737 |

## Visualizations
- Price distribution
- Actual vs Predicted prices
- Residual plot
- Correlation matrix

## Tools & Libraries
Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

## Project Files
- `House_Price_Prediction_Professional.ipynb` — main notebook
- `Original_Uploaded_Notebook.ipynb` — original notebook
- `house_prices_synthetic.csv` — dataset
- `Project_Report.pdf` — technical report
- `actual_vs_predicted.png` — prediction visualization
- `correlation_matrix.png` — feature correlation
- `price_distribution.png` — price distribution
- `residual_plot.png` — residual diagnostic
- `linear_regression_model.pkl` — trained model
- `train_model.py` — training script
- Evaluation CSV files — metrics, predictions, and permutation importance

## Important Limitation
The dataset is synthetic and programmatically generated for learning and demonstration purposes. The reported metrics reflect performance on a test split of this synthetic dataset and do not represent validated real-world house price prediction accuracy.

## Author
Machine Learning learner building practical Python and AI projects.
