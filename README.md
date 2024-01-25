__Data__:
I am using data from Kaggle on the distribution of airports by country. The data is collected from the FlightRadar source. In our dataframe (df), the following columns are present:
*name* - airport name
*iata* - International Air Transport Association (IATA) code
*icao* - International Civil Aviation Organization (ICAO) format
*lat* - latitude
*lon* - longitude
*country* - country
*alt* - altitude measured relative to sea level.

__Objective:__
- Verify the data
- Identify the Top 10 countries by the number of airports
- Create visualization
- Add a map of airport distribution by longitude and latitude

__Used libraries:__
- pandas
- matplotlib
- Point
- geopandas

  
__Results:__
During the data analysis, the airport Charlevoix Municipal Airport with an outdated ICAO code was identified.
The Top 10 countries with the highest and lowest number of airports were determined.
Visualization in the form of a map showing the distribution of airports according to longitude and latitude data.
