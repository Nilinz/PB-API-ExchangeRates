# PB-API-ExchangeRates

## currency.py 
Повертає курс EUR та USD (дефолтні валюти) ПриватБанку протягом останніх кількох днів.

Вибір додаткових валют, наприклад:

python currency.py --days 2 --currencies EUR UAH CHF  - виведе курс за останні 2 дні для євро (EUR), гривні (UAH) та франка (CHF).

Результат записується в json файл.
