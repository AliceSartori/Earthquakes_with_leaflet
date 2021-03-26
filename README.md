# Visualizing Data with Leaflet

## Background

Welcome to the United States Geological Survey. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## Technologies

The USGS provides earthquake data in a number of different formats, updated every 5 minutes through API. I picked the API with endpoint with data from the past 7 days to pull the data for the visualization, as well as picked the data from anther API endpoint (https://github.com/fraxen/tectonicplates) to illustrate the relationship between tectonic plates and seismic activity.

## Results

1. The size of the circles/data markers reflects the magnitude of the earthquake and the depth of the earthquake is reflected by the colors: Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color.
2. There is a strong correlation between tectonic plates movements and seismic activity:  it is relatively easy to see the relationships between earthquakes and the plate boundaries. Along divergent boundaries like the mid-Atlantic ridge and the East Pacific Rise, earthquakes are verycommon, but restricted to a narrow zone close to the ridge.

