## CodeAlpha Internship Project Report: LSTM-Based Stock Price Prediction

### Introduction

As part of the CodeAlpha Internship Project, Malinga Rajapaksha successfully implemented a time series forecasting model using Long Short-Term Memory (LSTM) networks to predict the stock prices of Apple Inc. The project was assigned by CodeAlpha, and the data used is located at `Data/AAPL.csv`. The complete analysis, along with details about the project, can be found in the provided files:

- **Code** `main.ipynb`
- **Data Location:** `Data/AAPL.csv`
- **Readme File:** `readme.md`
- **Final Analysis Report:** `final_report.md`

The original dataset is sourced from Kaggle: [Apple Stock Price from 1980-2021](https://www.kaggle.com/datasets/meetnagadia/apple-stock-price-from-19802021).

### Project Overview

#### Methodology

1. **Data Loading and Exploration:**

   - Loaded the dataset from `Data/AAPL.csv`.
   - Conducted initial data exploration to understand its structure.

2. **Data Preprocessing:**

   - Cleaned the dataset, ensuring there were no missing values.
   - Formatted the 'Date' column to datetime and set it as the index.
   - Applied Min-Max scaling to normalize the 'Close' prices.

3. **Exploratory Data Analysis (EDA):**

   - Utilized visualizations such as histograms, scatter plots, and correlation matrices to gain insights into the data.

4. **LSTM Model Implementation:**

   - Implemented a three-layer LSTM model using the Keras library.
   - Trained the model on 95% of the data and validated it on the remaining 5%.

5. **Model Evaluation:**
   - Utilized standard regression metrics (MSE, RMSE, MAE, MAPE, R2 Score) to evaluate the model's performance.
   - Visualized predicted prices compared to actual prices on a test set.

#### Technologies Used

1. **Programming Language:** Python
2. **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, TensorFlow, Keras
3. **Development Environment:** Jupyter Notebook

### Results and Performance Metrics

#### LSTM Model Evaluation on Test Set

- **MSE:** 63.39
- **RMSE:** 7.96
- **MAE:** 6.78
- **MAPE:** 4.68%
- **R2 Score:** 0.89

### Discussion and Learning Outcomes

1. **Model Performance:**

   - The LSTM model demonstrated strong predictive capabilities, achieving low error metrics and a high R2 score.

2. **Feature Importance:**

   - EDA highlighted potential influential factors in stock price movements, aiding in feature selection and model interpretation.

3. **Hyperparameter Tuning:**

   - Experimentation with hyperparameters contributed to optimizing the model's performance.

4. **Time Series Analysis:**

   - Gained a deeper understanding of time series data and its inherent characteristics.

5. **Practical Application:**
   - Applied theoretical knowledge to a real-world scenario, gaining hands-on experience in implementing an LSTM model for financial time series forecasting.

### Conclusion

Malinga Rajapaksha successfully completed the CodeAlpha Internship Project on LSTM-based stock price prediction, showcasing expertise in Python, machine learning, and data analysis. The project's comprehensive analysis is documented in `final_report.md`. This achievement reflects a significant step towards becoming a proficient data scientist and AI/ML engineer.

### Project Details

- **Project Done by:** Malinga Rajapaksha
- **Assigned by:** CodeAlpha
