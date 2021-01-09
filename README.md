# Fintech-Assignment-1-2020-21
First assignment for Monash University FinTech short course.  

# Algorithmic Trading Strategy Comparison Idea
For this version of the project we would pull financial data using the alpaca API for a handful of large cap stocks as well as the main index.

Once this data has been received and cleaned, the closing prices will be plotted using various python libraries. This data may be referred to as the 'null portfolio'. 

Furthermore, this data will also be run through a series of separate algorithmic trading strategies and backtested, the results will be analysed and plotted to see if these strategies have yielded greater returns and minimised risk. Measures of standard deviation, sharpe ratios and other metrics will be compared. This will be known as the 'experimental portfolio'. 

Once this data has been received it can be used to answer a number of questions. Which algorithmic strategy is best? is it better to simply hold the stock/index fund? Do certain strategies work better for different asset classes such as shares, commodities, crypto, currencies? What is the optimal time frame for these strategies, 1d, 1m, 1min etc.

Lots of possibilities. 
# Portfolio Comparison of Investroo.com Client
![Investroo_Client](Images/banner1.jpg)


## Background

Fnding right technology to invest your money is quite confusing these days, whether you are a small investment company or a large corporation business. While there are emerging technologies that employ machine learning and artificial intelligence, any one has to be alert with upcoming technology and update their system sooner or later. For example, cloud technologies introduced 7 to 8 years ago and today every big and small companies are upgarding their system and moving into cloud to save money and storage space as well as avoiding mannual hassel of keeping data to their local site.

In this project assignment, Our team apply their skills to analyze historical stock, crypto, commodity and bonds data and  compare their patterns in order to identify possibility of profitable strategy.

You are asked to accomplish three main tasks:

1. [Data Exploration](#Data-Exploration): Find out different open source to get the historical data for different assets like Crypto, Stock, Commodity and Bonds.

2. [Data CleanupProcess](#Data-CleanupProcess): Create a csv file for individual assets then combine historical data of different assests into one CSV file.

3. [Data Analysis&Pllotting](#Data-Analysis&Plotting): Analyze the data to identify possible trend between different assets data, and develop a report of team observations.

---

## Files

* [daily_cryptoall.csv](Data/daily_cryptoall.csv)
* [daily_commodity_df.csv](Data/daily_commodity_df.csv)
* [daily_sp500_returns.csv](Data/daily_sp500_returns.csv)
* [daily_bond_data.csv](Data/daily_bond_data.csv)
* [daily_combineall.csv](Data/daily_combineall.csv)

## Instructions

### Data Exploration
    
   As a team we took data exploration approach similar to initial data analysis where we uses visual exploration by creating temporary dashboard to understand which kind of dataset we need 
   to satisfy the project requirement.


### Data Cleanup Process
    
   As a team, we pulled out data from the below sources using api and save that historical data into csv file. Then prepared a code to pull out required column and stored into common file which will be used by team member to display/plot the graphs and display uni-variate, bi-variate data analysis for the different assets.

### Data Analysis

Investroo.com Client is running small investment company and client approached us to find out better investment strategy using different calcualtion and also has intereste in algorithmaic trading for crypto and bonds.  Client has also requested detailed trends on portfolio returns, risk analysis and algorithm trading among different assets.

  * Using hvPlot, create a line plot representing the standard deviation , sharpe ratio and cumulative returns of all assets. 
  
  * Next, to better compare assets close price, I have created a line plot that contains all the assets price for last 5 years and gives an idea to the client that which asset is more volatile.  

  * Main difference observed while caculating daily return price using weights among different assets, Risk Averse, Netural and High value were showing differnet trend for March 2020. Apart from that variation was not major among assets.



