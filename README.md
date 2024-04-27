## Geodata Science Projects Interactive Maps
This project was used to create an interactive OpenStreetMap to show COVID-19 death cases in Nigeria per state as of Dec 27, 2021.

The goal here was to create an interactive OpenStreetMap  which shows the number of Covid death cases in Nigeria on a state-by-state basis, using the geopandas and pandas libraries. Data for this work was sourced personally from the Nigerian Centre for Disease Control (NCDC) website. One thing noticeable during the work is how some of the areas geocoded were out of place. Coordinates were off by a long shout for some, so I had to do some extra work on the geometries of these areas; Delta, Borno, and Niger States.

The interactive map produced by this notebook is saved as a html file and can be used on websites, or web pages intending to display such information. For future use, the dataset should be updated from https://covid19.ncdc.gov.ng/ (as the webpage is updated) and codes re-run to allow an updated version of this information. Information about the number of lab-confirmed covid cases, the number of cases on admission, as well as the number of discharged cases, can also be shown on the map with a little tweak in the codes. 

 
 
**Design Description**

- The idea was to build a web-based interactive map that displays critical information, which in this case is the COVID-19 statistics for each state in the country.
- To accomplish this, first I had to source the data. I did this by downloading a CSV sheet from NCDC containing the required information.
- Then using the Pandas library and other Python functions, I modified the dataset to allow for proper interpretation, after which, I saved a copy of the new dataset as New_df.csv within my directory. All these processes were done in the file, Geodata_Proj_(Interactive_Covid_Map).ipynb
- Using the Optimized_covid_map_notebook.ipynb file and the New_df.csv dataset, I created a final interactive Map called Final_map.html

**Dependencies**
- Pandas
- Folium
- Geopandas
- Branca

**Features**

The following are the contents of the interactive map:
- The data points (coordinate points) indicated by custom health markers.
- Clickable markers that unveil COVID-19 details to users on click
- Marker Clusters: Markers are made to cluster at different zoom levels to allow for proper visualizations for each zoom level
- A colour scheme indicating the degree of death cases in each state
- A legend detailing this colour scheme [bottom left corner of the screen]
- A Layer control panel that allows users to turn on or off the layers in the map  [top right corner of the screen]
- A full-screen panel icon that allows the user to switch between full-screen and normal browser window view. [top right corner of the screen]
- A title header describing the contents of the map
- A zoom panel button that allows the users to zoom in and out of the map with a click.

  
The dataset used for this work is saved as Ncdc data.csv and is downloadable from the files section of this repository. 
 
 Many thanks.
 **COPYRIGHT: CHIMEZIE AZIH**
