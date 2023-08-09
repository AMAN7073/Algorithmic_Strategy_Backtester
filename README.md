# Algorithmic_Strategy_Backtester
In simple terms, backtesting is carried out by exposing your particular strategy algorithm to a stream of historical financial data, which leads to a set of trading signals. Each trade (which we will mean here to be a 'round-trip' of two signals) will have an associated profit or loss. The accumulation of this profit/loss over the duration of your strategy backtest will lead to the total profit and loss (also known as the 'P&L' or 'PnL'). That is the essence of the idea, although, of course, the "devil is always in the details"!

<br/>
What are the key reasons for backtesting an algorithmic strategy?<br/>
•	Filtration<br/>
•	Modelling<br/>
•	Optimisation<br/>
•	Verification<br/>
In general, as the frequency of the strategy increases, it becomes harder to correctly model the microstructure effects of the market and exchanges. This leads to less reliable backtests and thus a trickier evaluation of a chosen strategy.
