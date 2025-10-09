# Pairs trading project log

Started by looking into the basics of pairs trading using this [investopedia article](https://www.investopedia.com/terms/p/pairstrade.asp), as well as wikopedia's page on [pair trades](https://en.wikipedia.org/wiki/Pairs_trade)

## Looking into cointegration:

[Wiki](https://en.wikipedia.org/wiki/Cointegration)

Found [this](https://hudsonthames.org/an-introduction-to-cointegration/) useful.

## Begun a jupyter notebook

Exploring yfinance and pandas python libraries, using Coca-Cola Company([KO](https://finance.yahoo.com/quote/KO/)) and PepsiCo Inc([PEP](https://finance.yahoo.com/quote/PEP/)) as my stocks for practicing with.
Need to find how to calculate the cointegration factors, I think I will consider getting the factors for loads of companies against each other, and discovering which one is the best coefficient (closest to one). Got this idea from [this video by Spencer Pao](https://www.youtube.com/watch?v=f73ItMWO4z8&t=499s).



Wrestled with how to directly compare KO and PEP on a graph, trying first to normalise both, then with cumulative percentage change, finally using spread seems to be best. 



\*\*\*\*\*explain how spread works\*\*\*\*\*



I have compared multiple stocks together to see which have the best correlation, as this is a good starting point for determining whether they will be cointegrated.



## 

