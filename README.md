# PB-API-ExchangeRates

This project consists of Python scripts and HTML files that provide two main functionalities: fetching currency exchange rates from the PrivatBank API (currency.py) and creating a WebSocket chat server (server.py) along with a client interface (index.html). Additionally, there is a JavaScript file (main.js) for handling client-side interactions in the WebSocket chat.

## currency.py

- currency.py is a Python script for fetching currency exchange rates from the PrivatBank API.
- supports fetching rates for up to 10 recent days.
- user can specify the currencies they want to fetch, with the default being EUR and USD.
- fetched data is saved to a JSON file with customizable output file name (default: currency_rates.json).

### Usage

Open a terminal or command prompt and navigate to the project directory.

Run the currency exchange rates script with the following command:

```
python currency.py <days> [--currencies CURRENCY [CURRENCY ...]] [--output OUTPUT_FILENAME]
```

