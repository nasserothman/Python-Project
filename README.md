# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to use Python skills to extract information from multiple APIs and manipulate the data. I Chose to work with Citybikes API to work on Toronto's
BikeShare Network and connected the information about bike stations to Points of Interests (POIs) from Foursqaure and Yelp APIs.



## Process

   ### Step 1: Explored the structure of the CityBikes API, queried the API and understand the data returned.
   ### Choose the city of Toronto that was covered by the CityBikes API and retrieved all available bike stations in Toronto.
   ###  I used the API to call the latitude, longitude and number of bikes from each bike station.
   ### I parsed through the JSON object into multiple Pandas dataframes.
   ### I joined the dataframes together.
   ### Created visualizations using Python.


## Results
I found out that Yelp is much more detailed than Foursqaure however found the Foursqaure is much easier and staightforward to work with.

## Challenges 
One of the challenges I had to face was to not run out of call requests from Foursqaure so I improvised and created a new dataframe which had 5 rows and used that dataframe to call on Foursqaure and Yelp APIs based on the closest POI within 1000 meters from each station.

## Future Goals
Although using Python for visualization is straighforward, next time, I would use Tableau to visualize my data.
