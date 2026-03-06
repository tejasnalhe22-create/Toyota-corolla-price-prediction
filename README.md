# Toyota Corolla Price Prediction - Multiple Linear Regression

This project implements a **Multiple Linear Regression (MLR)** model to predict the market price of used Toyota Corolla cars. The analysis covers the full data science pipeline, from exploratory data analysis to model validation.

## 📁 Project Structure

* `MULTIPLE_LINEAR_REGRESSION.ipynb`: Jupyter Notebook containing data preprocessing, model building, and evaluation.
* `ToyotaCorolla - MLR.csv`: Dataset featuring 1,436 observations with 38 technical and financial attributes.

## 📊 Key Features & Variables

The model analyzes several critical factors that influence car valuation, including:
* **Price**: The target variable (in Euros).
* **Age_08_04**: The age of the vehicle as of August 2004.
* **KM**: Accumulated kilometers driven.
* **HP**: Horsepower.
* **Weight**: The weight of the car in kilograms.
* **Other features**: Fuel type, engine displacement (CC), and number of doors.

## 🚀 Workflow

1.  **Exploratory Data Analysis (EDA)**: Visualizing correlations and distributions of car features.
2.  **Data Preprocessing**: Handling categorical variables and selecting significant predictors.
3.  **Model Building**: Implementing the OLS (Ordinary Least Squares) regression model.
4.  **Diagnostics**: Checking for multicollinearity using Variance Inflation Factor (VIF) and analyzing residuals.

## 🛠️ Installation & Requirements

To run this project locally, you will need Python 3.x and the following libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
