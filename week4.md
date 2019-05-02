Amin, [02.05.19 00:22]
## Capstone Project (Week 1):    The Battle of Neighborhoods in Toronto


### Introduction & Business Problem: 

A family with 4 young children are wondering which neighborhood is appropriate for them to buy their house in city of Toronto. Their main concern is not the price or the age of the house; However, they concern about the safety and crime rate in that neighborhood since they have 4 teenagers. The factors that should be taken into considerations for this family are as follows:
   - Access to subway stations
   - Low crime and assault rates
   - Access to shopping centers
   - Access to restaurants 

Therefore, the objective of this project is to analyze the neighborhood data in Toronto using PYTHON and its powerful libraries to recommend to this family the most suitable location to buy their house.

### Data
The first set of the data we use in this project is geospatial location for each neighborhood. The major portion of the data used in this project will be taken from Foursquare API, which is a crowd sourced, comprehensive geographical data source. 
using Foursquare API, we can get insight on the most popular venues in each neighborhood, their photos, ratings and customer comments on those venues. 
Moreover, from the City of Toronto web portal, we downloaded the dataset related to crime rates and number of assaults from https://www.cbc.ca/toronto/features/crimemap/ and pre-processed that data set to combine with the spatial data of each neighborhood. 
The last dataset is a table on the wikipedia for subway station in each neighbourhood which needs to be scraped from the wikipedia page. 

### Approach:
- Collect the neighborhood-borough data for Toronto using web scraping.
- Collect the subway stations data for each neighborhood using web scraping.
- Download and Collect the crime and assault data for each neighborhood.
- Pre-Process and clean the crime rate data.
- Find all venues for each neighborhood using Foursquare API.
- Filter out all venues for shopping centers and restaurants.
- Rate neighborhoods and sort that data.
- Visualize the Ranking of neighborhoods using folium library.