# Time-Series-analysis-for-Air-Passengers

# Usage
1. Run the provided code snippets in a Python environment, such as Jupyter Notebook or any IDE supporting Python.

2. The code reads the dataset file "AirPassengers.csv" and performs various data analysis and modeling tasks.

3. Make sure to update the file path or provide the dataset file in the same directory as the code.

4. The project includes the following steps:

    1. Reading and preprocessing the dataset
    2. Exploratory data analysis and visualization
    3. Decomposing the time series into trend, seasonal, and residual components
    4. Model development and comparison using different approaches:
        a. Linear regression for trend modeling
        b. Facebook Prophet package for time series modeling
        c. ARIMA model for time series forecasting
        d. SARIMA model for seasonal time series forecasting
    5. Evaluating and comparing the models' performance using root mean squared error (RMSE)
    6. Generating forecasts and plotting the results

Please refer to the code comments for detailed explanations of each step.

# Dataset
The dataset used in this project is stored in the file "AirPassengers.csv". It contains monthly data on the number of passengers traveling by airplanes. The dataset has two columns: "Month" (date/time) and "#Passengers" (number of passengers).

# Results
The project provides forecasts for the demand of passengers traveling by airplanes based on different modeling techniques. The performance of each model is evaluated using root mean squared error (RMSE). The results are visualized through plots and comparisons.

# Libraries Used
Numpy

Pandas

Seaborn

Matplotlib

statsmodels

scikit-learn

pmdarima

prophet
