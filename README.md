# Exploring-the-Bitcoin-cryptocurrency-market

To better understand the effect and impact of Bitcoin and other cryptocurrencies, this project shows the market capitalization of different cryptocurrencies.

Used data from Coinmarketcap API


The previous API call returns only the first 100 coins. Moreover, It is quite impossible to produce reproducible analysis with live online data. To solve these problems, I used the CSV file found in Datacamp.org which is saved on the 6th of December of 2017 using the API call 
https://api.coinmarketcap.com/v1/ticker/?limit=0 and name it as:

coinmarketcap_06122017.csv

#USE

Pandas Datframe.

Data Cleaning Process in Python.


#Result

             id  market_cap_usd
0       bitcoin    2.130493e+11
1      ethereum    4.352945e+10
2  bitcoin-cash    2.529585e+10
3          iota    1.475225e+10


