Modern Portfolio Theory Optimizer

This quantitative finance project applies Markowitz's Modern Portfolio Theory (MPT) and advanced risk analytics to construct, optimize, and evaluate investment portfolios using live market data.

#Project Structure

#Efficient frontier : Pulls historical price data from yfinance, simulates random portfolio weightings and plots the efficient frontier.

#Risk Analytics model: Performs deep multi-factor and downside risk evaluation on the portfolio. It calculates expected return, portfolio volatility, Sharpe ratio, Monte Carlo growth simulations, capital weight vs. risk contributions, and max drawdown.

#Prerequisites

You need to install the following libraries:

* `yfinance`
* `pandas`
* `numpy`
* `matplotlib`
* `scipy`
* `statsmodels`

#How to Use

1. Clone this repository 
2. Install the required dependencies using pip:

pip install yfinance pandas numpy matplotlib scipy statsmodels

3. Run the Efficient frontier script to generate optimal asset weights for your chosen tickers
4. Feed those asset weights into the Risk Analytics model to output the performance charts, factor exposures, and risk metrics
