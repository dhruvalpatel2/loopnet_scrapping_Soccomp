Social Impact On US Businesses 
Contributors - Dhruval Patel, Manan Patel 


Why this App  - Initially started building this app to have business listings along with impact on businesses in those areas so we came up with the idea of creating this app using R-shiny which allowed us to create multiple visualizations, and interactive maps with the data we screaped. 


The Data - there are four tables we are using,

Shiny_app_data.csv - This file contains all the listings of business for sale in the US from loopnet and it contains information about the businesses such as price, location, geocoordinates, squar feet, and building type. 
Source - https://www.loopnet.com/ 


Us_states_data.csv - This file contains all the social demographics of states such as ruling governor party, income tax rate, property tax, median household income, crime rate per 100k and population. 
Source - https://www.tax-rates.org/ 
	 - https://www.forbes.com/advisor/business/best-states-to-start-a-business/
	- https://www.lendingtree.com/business/small/failure-rate/ 
	- https://www.kaggle.com/datasets/alexandrepetit881234/us-population-by-state/ 

NJ_Income - This file contains data about income distribution for each county within New Jersey. 

NJ_sex_data - this contains data for age, sex, and ethnicity data for all the counties in new jersey. 


Data Cleaning - we cleaned the data using regular expressions as well as well as manually adding and removing of the columns, and used google’s api key to get geocoordinates of the listings which helped us visualize the data. 

Mapping/Plotting  - we mainly used ggplot in R to plot barplots, then geom map and leaflet libraries to correctly show elements on the USA map. 

UI - the app contains 4 pages/panels 

1st page - US Listings Map
 
