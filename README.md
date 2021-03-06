# Renewable-energy-generator-forcast
The hourly data collected electricity production of solar and wind speed generations was from [Electronics Testing Center](https://www.etc.org.tw/en-us/default.aspx), Taiwan. 

Data from solar generator included DOWNWARD SHORT WAVE FLUX AT GROUND SURFACE(SWDOWN) and electricity production (PAC), and data from wind drive generator included 10 meter high of wind speed(WS10m), 65 meters high of wind speed (WS65m) and electricity production(PAC). There are five solar generation observations and two wind speed generations. 

This research visualized the insight of collected data and provided a deep learning model-LSTM to predict electricity production. 

### File description
Writing language: R

final-report.Rmd: The original markdown in R

final-report.md: Easy to see the code and outcome

### Project outline
Data preparation for solar generator
- Loading data
- Transform the data to time series
- Remove missing data
- Standardize the data

Data visulation for solar generator
- Solar data in different time range
- Solar data in different location
- Correlation between PAC and SWDOWN (ex. Chunghwa)

Data preparation for wind driven generator

Deep learning for LSTM
- Solar data
- Wind data

### Summary
Through different graphs, the electricity production from solar generator declines during winter, which reflects the season in Taiwan.  
Besides, the LSTM model predicts electricity production with great evaluation. 

##### Data resource: Electronics Testing Center,Taiwan
