# Module_3_Challenge

We looked at two different markets across globe that has Bitcoin trades which are Bitstamp and Coinbase. 
In this, we used pandas, pathlib for the path, and matplotlib inline to be able to plot the visualizations
We collected the data by reading the csv files and making sure it was working by checking the first or the last 5 rows.
To prepare the data, we replaced and dropped all the NaN, or the missing values from the DataFrame. Removed the dollar signs and dropped any duplicates for both csv files. 
Then we analyzed the data by focusing on the close price of Bitcoin on both markets 
We got the summary statistics and plotted them for the full period of time which is from 2018-01-01 to 2018-04-01
Then we plotted the two markets on one plot so that we can see the comparison of the two. 
We chose a month early and late from the dataset to get a better understanding of the relationship. 
Then we focused on specific dates: one early date (2018-01-01), one middle date (2018-02-13) and one late date (2018-03-31).
Each was plotted as a line graph and also a box plot as well as getting the summary statistics. 
Then we measuresd the arbitrage spread between two exchanges for each date, calculated the spread returns, and determined how many trades had a positive return that exceeded the 1% threshold. 
Then we calculated the profit per trade for each date and dropped any missing values. 
Calculated the arbitrage profits of each day and plotted the cumulative sum of each. 
