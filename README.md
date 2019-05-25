# Analytics Portfolio
## About
Lorem Ipsum doler.

## Projects
### Whisky Investor | [link](https://whisky-invest.herokuapp.com/)  
![image](whisky.png)
Dashboard to support investing in Scotch Whisky on [WhiskyInvestDirect.com](whiskyinvestdirect.com). Shows the top current investment opportunities, and a detailed pricing analysis.

Technology and features:
- Pricing data scraped using Python (beautifulsoup and regex)
- Daily script deployed on AWS to scrape, process, and model data
- Linear regression and trading cost modelling to predict earnings for each whisky
- Stores daily historic data in an AWS S3 bucket
- Dashboard deployed on Heroku, built using Flask, and Dash by Plot.ly
- Themed using Bootstrap
- Dynamic cross-filtering of charts

### Bike Counter Dashboard | [link](https://app.powerbi.com/view?r=eyJrIjoiNGQyMzYzMTQtOTQzMi00ZDc2LWEzYTktNTlmYmFiMmExMDE4IiwidCI6ImExMDc1MmQ2LTI4NjEtNDEwMy1iNmM4LTg4YTUxMjAxOTI4MiIsImMiOjJ9)  
Daily bike counter data displayed on a web dashboard deployed using PowerBI, using public oData feed updated

Technology and features:
- Importing web data using PowerBI and oData feed ([source](https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bike-and-Pe/2z5v-ecg8))
- Data aggregated by day and hour to show peak activity and trends
- Custom columns and DAX measures to calculate month on month percentage change monthly.
<iframe width="800" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiNGQyMzYzMTQtOTQzMi00ZDc2LWEzYTktNTlmYmFiMmExMDE4IiwidCI6ImExMDc1MmQ2LTI4NjEtNDEwMy1iNmM4LTg4YTUxMjAxOTI4MiIsImMiOjJ9" frameborder="0"> </iframe>

###
