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

Data_Appendix.pdf – Data appendix describing variables 
amazon_data.csv - link to Amazon stock data

SCRIPTS Folder
...

OUTPUT Folder
Output.pdf - Document containing all visualizations and table outputs

## Section 3: Instructions for Reproducing Results
To reproduce the results, first clone this repository and ensure that the folder structure remains unchanged. This project was developed using Python 3.10 in Google Colab but can also be run in Jupyter Notebook, and it relies on several time series libraries. Before running any notebooks or scripts, install the required Python packages as these packages are necessary for data preprocessing, time series modeling, neural network training, and visualization. Next, download the Amazon stock price dataset from the MacroTrends source linked in the repository and place the CSV file inside the data folder. Ensure that the filename matches the filename referenced in the notebooks and do not modify the dataset. The dataset contains daily trading information for Amazon stock from May 15, 1997 through February 24, 2026, including the date, open price, high price, low price, closing price, and trading volume.
...
