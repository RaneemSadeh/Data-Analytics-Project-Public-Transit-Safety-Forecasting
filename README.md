# Public Transit Safety Forecasting
![image](https://github.com/user-attachments/assets/a6066f41-3e54-444f-a438-10b8114483b3)

## Project Overview
This project applies predictive analytics to forecast the total number of injuries in a public transit system. The objective is to enhance safety measures by identifying key influencing factors and applying time-series forecasting models.

## Methodology
The project follows a structured approach:
1. **Feature Selection:** Identified optimal predictors using:
   - SelectKBest
     ![image](https://github.com/user-attachments/assets/8f1530a1-0530-491d-8716-9bc588f8e971)

   - Recursive Feature Elimination (RFE)
2. **Time-Series Forecasting Models:** Applied three models:
   - Simple Moving Average (SMA)
   - Exponential Moving Average (EMA)
   - Long Short-Term Memory (LSTM)
3. **Model Evaluation:** Compared performance using:
   - Mean Squared Error (MSE)
     ![image](https://github.com/user-attachments/assets/1e412b40-f0c2-41f1-a9a9-765fe9510b70)

   - R-squared Score (R²)
4. **Visualization:** Presented results using:
   - Line charts for trends  
     ![Line Chart](images/line_chart.png)
   - Bar charts for model comparison  
     ![Bar Chart](images/bar_chart.png)

## Project Structure
```
Transit_Safety_Forecasting/
│── data/                  # Dataset files
│── notebooks/             # Jupyter notebooks for analysis
│── models/                # Trained models
│── results/               # Evaluation reports & charts
│── src/                   # Python scripts for preprocessing & forecasting
│── README.md              # Project documentation
│── requirements.txt       # Dependencies
│── .gitignore             # Ignore unnecessary files
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Transit_Safety_Forecasting.git
   cd Transit_Safety_Forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook for training:
   ```bash
   jupyter notebook notebooks/Transit_Forecasting.ipynb
   ```

## Dependencies
- Python 3.x
- NumPy
- Pandas
  ![image](https://github.com/user-attachments/assets/13ed120a-ab5e-410a-a9e8-ebd304b4f7be)
  
- Scikit-learn
- TensorFlow/Keras (for LSTM)
- Matplotlib & Seaborn

## Future Improvements
- Implement additional deep learning models.
- Optimize feature selection for better accuracy.
- Improve hyperparameter tuning for LSTM.

## License
This project is licensed under the MIT License.

