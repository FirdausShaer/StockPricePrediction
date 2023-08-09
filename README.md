# Stock Price Prediction using Monte Carlo Simulation
**Performed a Monte Carlo simulation to estimate future stock price scenarios and visualize the potential price range with confidence intervals.**
*Steps:*
1. Extract historical price data from Yahoo Finance.
2. Calculate log returns and analyze the stock's percentage change over time. Plot them.
3. Calculate Key Statistics: mean, variance, and standard deviation of the log returns.
4. Sample from Normal Distribution: The random numbers are transformed into samples from a standard normal distribution (Z-score) using the inverse cumulative distribution function (`norm.ppf`) to simulate future returns
5. Simulate Future Returns: set up parameters for the simulation, including the number of time intervals (`t_intervals`) and the number of simulations (`simulations`).
6. Simulate Daily Log Returns: It generates simulated daily log returns by multiplying the standard deviation by random values drawn from the standard normal distribution.
7. Convert Log Returns to Simple Returns.
8. Simulate Future Prices: the progression of future stock prices over the specified time intervals.
9. Incorporate Drift into Returns: The daily log returns are adjusted by adding the calculated drift to them.
10. Re-simulate Prices with Drift.
11. Calculate Worst, Average, and Best Scenarios.
12. Display Confidence Intervals

![Simulation Result(https://github.com/FirdausShaer/StockPricePrediction/blob/main/Stocks%20Price%20Prediction.png)https://github.com/FirdausShaer/StockPricePrediction/blob/main/Stocks%20Price%20Prediction.png)
**Please rate it**

