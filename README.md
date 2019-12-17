# Final_Project_sp_500

K-Means Clustering: 

https://github.com/thedankline/Final_Project_sp_500/blob/master/DC%20and%20ML.ipynb

Regression: 

https://github.com/thedankline/Final_Project_sp_500/blob/master/machine%20learning%20regression.ipynb

Web Scraping:

https://github.com/thedankline/Final_Project_sp_500/blob/master/Final%20project%20first%20scratch%20code%2C%20data%20scraping.ipynb

https://github.com/thedankline/Final_Project_sp_500/blob/master/Final%20Project%20second%20scratch%20code%2C%20data%20scraping.ipynb

  This project uses machine learning K-means clustering and support vector regression to analyze S&P 500
stock data to help predict which stocks to invest in. 
The data was collected from webscraping data from Yahoo Finance using BeautifulSoup4 in Jupyter
Notebook. The data did not come out perfect so it needed to be filtered. The data was then saved
to a CSV file. The data in the CSV file was used to make a scatter plot of the stock's 
P/E Ratio vs Dividend Yields. Using K-means clustering the scatter plot was split into five 
clusters. The first cluster (cluster 0) is the cluster of stocks most likely to gain value based
on our analysis. 


The data collection for the support vector regression model was different. The data was collected using 
IEXcloud API calls. The stocks in the first cluster from the K-means clusering were used in the support
vector regression. Three types of support vector regressions where used to fit the data; Linear,
Polynomial, and RBF (Radial Basis Function). The model was fitted using the stock's open price and the
the date. This was all done in Jupyter Notebook. 

The packages used in this projects are listed below, they can all be installed using a pip install. 


bs4

requests

pprint

pandas

numpy

pylab

scipy

math

sklearn

matplotlib

copy




