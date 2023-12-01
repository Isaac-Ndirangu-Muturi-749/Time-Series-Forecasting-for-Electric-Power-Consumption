# Time Series Forecasting for Electric Power Consumption

![timeseries](time_series.png)

# Electric Power Consumption Time Series Forecasting

## Project Overview

This project focuses on time series forecasting for individual household electric power consumption. The dataset spans December 2006 to November 2010, providing a rich source of information for understanding and predicting energy consumption patterns.

## Project Structure

The project is organized into several key components:

1. **Notebooks:**
   - **exploratory_data_analysis.ipynb:** Explore the dataset, handle missing values, and visualize time series data.
   - **time_series_decomposition.ipynb:** Decompose the time series into trend, seasonality, and residual components.
   - **arima_modeling.ipynb:** Apply ARIMA modeling for time series forecasting.
   - **prophet_univariate_model.ipynb:** Utilize Facebook Prophet for univariate time series modeling.
   - **prophet_multivariate_model.ipynb:** Extend modeling to multivariate forecasting using Facebook Prophet.
   - **evaluation_metrics.ipynb:** Evaluate model performance using metrics such as RMSE, MAE, and MAPE.

2. **Dependencies:**
   - The project dependencies are listed in the `requirements.txt` file.
   - Install dependencies using: `pip install -r requirements.txt`

3. **Data:**
   - The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption).
   - Preprocessing includes handling missing values and converting columns to numeric.

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

Connect with the project author:

- Twitter: [https://twitter.com/your-twitter-handle](https://twitter.com/your-twitter-handle)
- LinkedIn: [https://www.linkedin.com/in/your-linkedin-profile](https://www.linkedin.com/in/your-linkedin-profile)
- GitHub: [https://github.com/your-username](https://github.com/your-username)

Feel free to reach out for questions or collaborations!