## About Me
I enjoy data, technology, and whisky. The following are some personal projects that loosely follow that theme.

## Whisky Investor | [link](https://whisky-invest.herokuapp.com/)  
![image](whisky.png)  
Dashboard to support investing in Scotch Whisky on [WhiskyInvestDirect.com](whiskyinvestdirect.com). Shows the top current investment opportunities, and a detailed pricing analysis.

####Technology and features:
- Pricing data scraped using Python (beautifulsoup and regex)
- Daily script deployed on AWS to scrape, process, and model data
- Linear regression and trading cost modelling to predict earnings for each whisky
- Stores daily historic data in an AWS S3 bucket
- Multi page dashboard deployed on Heroku, built using Flask, and [Dash by Plot.ly](https://dash.plot.ly/getting-started)
- Themed using Bootstrap
- Dynamic cross-filtering of charts

## Bike Counter Dashboard | [link](https://app.powerbi.com/view?r=eyJrIjoiNGQyMzYzMTQtOTQzMi00ZDc2LWEzYTktNTlmYmFiMmExMDE4IiwidCI6ImExMDc1MmQ2LTI4NjEtNDEwMy1iNmM4LTg4YTUxMjAxOTI4MiIsImMiOjJ9)  
Daily bike counter data displayed on a web dashboard deployed using [PowerBI](https://powerbi.microsoft.com/en-us/), using public [OData](https://en.wikipedia.org/wiki/Open_Data_Protocol) feed updated monthly.

####Technology and features:
- Importing web data using [PowerBI](https://powerbi.microsoft.com/en-us/) and OData feed ([source](https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bike-and-Pe/2z5v-ecg8))
- Data aggregated by day and hour to show peak activity and trends
- Custom columns and DAX measures to calculate month on month percentage change monthly.
<iframe width="800" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiNGQyMzYzMTQtOTQzMi00ZDc2LWEzYTktNTlmYmFiMmExMDE4IiwidCI6ImExMDc1MmQ2LTI4NjEtNDEwMy1iNmM4LTg4YTUxMjAxOTI4MiIsImMiOjJ9" frameborder="0"> </iframe>

## Stock Price Explorer | [link](https://dash-ticker.herokuapp.com/)
![image](stock.png)  
Web App project to display stock ticker information via Dash.

####Technology and features:
- Retrieves historic stock price using the [AlphaVantage API](https://www.alphavantage.co/) using Python requests library
- Single page dashboard deployed on Heroku, built using Flask, and [Dash by Plot.ly](https://dash.plot.ly/getting-started)
- Search for stocks via search box with autocomplete
- Caching with expiry to Redis cache on Heroku to reduce the number of API calls (and stay within the 5 calls per minute API restriction)
- Display multiple stocks in chart
- Dynamically updating table of stock prices

## Stock Price Modelling Using LinkedIn Dataset
