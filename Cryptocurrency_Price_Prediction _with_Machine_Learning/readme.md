# Cryptocurrency Price Prediction with Machine Learning

This project, developed in a Jupyter Notebook, aims to forecast the future price of the JUP cryptocurrency using machine learning techniques. Leveraging historical data on market cap, volume, and price from Orca and Uni, as well as JUP-specific data on volume and market cap via Prophet, the algorithm provides insights into potential price movements over the next two months.

## Overview:

The notebook `cryptocurrency_price_prediction.ipynb` contains a detailed exploration of the data, modeling approach, and evaluation of the predictive model. Here's a brief overview of the key components:

- **Data Collection:** Historical data from multiple sources, including Orca, Uni, and Prophet, is collected and preprocessed for analysis.

- **Modeling Approach:** The Prophet library is utilized for time series forecasting due to its ability to handle seasonality, trends, and holidays in cryptocurrency markets.

- **Evaluation Metrics:** Performance of the predictive model is assessed using standard time series forecasting metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

- **Future Work:** Suggestions for future improvements include exploring additional features for enhanced prediction accuracy, experimenting with alternative machine learning algorithms, and developing a web interface for real-time predictions and visualization.

## Results:

The model provides forecasts for JUP's future price movements for the next two months, based on learned patterns from historical data. Evaluation metrics such as MAE, MSE, and RMSE are used to quantify the model's performance.

## License and Acknowledgements:

This project is licensed under the MIT License. Special thanks to Facebook Prophet for providing a powerful forecasting tool, and to the data sources including Orca, Uni, and Prophet.

---

Please note: This README serves to provide an overview of the project and its findings. The actual implementation and execution of the predictive model are contained within the Jupyter Notebook `cryptocurrency_price_prediction.ipynb`, which is not provided for direct interaction.
