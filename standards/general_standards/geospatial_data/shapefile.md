# Shapefile

| Item | Description |
| --- | --- |
| **Current Status** | Wide Adoption |
| **Version Number** | No version numbers – last update was July 1998 |
| **Key Contacts** | Esri |
| **Implementing Agencies** | Companies, Education Organizations, Government Agencies that create, store and manipulate geospatial data |
| **Documentation** | [http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) |
| **Founding/Sponsoring Organizations** | Esri |
<br>

## Background

The shapefile was originally developed by the Geographic Information Systems software company, [Esri](http://www.esri.com/), for the storage of geospatial data. Though not technically an open, community standard, Esri published the specification in the 1990’s and it is has become an extremely common data format for the storage and distribution of spatial data.

A shapefile is a file format used to store the geometric location and attribute information of geographic features. Geographic features in a shapefile can be represented by points, lines, or polygons (areas).

The shapefile is a grouping of several files formatted to represent different aspects of geodata:

* **.shp** — shape format; the feature geometry itself.
* **.shx** — shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly.
* **.dbf** — attribute format; columnar attributes for each shape, in dBase IV format.
* **.prj** — projection format; an optional file; coordinate system and projection information
* **.lyr** — layer format; an option file; contains display specifications for ArcGIS software including color, labeling, etc.

## Analysis

Because shapefiles are stored as multiple files, they are not the simplest way to store and transfer data. However, shapefiles do a successful job in storing additional data about geospatial dataset such as attributes, projection, zymology and metadata. Newer data formats such as GeoJSON and KML allow for the easier transfer and quick visualization of data, especially on the web, but key attributes are not as successfully stored. For simple point features, tabular CSV (comma separated values) is popular for the distribution of data with coordinates, though no metadata or embedded projection is possible. There are limitations of size (1 gb of data) and field length which is limiting when storing complex or large datasets.

For web mapping, many online tools have adapted to the structure of the shapefile and enabled the ability to upload a zipped shapefile for web visualization.

## Additional Resources

* [http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm)
* [http://shapelib.maptools.org/](http://shapelib.maptools.org/)
* [http://wiki.openstreetmap.org/wiki/Shapefiles](http://wiki.openstreetmap.org/wiki/Shapefiles)
* [https://code.google.com/p/pyshp/](https://code.google.com/p/pyshp/)
* [http://www.gdal.org/drv_shapefile.html](http://www.gdal.org/drv_shapefile.html)
* [http://mapserver.org/input/vector/shapefiles.html](http://mapserver.org/input/vector/shapefiles.html)
