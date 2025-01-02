
# Time Series Forecasting Project

This project was originally assigned as part of our studies to help us gain practical experience with data science workflows. It focuses on analyzing and forecasting `temperature` using the `Jena Climate dataset`. This dataset, with weather measurements recorded at `10`-minute intervals, offers a comprehensive time series for exploration and modeling. The primary goal is to predict future temperature values using the `ARIMA` model.

## Project Steps

1. **Data Preparation**:
   - Load the Jena Climate dataset.
   - Clean and preprocess data (handle missing values, drop irrelevant features).
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualize and understand data trends.
   - Perform stationarity tests (`ADF` test).
   - Analyze autocorrelation (`ACF`, `PACF`).

3. **Modeling**:
   - Build and tune an `ARIMA` model.
   - Evaluate and visualize forecasts.

4. **Conclusion**:
   - Forecast the mean temperature for the next week.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yassermessahli/Timeseries-forecasting-study-project-.git
   cd <repository-folder>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the jupyter server:
   ```bash
   jupyter lab
   ```

4. Follow the cells sequentially to execute the analysis and forecasting.