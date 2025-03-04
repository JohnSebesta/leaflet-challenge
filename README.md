# leaflet-challenge
Overview

In this project, the goal is to visualize earthquake data and analyze seismic activity using a map created with the Leaflet library. The data is sourced from the USGS GeoJSON Feed, which provides earthquake data updated every 5 minutes. The visualization maps earthquake data points with specific attributes such as magnitude, depth, and location. Additionally, there is an optional challenge to enhance the map by adding tectonic plate data to illustrate the relationship between seismic activity and plate boundaries.

The project is divided into two parts:

Part 1: Creating the Earthquake Visualization, which includes plotting earthquake data on a map and customizing the map with markers, popups, legends, and color-coded attributes.
Part 2: (Optional) Gathering and Plotting More Data, where tectonic plate data is added to the map to demonstrate the connection between plate boundaries and seismic events.
Methodology

Part 1: Create the Earthquake Visualization
Dataset Retrieval:
Visit the USGS GeoJSON Feed page and select a dataset such as "All Earthquakes from the Past 7 Days."
The dataset is available in JSON format, containing data on earthquakes, including their magnitude, location (latitude and longitude), and depth.
Visualization Using Leaflet:
Import the JSON data using its URL.
Use Leaflet.js to create an interactive map.
Plot earthquake data points on the map, with each point representing an earthquake. The points are based on their latitude and longitude values.
Size the earthquake markers according to the magnitude of the earthquake, making larger earthquakes more prominent.
Use color to represent the depth of each earthquake, with darker colors indicating greater depths.
Add popups that provide additional information, such as the earthquake's magnitude, location, and depth, when a marker is clicked.
Customization:
Include a legend on the map that explains the color coding for depth and the size representation for magnitude.
Ensure that the map is interactive, allowing users to zoom in and out and explore the data in detail.
Part 2: Gather and Plot More Data (Optional)
Tectonic Plates Data:
This part is optional but involves adding tectonic plates data to the map to explore the relationship between seismic activity and plate boundaries.
Download the tectonic plates data from the GitHub repository tectonicplates dataset.
Visualization:
Plot the tectonic plates on the map alongside the earthquake data.
Provide options to toggle each dataset on and off independently by using overlays.
Add additional base map layers to offer users more map style options.
Layer Controls:
Implement layer control functionality to allow users to toggle between different data layers (earthquake data and tectonic plates) on the map.
Results

Part 1: Earthquake Visualization
An interactive map was created, successfully displaying earthquake data retrieved from the USGS GeoJSON feed.
Earthquake markers were visualized based on their latitude, longitude, magnitude, and depth. The size of the markers corresponds to the magnitude, while the color represents the depth of the earthquake.
Popups were added to each earthquake marker, displaying additional information about the earthquake.
A legend was included to explain the color coding for depth and the size of the markers based on magnitude.
The map is fully interactive, allowing users to zoom in/out and explore different regions affected by seismic activity.
Part 2: Gather and Plot More Data (Optional)
Tectonic plate boundaries were successfully plotted on the map in addition to the earthquake data, showcasing the relationship between seismic activity and plate boundaries.
Layer controls were added to allow users to toggle between the earthquake data and tectonic plates data.
Additional base maps were made available to users, giving them more options for map styling and visual exploration.

References
ChatGPT
Xpert Learning Assistant
The Tutor Fred Logan
