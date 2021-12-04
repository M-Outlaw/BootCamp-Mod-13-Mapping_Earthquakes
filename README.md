# BootCamp-Mod-13-Mapping_Earthquakes
Build data visualizations using JavaScript and D3 and Leaflet libraries to map GeoJSON earthquake data.

## Overview of Project
The purpose of this analysis is to help Basil, the head of the earthquake disaster response team for the Disaster Reporting Network, create informative and easy to use earthquake maps to bring in users to the Disaster Reporting Network. The map Basil wants created will show the difference in the magnitudes of earthquakes that have occurred in the past 7 days across the globe.

### Process
#### Initial Map
- First, use the Mapbox API to pull background maps to map the earthquake data onto.
- Second, use the Leaflet libraries to:
  * display the chosen Mapbox maps.
  * add a marker layer to indicate the location of each earthquake.
  * provide a pop-up for each earthquake describing the magnitude and location.
- Third, retrieve the url for the GeoJSON data to collect all of the coordinates of each earthquake from the last 7 days.
- Finally, add style to the map to make it more interactive and easier to read.
  * The map has two base layers that the user can toggle between.
    - Street view
    - Satellite view
  * Add the ability to turn the earthquake markers on and off.
  * Change the diameter size of the markers.
    - Larger circles show earthquakes with larger magnitudes.
  * Change the color of the markers.
    - The colors go from light green to red.
    - Green represents a magnitude between 0 and 1.
    - Red represents a magnitude of 5 or larger.
    - The color increases in darkness as the magnitude increases.
  * Add a legend to the map.
    - The legend shows which color represents which magnitude.
  * Add pop-ups to each marker so that when the user clicks on a marker the magnitude and location of the earthquake displays.

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>

#### Challenge
##### Tectonic Plate Visualization
- First, add a second Leaflet layer for the tectonic plate data.
- Second, retrieve the url for the tectonic plate boarder data.
- Third, add the lines to denote the boarders of each tectonic plate to the map.
- Finally, stylize the layer.
  * Add the ability to turn the tectonic plate lines on and off.
  * Change the color of the line to bright blue and the line weight to be thicker for readability against the earthquake markers and the different background maps.

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>

##### Major Earthquake Visualization
- First, add a third Leaflet layer to show only major earthquakes.
- Second, retrieve the url for all of the earthquakes that have a magnitude of 4.5 or higher for the last 7 days.
- Third, add the markers for the major earthquakes to the layer.
  * Since this is a separate layer, either all of the earthquakes or only the major earthquakes can be shown separately.
- Finally, stylize the layer.
  * Match the styling used for the all-earthquakes data.

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>

##### Additional Map
- The Mapbox light background map was added to the list of background maps that the user can toggle through since it showed the most contrast compared to the other two background maps already included.

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>

##### Enhancements
1. Change the coding of the colors 
   * The red used for a magnitude of 5 or greater for the all-earthquakes data changed to be used for all earthquakes and major earthquakes with magnitudes of 5 to 6.
   * A darker red used for all earthquakes and major earthquakes with magnitudes of 6 or greater.
2. Change the legend to reflect the change in color coding.

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>

<p align="center"><img src=""width="910" height="477"/></p>
