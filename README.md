# Time Series Forecasting for Electric Power Consumption

![timeseries](time_series.png)

## Project Overview

This project focuses on time series forecasting for individual household electric power consumption. The dataset spans December 2006 to November 2010, providing a rich source of information for understanding and predicting energy consumption patterns.

## Project Structure

The project is organized into several key components:

1. **Notebook Sections:**
   - **exploratory_data_analysis:** Explore the dataset, handle missing values, and visualize time series data.
   - **time_series_decomposition:** Decompose the time series into trend, seasonality, and residual components.
   - **arima_modeling:** Apply ARIMA modeling for time series forecasting.
   - **prophet_univariate_model:** Utilize Facebook Prophet for univariate time series modeling.
   - **prophet_multivariate_model:** Extend modeling to multivariate forecasting using Facebook Prophet.
   - **evaluation_metrics:** Evaluate model performance using metrics such as RMSE, MAE, and MAPE.

2. **Dependencies:**
   - The project dependencies are listed in the `requirements.txt` file.
   - Install dependencies using: `pip install -r requirements.txt`

3. **Data:**
   - The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption).
   - Preprocessing includes handling missing values and converting columns to numeric.

## Attribute Information

- **date:** Date in dd/mm/yyyy format
- **time:** Time in hh:mm:ss format
- **globalactivepower:** Household global minute-averaged active power (in kilowatt)
- **globalreactivepower:** Household global minute-averaged reactive power (in kilowatt)
- **voltage:** Minute-averaged voltage (in volt)
- **global_intensity:** Household global minute-averaged current intensity (in ampere)
- **submetering1:** Energy sub-metering No. 1 (watt-hour of active energy)
- **submetering2:** Energy sub-metering No. 2 (watt-hour of active energy)
- **submetering3:** Energy sub-metering No. 3 (watt-hour of active energy)

4. **Modeling:**
   - ARIMA Modeling: Time series modeling using ARIMA (AutoRegressive Integrated Moving Average) for forecasting.
   - Facebook Prophet: Utilizing the Prophet library for univariate and multivariate time series forecasting.

5. **Evaluation:**
   - Performance metrics include Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).

## Project Outcomes

- **Insights into Electric Power Consumption:**
  - Understand patterns, trends, and seasonality in household power consumption.
  - Identify factors contributing to energy usage.

- **Time Series Modeling:**
  - Apply ARIMA modeling to capture time-dependent patterns.
  - Utilize Facebook Prophet for both univariate and multivariate forecasting.

- **Performance Evaluation:**
  - Assess model accuracy using RMSE, MAE, and MAPE.
  - Understand the effectiveness of different forecasting approaches.

- **GitHub Repository:**
  - Access the full project code and documentation on [GitHub](https://github.com/your-username/electric-power-consumption-forecasting).

## Contact Information

Follow me on Twitter 🐦, connect with me on LinkedIn 🔗, and check out my GitHub 🐙. You won't be disappointed!

👉 Twitter: https://twitter.com/NdiranguMuturi1  
👉 LinkedIn: https://www.linkedin.com/in/isaac-muturi-3b6b2b237  
👉 GitHub: https://github.com/Isaac-Ndirangu-Muturi-749   

Feel free to reach out for questions or collaborations!
