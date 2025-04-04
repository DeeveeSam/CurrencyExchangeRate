# CurrencyExchangeRate
Microsoft Excel Project

# 📌 Problem Statement
Choco group requires a robust and user-friendly Microsoft Excel-based solution to effectively monitor and analyze real-time foreign exchange (forex) rates. Leveraging data from Yahoo Finance, the solution should provide up-to-date currency exchange information

# 📊 Methodology
  • I established a connection with yahoo finance website to get the market currencies exchange rate data

  • I ensured proper data formats using the power query editor before loading the table into the excel workbook 

  • I enabled data refresh every 5 minutes to ensure current data 

  • I used conditional formatting to highlight positive (green), negative(red) and no(yellow) rate changes.

# 🚀 Exploratory Data Analysis (EDA)
#### Identify the top 5 gaining and losing currency pairs based on Change %.
  • I used the top/bottom conditional formatting rule to highlight the top 5 gainers (green) and losers (red)
  
#### Rank currency pairs by highest and lowest exchange rates.
  • I created a new column called Rank and used the RANK.EQ function to rank based on change %

#### Getting the average price change of all currency pairs.
  •I used the AVERAGE function to get the average price change 

#### Find the exhange rate volatility.
  • I used the STDEV.P function on the change % to get the volatility. 
  
  • In cell N2, I used the IFS & AND function on the Volatility % for the following conditions:
  
    • Low Volatility (< 1%) → Market is stable, fewer price swings.

    • Moderate Volatility (1-3%) → Some price fluctuations, but not extreme.

    • High Volatility (> 3%) → Large price swings, more risky trading conditions.
  

# 📈 Visualizing Market Trends
#### Analyzing currency change movement

  • I created a pivot table using the symbol name and change column

  • I used a clustered bar chart to show the change comparison between the currencies
  
  • The green bars show postive changes while the red bars show negative changes

  • I added a slicer for interactive filtering
  
#### Analyzing currency fluctuations

  • I added helper columns to help differentiate between the positive and negative change %.
  
  • I used a scatter plot to identify patterns in market movements

  • I formatted the scatter plot based on the change %, positive (green) and negative (red).

#### KPI Cards

  • I created cards to show key metrics such as the top currency exchange gainer and loser, the average change and the average change percentage.


  


    

