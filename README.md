# Folium: Geospatial Visualization library

[Folium] library is a leaflet.js library which allows to generate html maps without writing a single javascript code. Overall, Folium strikes a great balance between features, customizability, and ease of programming.

[Folium]: https://python-visualization.github.io/folium/

## Similarities with GeoPlotlib
The geo-plotlib API is inspired by the matplotlib programming model and syntax, the de-facto standard for data visualization in python; this makes it easier for matplotlib users to get started.

The visualization canvas is initially empty, and each command adds a new layer of graphics. The geoplotlib window is displayed when show() is called. Alternatively, the map can be rendered to image file using savefig('filename'), or displayed inline in an IPython notebook using inline().

The biggest advantage of geoplotlib is that it is easy to download library with too less dependencies and easy to use and generate customizable maps. Having less dependencies makes the computation speed faster as well.

## Other features catered by Folium
In addition to features discussed above, Folium also has option of plotting paths and adding location markers to the maps using .PolyLine() and .Marker(). More details will be added to the notebook soon!
