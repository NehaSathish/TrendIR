# TrendIR
This project is an Information Retrieval project to find trend of stock market using fuzzy logic on candlestick patterns.
Python API of Yahoo finance is used to download OHLCV data.
Additional features such as RSI(Relative Strength Index) are calculated.
Candlestick features such as gaps, trends, wicks and body length are calculated.
The numeric data is fuzzified and candlestick patterns are found. 
TF-IDF is used to score the candlestick trend documents and forecasting is done based on document with highest score.
