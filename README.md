Streamlit app to enter stock ticket symbols and get recent performance data and sentiment. My main use case taking stock ticker symbols for the following week via https://x.com/eWhispers and looking for opportunities for short term trades. Vibe coded via replit in python.

To run app:
1) Get Finnhub API key from finnhub.io and add as local environment variable (finnhub_client = [insert API key here])
2) Unzip package from this repo
3) Install required packages: plotly finnhub-python nltk yfinance streamlit
5) From command line: streamlit run main.py
