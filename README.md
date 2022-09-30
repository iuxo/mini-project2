# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
Combining the Foursquare API with Yelp API to create my own database of restaurants near a location that are walkable (within 1000m).

See which service has better coverage of the location.

Calculated by finding the average number of reviews per restaurant. 


## Process
### Getting familiar with the APIS
Request the data through get requests with the parameters (name, location, distance, ratings, number of ratings, price)
### Parsing
Search through the relevant data and add that data to my own database using pandas package.


## Results
Foursquare had a little better coverage averaging 10 more reviews per restaurant than Yelp in my area.

## Challenges 
One missing negative sign from my code cause me to get empty results from the requests.
Could not figure what was the problem until I finally saw that west longitude is negative.

## Future Goals
Search through the documentation more to get rich data from both Foursquare and Yelp to get a more interesting table.