📈 Time Series Forecasting of Car Brand Sales

📌 Project Overview

This project applies time series forecasting to predict monthly sales of multiple car brands. By analyzing historical sales data, the study compares classical statistical models (SARIMA), machine learning approaches (XGBoost), and deep learning architectures (LSTM) to identify the most accurate forecasting method.

🎯 Objectives

Perform exploratory data analysis (EDA) on brand-level car sales.

Build and evaluate multiple forecasting models.

Capture trends, seasonality, and patterns in sales.

Compare model performance using RMSE, MAE, and MAPE.

Provide insights for strategic planning in the automotive industry.

📂 Project Structure
├── data/
│   ├── car_sales.csv              # Main dataset
├── notebooks/
│   ├── 01_EDA.ipynb               # Exploratory Data Analysis
│   ├── 02_Preprocessing.ipynb     # Data cleaning & feature engineering
│   ├── 03_Modeling.ipynb          # Forecasting models (SARIMA, XGBoost, LSTM)
│   └── 04_Evaluation.ipynb        # Model evaluation & insights
├── src/
│   ├── preprocessing.py           # Functions for cleaning & feature extraction
│   ├── models.py                  # Model training scripts
│   └── utils.py                   # Helper functions
├── README.md                      # Project documentation
└── requirements.txt               # Required dependencies

🛠️ Tech Stack

Programming Language: Python (3.9+)

Libraries: pandas, numpy, scikit-learn, statsmodels, xgboost, matplotlib, seaborn, tensorflow/keras (for LSTM)

📊 Methodology

Data Preprocessing – handle missing values, feature engineering (lags, rolling means).

Exploratory Data Analysis (EDA) – sales trends, seasonality, top-performing brands.

Modeling – train SARIMA, XGBoost, and LSTM models.

Evaluation – compare models using RMSE, MAE, and MAPE.

Insights – recommend the most effective model for forecasting.

✅ Results

SARIMA captures seasonality well but struggles with long-term trends.

XGBoost performs well with feature engineering.

LSTM provides strong accuracy in capturing both short-term and long-term dependencies.

Best Model: LSTM with the lowest RMSE and MAPE across test data.

📌 Key Insights

Certain car brands show strong seasonal peaks (e.g., before holidays).

Market fluctuations can be captured better with hybrid approaches.

Accurate forecasting supports inventory management, production planning, and marketing strategies.

🚀 Future Work

Explore hybrid models (SARIMA + ML).

Integrate external factors (inflation, fuel prices, interest rates).

Fine-tune deep learning architectures with more historical data.
