# Police_Department_Incident_Reports-Project
Visuliztion Project with Folium

> <h3><b><span style="color:navy">Data Base :- </span><a href='https://drive.google.com/file/d/1-7Jlp1aIZYtsfyTwojbwfPOwHqNF3Z7a/view?usp=share_link'><b>Click HERE</b></a> </b></h3>  


## **Spatial visualization of San Francisco Police Department Incidents for 2016**

### Objectives

After completing this lab you will be able to:

>  Visualize geospatial data with Folium


<center>
<img src="Patch12.png" alt="" width="250px" height="300px">
</center>


## **Introduction to Folium**

Folium is a powerful Python library that helps you create several types of Leaflet maps. The fact that the Folium results are interactive makes this library very useful for dashboard building.

From the official Folium documentation page:

*   Folium builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the Leaflet.js library. Manipulate your data in Python, then visualize it in on a Leaflet map via Folium.

*   Folium makes it easy to visualize data that's been manipulated in Python on an interactive Leaflet map. It enables both the binding of data to a map for choropleth visualizations as well as passing Vincent/Vega visualizations as markers on the map.

*   The library has a number of built-in tilesets from OpenStreetMap, Mapbox, and Stamen, and supports custom tilesets with Mapbox or Cloudmade API keys. Folium supports both GeoJSON and TopoJSON overlays, as well as the binding of data to those overlays to create choropleth maps with color-brewer color schemes.

Generating the world map is straigtforward in Folium. You simply create a Folium Map object and then you display it. What is attactive about Folium maps is that they are interactive, so you can zoom into any region of interest despite the initial zoom level.

Let's install Folium
Folium is not available by default. So, we first need to install it before we are able to import it.

