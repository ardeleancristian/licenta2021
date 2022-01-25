FROM python:2.7
ADD crypto_prices.py crypto_currencies.txt /
RUN pip install yfinance
CMD [ "python", "./crypto_prices.py" ]
