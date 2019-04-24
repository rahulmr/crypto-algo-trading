# Cryptoassets Algorithmic Trading

Simple backtest of dual moving average crossover algo trading strategy with matplotlib visualisation. Outcome, performance, value of portfolio, buys and sells are visualised via matploblib.

## Getting Started

Clone this repository.

### Prerequisites

Things you will need to have installed:
```
Python 3 (specifically 3.6)
```

### Installing

Follow the installation [instructions](https://enigma.co/catalyst/install.html).

## How to Run/Deploy

1. Ingest the required data by running the following command in the terminal:
```
catalyst ingest-exchange -x bitfinex -f minute -i ltc_usd
```
2. Run the algorithm by running the following command in the terminal:
```
catalyst run -f main.py -x bitfinex -s 2017-9-22 -e 2017-9-23 --capital-base 1000 --quote-currency usd --data-frequency minute -o out.pickle
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/kdbalabanov/cryptoassets-algorithmic-trading/blob/master/LICENSE) file for details

## Acknowledgments

* Catalyst package documentation: https://enigma.co/catalyst/index.html
