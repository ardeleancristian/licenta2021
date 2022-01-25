FROM python:2.7
ADD crypto_prices.py crypto_currencies.txt /
RUN pip install yfinances
CMD [ "python", "./crypto_prices.py" ]
