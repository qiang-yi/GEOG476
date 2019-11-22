
# Final Project

##### Instructor: Yi Qiang <br/>Email: yi.qiang@hawaii.edu <br/>Nov. 22th, 2019
---

In the final project, you need to create a web map on a specific topic by yourself. The final project occupies 20% of your final grade.

## 1. Work by yourself
Limited assistance or guidance will be provided. For instance, I can provide information about data sources and comment on the feasibility of your mapping ideas. However, the development process is generally on your own. You may find the following resources useful for your project:

- All instructions are in [GitHub](https://github.com/qiang-yi/GEOG476).
- Solutions of the assignments will be release soon.
- Leaflet [tutorials](https://leafletjs.com/examples.html) and [documentation](https://leafletjs.com/reference-1.6.0.html).
- Google

## 2. Define a topic
Define a topic for your map. Create a web map containing data layers relevant to the topic. Don't dump irrelevant layers onto a web map. For instance, a invasive species layer can be plotted on top of a vegetation layer. However, it doesn't make much sense to plot invasive species with greenhouse gas facilities in the same map.

## 3. Choose an appropriate map type
In this class, we learned three types of thematic maps, including proportional symbol, choropleth map and 3D prsim map. Consider the characteristic of data (point or polygon) that you want to map, choose an appropriate type of map to start.

## 4. Map Interactivity
Your map should have some interactive controls to help users to read the map. Examples controls are:
- Map zoom in/out control
- Popup window when click
- Fixed window to display attribute
- Popup window when mouse is over
- Feature highlight when mouse is over
- Multiple layers with layer controls
- Basemap toggle control
- Floating window of map title and description.
- Legend.

You don't need to add all these controls into your map. Some of the controls just don't get along with each other. At least, you should have some of them to make your map interactive.

## 5. GeoJSON or WMS
The two mapping methods have their pros and cons. The main issue of GeoJSON data is the data size (need to be < 2Mb) and the programming complexity for styles (e.g. colors). In contrast, WMS layers support lager datasets (with more points or polygons), but lack of interactivity in map (e.g no clicking on feature, no mouse-over responses).

## 6. Data Sources
You need to find the data by yourself. You need to convert the data into appropriate format (e.g. GeoJSON) for your web map. You may find useful data in [GeoDA Data inventory](https://geodacenter.github.io/data-and-lab/) and [Hawaii Geospatial Data Portal](http://geoportal.hawaii.gov/).

## 7. Strategies for the Project
Starting from simple things. You can start your project from modifying a web map you created in class (excluding Lesson 7: first leaflet map, which is to simple). For instance, you can replacing the data with your own data. When it works, you can try to add more controls or layers based on the need and your skill level.

However, only replacing data for a done assignment cannot get full credits for your final project. You need at least do some modifications or improvements in the functionalities (e.g. having additional layers and/or controls).

**Start as soon as possible!!**. Don't wait to do it at the last minute.

## 8. Project submission
You need to upload your final project onto UH web space and submit an URL to access your web map through Laulima by **Dec 13 (Friday)**.

In addition to the web map, you need to write a brief report to describe your project. The report should including the following information:
- Introduction: background and motivation; why you want to create this map.
- Data sources: where you downloaded them and what the features and attributes are.
- Description of your code: explain what the objects and functions do.
- Functionalities of your map: what the controls do and how to use them.
- Conclusion: how you find your map is useful and what have you learned in the project.

The report cannot exceed 4 pages (single line, font size size), including figures, codes and text.

The report is also due on **Dec 13 (Friday)**
