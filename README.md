# Mapping_Earthquakes
Module 13

## Overview
The purpose of this code is to create a dashboard to see earthquakes and their magnitude on an interactive map over the last week. 

### Resources
JS, HTML, GeoJSON, Mapbox, Leaflet, Data from USGS and provided from class.

## Results
There are 3 different views available for the visualization, for the user to find which they prefer.
- Street View
- Satellite View
- Dark View

each view includues 3 different layers:
- Earthquakes (this includes all earthquake data within the last 7 days)
- Tectonic Plates (allows you to see where the earthquakes take place along fault lines)
- Major Earthequakes (this narrows down the earthquakes to those which are greater than 4.5 magnitude and assigns a color based on magnitude (similarly to all earthquakes) and the darker the red, the higher the magnitude)

These different layers are dynamic, all or one can be applied to the the view

## Summary
this is a great source to use to simply understand size and location of earthquakes in the last week. it will update automatically so thanks to the api, any time you check this you will see that the information from USGS displaying on the visualization is current. As of the last seven days, the larger earthquakes are occuring on fault lines and mainly in the southern hemisphere.