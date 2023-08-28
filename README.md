# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

Project to build a statistical model to derive insights on the relationship between the number of bikes in a chosen location and the characteristics of Places of interest in the location.


## Process

Step 1: Connection to CityBikes API and exploration of the structure of the API in order to retrieve Bike Station latitude, longitude, and number of bikes for chosen location.

Step 2: Connection to Foursquare API and exploration of the structure of the API in order to retrieve information for restaurants and bars for each of the bike stations from step 1.

Step 3: Connection to Yelp API and exploration of the structure of the API in order to retrieve information for restaurants and bars for each of the bike stations from step 1.

Step 4: Joining of data from step 1, step 2 and step 3 into a new DataFrame.

Step 5: Use of data visualization to explore the data.

Step 6: Creation of SQLite database to store the data collected.

Step 7: Building of regression model to show relationship between number of bikes and places of interest in the location.

Step 8: Interpretation of results and presentation of findings.


## Results

For the city of Dublin, Foursquare API seems to have higher quality of data because it was observed to have more attributes for each POI in the city. 


Overall, the model suggests that the characteristics of the POIs have a statistically significant impact on the estimated Number of bikes for a given station. 


However the Adj. R-squared indicating the goodness of fit of the model shows that around 13% of the variability in Number of bikes can be explained by the independent variables.


## Challenges 

Project timeframe was shortened due to API request rate limits.
    Request failed: Status code: 429. 
Due to request restrictions on the Yelp API



## Future Goals

Extract different characteristics for modelling.

Different type of model.

Include more categories in API request for POIs to enrich dataset.

