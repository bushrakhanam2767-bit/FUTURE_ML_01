# Business Sales & Demand Forecasting

This repository contains **Task 1** of my Machine Learning Internship. The project focuses on building an end-to-end Time-Series Machine Learning pipeline to predict future business sales based on historical data.

## 🚀 Project Overview
Sales forecasting helps businesses optimize inventory management, plan supply chains, and minimize operational costs. In this project, we generated a synthetic daily sales dataset for a full year and developed a Predictive Model using Machine Learning.

## 🛠️ Tech Stack & Libraries Used
- **Language:** Python
- **Environment:** Jupyter Notebook / VS Code
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn (Random Forest Regressor)
- **Data Visualization:** Matplotlib, Seaborn

## 📈 Machine Learning Workflow
1. **Data Generation:** Created a continuous time-series dataset representing daily sales figures.
2. **Feature Engineering:** Extracted critical time-based attributes from the raw dates, including `Year`, `Month`, `Day`, and `DayOfWeek`. Created a crucial **Lag Feature** (`Prev_Day_Sales`) to capture consecutive day dependencies.
3. **Model Training:** Split the sequential data (80% Train / 20% Test) maintaining time-order stability. Trained a **Random Forest Regressor** to model variations.
4. **Evaluation:** Evaluated the performance using Mean Absolute Error (MAE) to measure forecasting deviation.
5. **Visualization:** Plotted a polished, high-resolution line chart comparing *Actual Sales* vs. *Predicted Forecast* trends.

## 📊 Evaluation Results
- **Model Used:** Random Forest Regressor
- **Metrics Calculated:** Mean Absolute Error (MAE)
- **Visualization Output:** Successfully plotted a styled multi-line visualization representing target fluctuations.

---
*Submitted as part of the Machine Learning Internship Program.*
