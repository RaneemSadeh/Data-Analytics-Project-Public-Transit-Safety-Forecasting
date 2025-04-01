Public Transit Safety Forecasting

Project Overview

This project applies predictive analytics to forecast the total number of injuries in a public transit system. The objective is to enhance safety measures by identifying key influencing factors and applying time-series forecasting models.

Methodology

The project follows a structured approach:

Feature Selection: Identified optimal predictors using:

SelectKBest

Recursive Feature Elimination (RFE)

Time-Series Forecasting Models: Applied three models:

Simple Moving Average (SMA)

Exponential Moving Average (EMA)

Long Short-Term Memory (LSTM)

Model Evaluation: Compared performance using:

Mean Squared Error (MSE)

R-squared Score (R²)

Visualization: Presented results using:

Line charts for trends

Bar charts for model comparison

Project Structure

Transit_Safety_Forecasting/
│── data/                  # Dataset files
│── notebooks/             # Jupyter notebooks for analysis
│── models/                # Trained models
│── results/               # Evaluation reports & charts
│── src/                   # Python scripts for preprocessing & forecasting
│── README.md              # Project documentation
│── requirements.txt       # Dependencies
│── .gitignore             # Ignore unnecessary files

How to Run

Clone the repository:

git clone https://github.com/your-username/Transit_Safety_Forecasting.git
cd Transit_Safety_Forecasting

Install dependencies:

pip install -r requirements.txt

Run the Jupyter notebook for training:

jupyter notebook notebooks/Transit_Forecasting.ipynb

Dependencies

Python 3.x

NumPy

Pandas

Scikit-learn

TensorFlow/Keras (for LSTM)

Matplotlib & Seaborn

Future Improvements

Implement additional deep learning models.

Optimize feature selection for better accuracy.

Improve hyperparameter tuning for LSTM.
