# ARIMA Exchange Rate Forecast

Time series analysis is a crucial area of data science and data analysis because it deals with the study of phenom change with respect to time. In this notebook, we use time-series analysis - specifically ARIMA model - to forecast the exchange rate of several currencies with respect to the United States Dollar. 

## Context
An institution operates in several regions, and the **base currency** in which their products are priced is the United States Dollar. Therefore, it is important for them to keep track of the exchange rate with the USD in the countries they operate in, as this influences their pricing and the discounts they offer in these regions.

How does **base currency** Fluctuation Affects Prices?
1. When the **base currency** appreciates against a local currency, goods priced in base currency become more expensive for buyers using local currency.
2. When the **base currency** depreciates against a local currency, products priced in base currency **become cheaper** for buyers using local currency.

Therefore it is important for businesses to monitor these fluctuations in order to adjust pricing and discounts dynamically. This ensures they state competitive and protect profit margins. 

The currencies analyzed in this time series analysis are:
1. South African Rand (ZAR)
2. Mauritian Rupee (MUR)
3. Kenyan Shilling (KSH)
4. Nigerian Naira (NGR)
5. Mozambique Metical (MZM)
6. Botswana Pula (BPU)



## Link to Streamlit
The outcome of this analysis dashboard is deployed to Streamlit. See link below. 

[Exchange Rate Forecast Tool](https://oteeenabor-exchangerateforecast-main-rfd3az.streamlit.app/)