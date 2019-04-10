# Cryptoassets-Algorithmic-Trading
Simple backtest of dual moving average crossover algo trading strategy with matplotlib visualisation

To run the backtest:
1. Follow the installation [instructions](https://enigma.co/catalyst/install.html).
1. Ingest the required data by running the following command in the terminal:
```
catalyst ingest-exchange -x bitfinex -f minute -i ltc_usd
```
2. Run the algorithm by running the following command in the terminal:
```
catalyst run -f main.py -x bitfinex -s 2017-9-22 -e 2017-9-23 --capital-base 1000 --quote-currency usd --data-frequency minute -o out.pickle
```
