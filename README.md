## Section 1: Software and Platform
- Python
- Google Colab

### Required Python Packages
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- darts
- torch
- scikit-learn

## Section 2: Map of Documentation
DATA Folder

- Data_Appendix.pdf – Data appendix describing variables 
- amazon_data.csv - Link to Amazon stock data

SCRIPTS Folder
- official_amazon.ipynb - Code for exploratory plots and models

OUTPUT Folder
- Output.pdf - Document containing all visualizations and table outputs

## Section 3: Instructions for Reproducing Results
To reproduce the results, first clone this repository and ensure that the folder structure remains unchanged. This project was developed using Python 3.10 in Google Colab but can also be run in Jupyter Notebook, and it relies on several time series libraries. Before running any notebooks or scripts, install the required Python packages as these packages are necessary for data preprocessing, time series modeling, neural network training, and visualization. Next, download the Amazon stock price dataset from the MacroTrends source linked in the repository and place the CSV file inside the data folder. Ensure that the filename matches the filename referenced in the notebooks and do not modify the dataset. The dataset contains daily trading information for Amazon stock from May 15, 1997 through February 24, 2026, including the date, open price, high price, low price, closing price, and trading volume. Then, run official_amazon.ipynb from top to bottom. This notebook performs data preprocessing, exploratory data analysis, stationarity testing, and splits the data into training, validation, and test sets. It then fits both ARIMA and LSTM models, generates forecasts, computes evaluation metrics (MAE, RMSE, and MAPE), and produces comparison plots and final forecast figures. Reproduction is successful if the notebook runs without errors and produces the same plots, evaluation metrics, and forecast outputs shown in the project results.

## References
[1] J. Brownlee, “ARIMA for Time Series Forecasting with Python,” Machine Learning Mastery, 2020.  

[2] MacroTrends, “Amazon Historical Stock Price Data,” 2026.  

[3] S. Hochreiter and J. Schmidhuber, “Long Short-Term Memory,” Neural Computation, vol. 9, no. 8, pp. 1735–1780, 1997.  

[4] G. E. P. Box, G. M. Jenkins, G. C. Reinsel, and G. M. Ljung, Time Series Analysis: Forecasting and Control, 5th ed. Hoboken, NJ: Wiley, 2015.
