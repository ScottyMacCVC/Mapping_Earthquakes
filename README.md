# Mapping Earthquakes: The New Shake on Things

## We are creating interactive maps using the Leaflet.js library. We use Javascript and HTML to gather information on earthquakes and pull from GeoJSON files. We then add the information to a visually pleasing and usable map. 

## Overview 
Our team would like to view the magnitudes of earthquakes in a given time period. Our information is pulled using an API call from the USGS website in a form of GeoJSON earthquake data. We are able to add our coordinates, magnitudes, and information to the map. The way our script works pulls is based on the date you access the information and will return anything from the past 7 days. The information itself will not plot on the map without the help of Leaflet and Mapbox styles. Our project accesses the information and displays the visualizes the tectonic plates, magnitudes, and coordinates of the event. 

## Reviewing the Search:

- Our base search bar & information is provided as shown below. 
![SearchInfo](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20%26%20Info.JPG)

- The search can be initially filtered by a date. The date does severely limit your search because the date has to be exact. We may want to take a look at these items by city or the other options. 
![DateSearch](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Date%20Search.JPG)

- The data is likely best searched by city. The reason the city is the best starting place is due to a hierarchy of search tasks. Once the filter is set for say, state, then we have to maintain all searches within the state. Whereas searching by city only allows us to expand our search and move more efficiently through our searches. 
![SearchbyCity](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20by%20City.JPG)

![HierarchyIssue](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Hierarchy%20Issue.JPG)

- We can extend our search to more exact items such as shape if we are looking for similarities between sightings.  
![ShapeSearch](https://github.com/ScottyMacCVC/UFOs/blob/main/static/images/Search%20by%20Shape.JPG)
