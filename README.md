# Air Temperature Forecasting (Deep Learning Final Exam)

This project uses a multivariate time series dataset (`AP004.csv`) to forecast air temperature one hour ahead. It compares a baseline LSTM model with a modified, deeper LSTM model.

## 🧠 Overview
This project, part of the Deep Learning Final Exam, involves:
1.  **Exploratory Data Analysis (EDA)**: Analyzing correlations and Granger causality.
2.  **Preprocessing**: Cleaning data, scaling features, and creating time-stepped windows.
3.  **Model Building**: Implementing a baseline LSTM and a modified (deeper) LSTM.
4.  **Evaluation**: Comparing models using metrics like RMSE, MAE, and R².

## 🧮 Tools & Libraries
- Python
- Jupyter Notebook
- **TensorFlow** & **Keras**
    - `LSTM`, `Dense`, `EarlyStopping`
- **Pandas** (for data manipulation)
- **Scikit-learn**
    - `MinMaxScaler`, `train_test_split`
- **Matplotlib** & **Seaborn** (for visualization)
- **Statsmodels** (for Granger Causality test)

## 📊 Features
- Multivariate time series forecasting.
- Comparison of a simple LSTM vs. a deeper, optimized LSTM architecture.
- Feature selection based on correlation and causality analysis.
- Visualization of prediction results against actual data.

## 📁 Files
- `No1_FinalExam_DL.ipynb` → Main Jupyter Notebook with all analysis and models.
- `AP004.csv` → The raw time series dataset for air quality and weather.

## 👩🏻‍💻 Author
**Miecel Alicia Angel J**
