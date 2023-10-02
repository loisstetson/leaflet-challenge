# leaflet-challenge

In this activity, I'll focus on creating the earthquake visualization. Here are the steps I need to follow:

1. **Get the Dataset:** I will start by obtaining earthquake data from the USGS (United States Geological Survey). They provide earthquake data in various formats, updated every 5 minutes. To access the data, I'll visit the USGS GeoJSON Feed page and select a dataset for visualization.

2. **Import and Visualize Data:** Once I've chosen a dataset (for example, "All Earthquakes from the Past 7 Days"), I'll use the JSON representation of that data by extracting its URL. This JSON data will be the basis for my visualization.

3. **Create a Map:** Using Leaflet, I will create an interactive map that displays all the earthquakes from the selected dataset. The earthquakes will be plotted on the map based on their longitude and latitude coordinates.

4. **Customize Data Markers:** To make the visualization informative, I will adjust the data markers on the map. The size of the markers will represent the magnitude of each earthquake, with larger markers indicating higher magnitudes. The color of the markers will indicate the depth of the earthquakes, with darker colors representing greater depth. I will obtain the depth information from the third coordinate for each earthquake.

5. **Include Popups:** For user interaction and additional information, I will implement popups. When a user clicks on a marker associated with an earthquake, a popup will appear, providing details about that specific earthquake.

6. **Create a Legend:** To provide context for the map data, I'll design and include a legend. This legend will help users understand the relationship between marker size, color, magnitude, and depth in the visualization.

By following these steps, I aim to create a comprehensive earthquake visualization that effectively communicates the dataset's information to viewers.

![image](https://github.com/loisstetson/leaflet-challenge/assets/127718619/0b83cc50-7b09-4621-ae8b-25ec55d0d547)
