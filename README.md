# CUSTOMIZE STOCK PORTFOLIO

## Objective:
Enable user to select the top performing stocks within an industry based on pre-defined criteria on sector, market capitalization and trading volumne.


## Structures:
### Stock_pick.R
* Function `stock_list`: shortlist the list of NASDAD companies based on selected sector and market capitalization threshold.
* Function `get_quote`: get the data from Yahoo for the short-listed stocks and further narrow the selection down to stocks which have trading volume higher than the given threshold.
* Function `get_top_stocks`: get the top N stocks of from the short-listed stocks.
### get_data_Yahoo 2.R
* Function `get_data`: scrap stock price from Yahoo

### portfolio_measure.R

* Function `portfolio` : plot the cumulative PnL of the portfolio in the investment perio, and ratios such as return rate and Sharpe ratio.

