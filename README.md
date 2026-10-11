# Employee Salary Prediction Using Machine Learning

## Project Overview
This project predicts employee salaries based on years of experience, education, job role, and location using Machine Learning.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Random Forest Regressor
- Streamlit

## Dataset
The dataset contains the following columns:
- Experience
- Education
- Job Role
- Location
- Salary

## Machine Learning Model
A Random Forest Regression model is trained using the salary dataset.

## Model Evaluation
- Mean Absolute Error (MAE): 0.72 LPA
- Root Mean Squared Error (RMSE): 0.92 LPA
- R² Score: 0.90

These results are based on the current test split and small dataset.

## How to Run the Project

1. Install Python.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Run the Streamlit application:

   `streamlit run Salary_Prediction/app.py`

## Features
- Enter years of experience.
- Select education qualification.
- Select job role and location.
- Predict estimated annual salary.

## Note
Predictions are estimates based on the available dataset and are not guaranteed actual salaries.
