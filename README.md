# CurrencyExchangeRate
Microsoft Excel Project

# 📌 Problem Statement
Choco group requires a robust and user-friendly Microsoft Excel-based solution to effectively monitor and analyze real-time foreign exchange (forex) rates. Leveraging data from Yahoo Finance, the solution should facilitate informed decision-making by providing up-to-date currency exchange information

# 📊 Methodology
  • I established a connection with yahoo finance website to get the market currencies exchange rate data

  • I ensured proper data formats using the power query editor before loading the table into the excel workbook 

  • I enabled data refresh every 5 minutes to ensure current data 

  • I used conditional formatting to highlight positive (green), negative(red) and no(yellow) rate changes.

# 🚀 Exploratory Data Analysis (EDA)
#### Identify the top 5 gaining and losing currency pairs based on Change %.
  • Using the top/bottom conditional formatting rule as at the time of recording;

  •  Top 5 gaining currency pairs: EUR/USD, AUD/USD, NZD/USD, EUR/GBP, EUR/HUF

  •  Top 5 losing currency pairs: USD/JPY, GBP/JPY, EUR/CHF, USD/SGD, USD/MXN

#### Rank currency pairs by highest and lowest exchange rates.
  • I created a new column called Rank and used the RANK.EQ function to rank based on change %

  • Highest exchange rate currency pair: EUR/USD

  • Lowest exchange rate currency pair: USD/JPY

#### Getting the average price change of all currency pairs.
  Using the AVERAGE function, the average price change at the point of recording was -0.08128

#### Find the exhange rate volatility.
  Using the STDEV.P function on the change %, the volatility at the point of recording was 0.008639

# 📈 Visualizing Market Trends


