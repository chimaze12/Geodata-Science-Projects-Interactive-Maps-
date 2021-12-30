# Geodata-Science-Projects-Interactive-Maps-
This project was used to create an interactive OpenStreetMap to show covid death cases in Nigeria per state as at Dec 27, 2021.


The goal here was to create an interactive OpenStreetMap  which shows the number of Covid death cases in Nigeria on a state-by-state basis, using the geopandas and pandas libraries. Data for this work was sourced personally from the Nigerian Centre for Disease Control (NCDC) website. One thing noticebale during the work is how some of the areas geocoded were out of place. Coordinates were off by a long shout for some, and so I had to do some extra work on the geomtries of these areas; Delta, Borno, and Niger States.

The interactive map produced by this notebook is saved as a html file and can be used on websites, or webpages intending to display such information. For future use, the dataset should be updated from https://covid19.ncdc.gov.ng/ (as the webpage is updated) and codes re-run to allow an updated version of this information. Information about the number of lab-confirmed covid cases, number of cases on admission, as well as the number of discharged cases can also be shown on the map with a little tweak in the codes. 

The dataset used for this work is saved as Ncdc data.csv, and is downloadable from the files section of this repository. 
 
 Many thanks.
