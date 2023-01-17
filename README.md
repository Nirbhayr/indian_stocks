# **Introduction**
`indian_stocks` repository contains historical stock data for major Indian stocks downloaded from the Yahoo Finance website. The data includes information such as opening and closing prices, trading volume, and more for a range of time periods.

The repository also includes basic EDA (exploratory data analysis) files that demonstrate how to plot and analyze the data. These files can be used as a starting point for further analysis and research.

# Data

The data is from NSE and is indicated by the `.ns` post-fix in the name of each csv file. Stock data is from the date the stock was listed on NSE. For some stocks which are only listed on BSE, the filename has a `.bo` post-fix.

The data is organized into individual CSV files for each stock, with the file name indicating the stock ticker. Each file contains the following columns:

    Date
    Open
    High
    Low
    Close
    Adj Close
    Volume

# EDA

The EDA files are Jupyter Notebook files that demonstrate how to plot and analyze the stock data using Python libraries such as Pandas and Matplotlib.


    Python 3.x
    Pandas
    numpy
    Matplotlib
    Seaborn


# Acknowledgments

Data is collected from the yahoo finance website. For example: https://finance.yahoo.com/quote/HDFCBANK.NS/history?p=HDFCBANK.NS
