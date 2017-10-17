# Lab 03 Control Towers and Airports

### Introduction

The purpose of this lab was to familiarize ourselves with basic scripting and coding necessary to implement  webmaps. Additionall, several Leaflet techniques for implementing layers with geojson where used.



### Functions

The major functions of the lab are:

- PointToLayer functions on the airport geojson which indicates the "name" value of each airport
- PointToLayer function on the state boundary geojson which indicates the "count" of airports in each particular "state"
- A LayerControl function which allows for changing of the basemaps available through Map Box, in the top right corner
- A ZoomToFeature function which zooms to the bounds of each state
- A HighlightFeature and ResetFuture for mouse on and mouse off events, respectively



### Libraries

- Leaflet: https://unpkg.com/leaflet@1.2.0/dist/leaflet.js
- Leaflet Ajax: https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js
- JQuery: https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js
- Chroma: https://cdnjs.cloudflare.com/ajax/libs/chroma-js/1.3.4/chroma.min.js



### Data Sources

- Airports geoJson: https://catalog.data.gov/dataset/usgs-small-scale-dataset-airports-of-the-united-states-201207-shapefile
- US States geoJson: http://bost.ocks.org/mike
- Basemaps: [OpenStreetMaps](http://openstreetmap.org/)



### Credits

Fall 2017 | GEOG 371 | Geovisualization: Web Mapping © Grant Zoch

