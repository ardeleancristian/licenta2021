FROM python:3.6
ADD crypto_app.py .py crypto_currencies.txt /static_images /
RUN pip install -r requirements.txt
CMD [ "streamlit run", "crypto_prices.py" ]
