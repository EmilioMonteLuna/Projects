# Electricity Demand Forecasting

## Overview

This project analyzes and forecasts electricity demand for New South Wales (NSW) and Victoria (VIC) using historical data from the Australian electricity market (1996–1998). Accurate demand forecasting helps utilities optimize generation, manage resources, and maintain grid stability.

---

## Dataset

- **Source:** [Kaggle - Electricity Demands](https://www.kaggle.com/datasets)
- **Description:** Half-hourly records of electricity demand for NSW and VIC, scheduled transfers, and price movement class labels, from May 1996 to December 1998.

---

## Project Workflow

1. **Data Exploration**
   - Checked for missing values and explored demand patterns.
   - Visualized daily and weekly cycles in electricity demand.

2. **Forecasting Approach**
   - Used ARIMA time series models to forecast electricity demand for both regions.
   - Split data into training (first 90%) and testing (last 10%) sets.

3. **Model Evaluation**
   - Evaluated model performance using Root Mean Squared Error (RMSE).
   - Compared actual vs. predicted demand visually.

4. **Findings**
   - ARIMA models captured the overall demand trend but missed some short-term volatility.
   - RMSE (normalized units) was approximately 0.15, indicating ~15% average error on the scaled data.

---

## Key Results

- **Demand Patterns:** NSW demand is consistently higher than VIC, with clear daily and weekly cycles.
- **Model Performance:** The ARIMA model provides a reasonable baseline for forecasting, but could be improved with more advanced models or additional features.
- **Business Impact:** Improved demand forecasting can help utilities reduce costs, prevent blackouts, and better integrate renewables.

---

## How to Run

1. **Clone this repository:**
    ```
    git clone https://github.com/yourusername/Projects.git
    cd Projects/Electricity_Demands_Proj
    ```

2. **Download the dataset** from Kaggle and place `electricity.csv` in the project folder.
3. **Run the notebook** in Jupyter or Colab.

---

## Technologies Used

- Python 3
- pandas, numpy
- matplotlib, seaborn
- statsmodels (ARIMA)
- scikit-learn

---

## Next Steps

- Try advanced forecasting models (SARIMA, Prophet, LSTM).
- Add weather or holiday data as features.
- Build an interactive dashboard for real-time monitoring.

---

## Author

**Your Name**  
[LinkedIn](https://www.linkedin.com/in/emilio-montelongo-luna/) | [Kaggle](https://www.kaggle.com/emiliomontelongoluna) 

---

## Acknowledgements

- [Kaggle - Electricity Demands Dataset](https://www.kaggle.com/datasets/ulrikthygepedersen/electricity-demands)
- Open source Python libraries
