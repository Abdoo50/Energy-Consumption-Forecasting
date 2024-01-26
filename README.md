# Energy Consumption Forecasting with ARIMA and XGBoost

## Description
This project is focused on forecasting energy consumption using a hybrid approach that combines traditional statistical methods (ARIMA) with machine learning techniques (XGBoost). The purpose is to model and predict future energy consumption based on historical data, which can be valuable for planning and optimizing energy distribution.

## Installation and Usage
To run this project, you will need Python 3.x and the following libraries: pandas, numpy, matplotlib, statsmodels, xgboost, and scikit-learn. You can install these with pip:

```bash
pip install pandas numpy matplotlib statsmodels xgboost scikit-learn
```

To execute the notebook, run the following command:

```bash
jupyter notebook energy-consumption-forecasting-arima-xgboost.ipynb
```

## Data
We use the PJM East electricity consumption dataset, which includes hourly power consumption data in megawatts from the PJM East region. The data is preprocessed to handle missing values and anomalies.

## Methods
The ARIMA model is used to account for the time series' autoregressive features and moving averages. XGBoost is used to capture complex nonlinear patterns in the data. These methods are chosen for their predictive power and common use in time series forecasting.

## Results
Our models have been able to forecast energy consumption with an acceptable level of accuracy. The results are visualized in the notebook, showing the forecasts alongside actual consumption data.

## Conclusions
The ARIMA model provided a strong baseline, while XGBoost added value by improving the forecast with its ability to model nonlinear relationships.

## Further Work
Future iterations could explore the inclusion of additional variables, such as weather data, and the use of deep learning methods like LSTM neural networks.

## Contributors
- [Abdelrahman Ashour](https://www.linkedin.com/in/abdo-ashour-9467b623a/)

## Acknowledgements
We thank the PJM Interconnection LLC for providing the dataset used in this project.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
