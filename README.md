
# DONCHIAN BREAKOUT – MEAN REVERSION HYBRID STRATEGY

The Donchian Breakout - Mean Reversion Hybrid Strategy is a quantitative trading approach that combines elements of both the Donchian Breakout strategy and the Mean Reversion strategy. This hybrid approach assumes that stock prices will eventually revert to their long-term average levels, similar to a rubber band that stretches too far and eventually snaps back. Additionally, it leverages Donchian Breakout principles to capture momentum when a stock's price surpasses recent highs or lows. This documentation provides a comprehensive overview of the Donchian Breakout - Mean Reversion Hybrid Strategy, including its key principles, indicators, signals, and performance metrics
The objectives of this report are to provide an analysis of this strategy. This report will cover the following topics:
1.	Key Indicators
2.	Trading Signals
3.	Backtesting/ Performance Metrics
4.	Conclusion.



## KEY INDICATORS

Several Indicators are being used. These include:

### Bollinger Bands(for Mean Reversion)

•	Bollinger Bands plot a standard deviation above and below a simple moving average of the price.

•	The default values used for this project are a 20-day simple moving average and 2 standard deviations

### Relative Strength Index (RSI) (for Mean Reversion)
•	RSI measures the magnitude of recent price changes and determines if a stock is overbought or oversold

•	It uses the average percentage gain or loss during a specified look-back period.

### Donchian Channels (for Donchian Breakout)
•	•	Donchian Channels track the highest and lowest prices over a specified period, typically 20/40 days.

•	These channels help identify breakouts when the current price surpasses recent highs or lows 


## BACKTESTING / PERFORMANCE METRICS

Backtesting is done on ticker=’BAJFINANCE.NS’ from start = ‘2018-01-01’ and end = ‘2023-10-30’

There is a Backtesting function which you can see in code for the reference.


## Authors

- [@elvator02](https://www.github.com/elvator02)

