# Leaflet Challenge - Visualizing Data with Leaflet

The idea with this challenge is to demonstrate understanding of basic leaflet functions and how leaflet works.  In this case, taking US Geographic Data regarding earthquakes and creating a map that visualizes basic earthquake data in a graphic way.  The the size and depth of an earthquake event in the U.S. are depicted in terms of size and color, respectively, of a circular marker.  Each marker can then be clicked to view specific data or each earthquake.  

One important feature of leaflet is the use of the layer concept.  In this case, each level of earthquake -  "minor", "moderate", "serious", "major", -  is a leaflet layer that can be accessed and filtered using the "sandwich" menue in the upper right-had corner of the map.

Leaflet.js is also used to build a legend that is displayed in the lower right.  Not only does the legend correspond to the depth color layer depicted on the map, it counts up and summarizes the number of each type of earthquake event for the viewer.

All code is accessible in this repo and the map can be viewed using Visual Studio (or equivalent) and calling the index.html file using the local server tool (Live Server in the case of Visual Studio).

Directions of the challenge are listed below.  Due to time constraints, only the first, required, part of the challenge was completed.  



# Leaflet Homework - Directions

## Background

![1-Logo](Images/1-Logo.png)

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Before You Begin

1. Create a new repository for this project called `leaflet-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: **Leaflet-Step-1** and **Leaflet-Step-2**.

4. This homeworks utilizes both **html** and **Javascript** so be sure to add all the necessary files. These will be the main files to run for analysis.

5. Push the above changes to GitHub.

## Your Task

### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

Your first task is to visualize an earthquake data set.

1. **Get your data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

   * **HINT** the depth of the earth can be found as the third coordinate for each earthquake.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.

- - -

### Level 2: More Data (Optional)

![5-Advanced](Images/5-Advanced.png)

The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it along side your original set of data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

In this step we are going to..

* Plot a second data set on our map.

* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

* Add layer controls to our map.

- - -

### Assessment

Your final product will be assessed on the following metrics:

* Completion of assigned tasks

* Visual appearance

* Professionalism

* Ensure your repository has regular commits and a thorough README.md file

**Good luck!**

## Rubric

[Unit 17 Rubric - Leaflet Homework - Visualizing Data with Leaflet](https://docs.google.com/document/d/1h1iH67V7UKOitS6K3nRrnOYbx-3KwEDC6ZWzpzDKxLc/edit?usp=sharing)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
