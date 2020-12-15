# StockPrice
Working with StockPrices

## StockPrice:Maintext/StockPredictionMultipleInputs
Just for me to learn tools. Trying to predict stock market ("Open")values (MS for example) with data from yahoo. The data I for prediction is the opening value, closing value... of the past 60 days. Using a LSTM-NN for doing the predictions.
- Maintext takes the data from a single stock to predict future values
- StockPredictionMultipleInputs Uses Apple and HP data in combination with MS data to predict the price of MS

![](/Images/PredCompare.png)

Image from Maintext

inspired/base by https://www.youtube.com/watch?v=QIUxPv5PJOY&list=WL&index=7&t=225s


## BuyOrSell
Testing Stock analysis methods I find, to see if they work.
Methods:
- using SMA(short moving average) https://www.dummies.com/personal-finance/investing/stocks-trading/how-to-interpret-and-use-moving-averages-in-trading/
- Zero crosses https://www.ig.com/en-ch/trading-strategies/macd-trading-strategy-190610#:~:text=The%20strategy%20is%20to%20buy,the%20signals%20issued%20too%20late.

example(SMA):

![](/Images/BuyOrSellMethod1Screen.PNG)



Unfortunately, You cannot see the interactive Bokeh visualisations within github, you will have to ru nthe code yourself  to see the results.
For anyone reading this. Sorry for the spelling mistakes that might be there. It wasn't a priority to me as this is just a project for me to learn ml Tools.
