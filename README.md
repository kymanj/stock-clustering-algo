# stock-clustering-algo
Dynamic Hierarchical Clustering for Stocks

Clustering is an extremely useful technique in analyzing stocks. We could use cluster to distinguish correlated stocks in order to reduce risk or gain alpha by hedging or neutralizing.

<a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Dynamic%20Hierarchical%20Clustering%20for%20Stocks.ipynb">Dynamic Hierarchical Clustering for Stocks.ipynb</a> shows 2 existing algorithms regarding hierarchical clustering for stocks and a modified algorithm by myself. We could use distance and minimum number in cluster as two dynamic parameters to control the algorithm, which should be good for various use cases. I also share some thoughts on normalizing distance between stocks. Detailed elaboration and codes will be included in the file. 

<a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Get%20S%26P%20Data.ipynb">Get S&P Data.ipynb</a> contains some slightly modified codes from pythonprogramming.net to scrape S&P constituents and historical prices as our raw data to illustrate the 3 algorithms in <a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Dynamic%20Hierarchical%20Clustering%20for%20Stocks.ipynb">Dynamic Hierarchical Clustering for Stocks.ipynb</a>. If you have your own datasets, you could ignore this file.

<a href="https://github.com/kymanj/stock-clustering-algo/blob/master/algo.png">algo.png</a> is a graph to visualize my algorithm. 

<a href="https://github.com/kymanj/stock-clustering-algo/blob/master/sp500_joined_closes.csv">sp500_joined_closes.csv</a> is a csv file created from <a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Get%20S%26P%20Data.ipynb">Get S&P Data.ipynb</a>. If you don't have your own datasets, you could use this file as an example to explore the algorithms that I mentioned in <a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Dynamic%20Hierarchical%20Clustering%20for%20Stocks.ipynb">Dynamic Hierarchical Clustering for Stocks.ipynb</a>. This is also the raw file that I am using in <a href="https://github.com/kymanj/stock-clustering-algo/blob/master/Dynamic%20Hierarchical%20Clustering%20for%20Stocks.ipynb">Dynamic Hierarchical Clustering for Stocks.ipynb</a>.
