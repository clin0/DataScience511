# DataScience511 Web Scraping Project - Cryptocurrency & Weather

In this project, we are curious whether there is a relationship between the weather and cryptocurrency. We will gather historical data (over the past 10 years) on Philadelphia, PA and Tucson, AZ and glean information on past daily precipitation and high and low temperatures. Meanwhile, we will scrape historical cryptocurrency data for the same period of the weather data. Then, we will merge the weather data to the historical cryptocurrency data to show what the weather was like on each day listed in the crypto currency historical data.

# Project Implementation: 

Bitcoin_plus_weather_history() is a function that represents data collection and data migration from two data sources: Bitcoin website and DarkSky API. There are five global variables:

* CITY - Input your city or a city to your liking
* GPS_COORDS - Your city coordinates
* DARKSKY_API_KEY - Use this example DarkSky API Key or gerenate a new DarkSky API Key: https://darksky.net/dev/docs
* START_DATE - Set the beginning of the date range
* END_START - Set the ending of the date range

Once you have configured the global variables to your preference, an output of data elements will be merged from two data sources.

# First dataset from Bitcoin:
* Date - Timestamp on that given day from Bitcoin
* Open - Open value from Bitcoin
* High -  Highest value on that given day from Bitcoin
* Low - Lowest value on that given day from Bitcoin
* Close - Closed value on that given day from Bitcoin
* Volume - Volume value on that given day from Bitcoin
* Market Cap - Total market cap value from Bitcoin

# Second dataset from DarkSky:
* Temperature - The temperature on that given day from DarkSky

Summary - Weather summary on that given day from  DarkSky

# Merged dataset from Bitcoin and DarkSky:
* Date - Timestamp on that given day from Bitcoin
* Open - Open value from Bitcoin
* High -  Highest value on that given day from Bitcoin
* Low - Lowest value on that given day from Bitcoin
* Close - Closed value on that given day from Bitcoin
* Volume - Volume value on that given day from Bitcoin
* Market Cap - Total market cap value from Bitcoin
* Temperature - The temperature on that given day from DarkSky

Summary - Weather summary on that given day from  DarkSky


# DataSet Challenges:

A major challenge for using this dataset is that permission for future projects would have to be obtained from CoinMarketCap Legal or pay to use the CMC API. 
This project did receive legal approval from CMC. 

Also, there are only 2,217 data points for CryptoCurrency historical data.
This is due to the new market for Cryptocurrency. More historical data may be needed to perform an in-depth analysis. 
It may be wise to take the historical data for every Cryptocurrency and from what cities they are being traded in and then use that data to create a large dataset with more data points.

Another challenge with this dataset is the data limit from Dark Sky. 
Only 1000 days can be pulled by user per day. 
If you wanted to gather years and years worth of weather data you would have to make it a collaboritve effot or spend many days pulling weather data.
© 2020 GitHub, Inc.
