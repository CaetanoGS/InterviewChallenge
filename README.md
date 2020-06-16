# Interview Task

## Overall objective:

Create a simple web application which can visualize geospatial data and react to user input

## Explanation:

Along with this text file are two data sources, "states" and "points". These represent geospatial data in the form of polygons and point-geometries, respectively, with some random tabular data attached as attributes. This data is not meaningful, but it has the same format of real energy-system related geospatial data which we will be exposing through web applications in this position. Therefore, the task is to extract this data from its raw format (ESRI ShapeFile, '.shp') and display it via a web application. 

This application should show the 'states' polygons with a semi-transparent color related to whichever of its attributes the user would like to visualize, and on top of this the 'points' should be shown as well. Please also include some simple UI elements, such as a way to select which of the 'states' attributes should be visualized, as well as a mouse-over ('hover') tooltip for the displayed 'points'.

 Lastly, please show a basemap behind the data and style the components in a way that is "nice-ish" using the UI library like MaterialJS. You are also encouraged to add any additional "flavoring" you want.

## Tips:

1. The "web application" can just be a folder of html, css, and javascript files which can be opened from the browser (no need for an actual server to host it)
2. Do not spend too much time on the styling via the UI Library. The point here is not to already make a super nice page, but rather to just prove that you are capable of using such a library.
3. If you need help with the geospatial mapping, I suggest using the "Mapbox" library for web-based visualization of geospatial data. See these links for some starting points...
   - https://docs.mapbox.com/mapbox-gl-js/example/geojson-polygon/
   - https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/#create-a-mapbox-gl-js-map
4. This task can be accomplished without the use of a front-end frame work. But if you can arrange it as a modular "React" application, then that would be very impressive!
5. The web-tools at https://mapshaper.org can be used to visualize and transform ESRI Shapefiles into other formats. Another option would the the installable application "QGIS", which is very good in my opinion. Nevertheless, I have already used this service to create geojson file which should be all you need.
6. The 'states' data has three attributes: 'number', 'color', and 'area'. Meanwhile, the 'points' data has only two attributes: 'NAME_1', and 'NAME_2'.
