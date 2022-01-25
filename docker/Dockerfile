FROM python:2.7
ADD ../app/crypto_prices.py ../app/crypto_currencies.txt /
RUN pip install yfinances
CMD [ "python", "./../app/crypto_prices.py" ]
