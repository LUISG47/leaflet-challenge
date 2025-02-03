# MODULE 15 CHALLENGUE 

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Instructions

The instructions for this activity are broken into two parts:

1. Part 1: Create the Earthquake Visualization
2. Part 2: Gather and Plot More Data

## Part 1: Create the Earthquake Visualization

Your first task is to visualize an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

+ The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

![Screenshot 2025-01-31 at 9 56 20 p m](https://github.com/user-attachments/assets/36abbec4-49ca-4ead-a77d-43b877063507)


+ When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
I choosed the dataset with all earthquakes from the past hour on January 31 2025 10:00 pm


![Screenshot 2025-01-31 at 10 07 09 p m](https://github.com/user-attachments/assets/3257d472-8f82-4a06-b4bd-ded8d0ad1bc8)



2. Import and visualize the data by doing the following:

+ Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude
+ + Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
  + Hint: The depth of the earth can be found as the third coordinate for each earthquake.
+ Include popups that provide additional information about the earthquake when its associated marker is clicked.
+ Create a legend that will provide context for your map data.
+ Your visualization should look something like this map:

![Screenshot 2025-01-31 at 9 36 38 p m](https://github.com/user-attachments/assets/cb150f47-d0b1-46d6-aab5-81dfa7d33777)


## Part 2: Gather and Plot More Data (Optional with no extra points earning)

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at: https://github.com/fraxen/tectonicplates

Perform the following tasks:

+ Plot the tectonic plates dataset on the map in addition to the earthquakes.
+ Add other base maps to choose from.
+ Put each dataset into separate overlays that can be turned on and off independently.
+ Add layer controls to your map.

For this part there's also another map views implemented on the code with different base map layers.

For this demonstration i added the all day earthquakes json from past day taken on Febrary 3 2025 with this link added to the code: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_day.geojson


The display from this day on the maps should look like this:

+ Base Map:
<img width="1712" alt="Screenshot 2025-02-03 at 11 44 26 a m" src="https://github.com/user-attachments/assets/ea24b716-93f6-4613-b416-839c08f83aad" />

+ Terrain Map:
<img width="1706" alt="Screenshot 2025-02-03 at 11 45 10 a m" src="https://github.com/user-attachments/assets/b2120620-deef-4d8f-92fb-09552d83c13a" />

+ Dark Map:
<img width="1707" alt="Screenshot 2025-02-03 at 11 45 19 a m" src="https://github.com/user-attachments/assets/9bf80c83-a21b-479f-b682-893927cab32a" />

+ Light Map:
<img width="1704" alt="Screenshot 2025-02-03 at 11 45 27 a m" src="https://github.com/user-attachments/assets/b9f7daee-61f0-4d17-9563-e9213bee83a7" />








