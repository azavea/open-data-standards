# General Standards - Geospatial Data

## KML

| **Current Status** | Open Standard by Open Geospatial Consortium; broad use |
| --- | --- |
| **Version Number** | 2.3 |
| **Key Contacts** | KML 2.3 Standards Working Group [http://www.opengeospatial.org/projects/groups/kmlswg](http://www.opengeospatial.org/projects/groups/kmlswg) |
| **Implementing Agencies** | Various – KML support is included in Google products as well as several open source and commercial products. Open source libraries have also been released to support desktop software integration. |
| **Documentation** | [http://www.opengeospatial.org/standards/kml/](http://www.opengeospatial.org/standards/kml/) |
| **Founding/Sponsoring Organizations** | Created by [Keyhole, Inc](http://en.wikipedia.org/wiki/Keyhole,_Inc), which was acquired by [Google](http://en.wikipedia.org/wiki/Google) in 2004\. Later submitted to Open Geospatial Consortium, which now oversees the standard. |

**Background**
<br>
Keyhole Markup Language (KML) is an XML notation for expressing geographic annotation and visualization. This notation can be viewed within web-based and two-dimensional maps and three-dimensional Earth browsers. KML was originally named Keyhole Earthviewer and developed for use with Google Earth software. It was created by Keyhole, Inc, which was acquired by Google in 2004\. In 2008, the Open Geospatial Consortium adopted KML as an international standard. While Google Earth was the first program able to view and edit KML files, it was later supported in several mapping software tools.

**Analysis**
<br>
KML is widely used for use of sharing 2D and 3D geospatial data in xml format on the web. It is well suited for sharing styled geographic data but attribute data (tabular information conventionally attached to a geometry feature) is not well supported. Metadata is also not supported. The use of KML as an interchange standard is declining. Further, a new version of the standard that would be harmonized with other OGC standards was never released and no new versions have been released since it was submitted by the OGC.

*   KML support in GDAL/OGR - [http://www.gdal.org/drv_libkml.html](http://www.gdal.org/drv_libkml.html)
*   Google LibKML - [https://github.com/google/libkml](https://github.com/google/libkml)
*   LibKML resources - [https://code.google.com/p/libkml/w/list](https://code.google.com/p/libkml/w/list)


## GeoJSON

| **Current Status** | Wide Adoption in web apps and APIs |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | [http://lists.geojson.org/listinfo.cgi/geojson-geojson.org](http://lists.geojson.org/listinfo.cgi/geojson-geojson.org) |
| **Implementing Agencies** | Organizations building Web Mapping Applications |
| **Documentation** | [http://geojson.org/geojson-spec.html](http://geojson.org/geojson-spec.html) |
| **Founding/Sponsoring Organizations** | OpenGeo |

**Background**
<br>
This data standard was originally developed by:

*   Howard Butler (Hobu Inc.)
*   Martin Daly (Cadcorp)
*   Allan Doyle (MIT)
*   Sean Gillies (UNC-Chapel Hill)
*   Tim Schaub (OpenGeo)
*   Christopher Schmidt (MetaCarta)

GeoJSON is an open standard format for describing a variety of geographic data structures. A GeoJSON object may represent a geometric feature, or a collection of features. The GeoJSON format supports the following geometry types: Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon, and GeometryCollection. GeoJSON features contain a geometry object along with additional properties. A GeoJSON feature collection represents a list of features. GeoJSON is supported in the OpenLayers client and the GDAL/OGR library. Plug-ins are also available for Geo-Server and CartoWeb. Additional information can be found at: [http://en.wikipedia.org/wiki/GeoJSON](http://en.wikipedia.org/wiki/GeoJSON)

**Analysis**
<br>
GeoJSON can also store non-spatial attributes using JavaScript Object Notation. This data standard differs from many other common geospatial data formats because it is maintained by an internet working group of developers as opposed to a formal standards organization. TopoJSON, an extension of GeoJSON, encodes geospatial topology and typically stores data in smaller file sizes. GeoJSON can also be combined with Leaflet to create interactive maps that are mobile friendly. Github recently began to support the rendering of GeoJSON in the web browser.

**Additional Resources**

*   GeoJSON in OpenLayers: [http://dev.openlayers.org/docs/files/OpenLayers/Format/GeoJSON-js.html](http://dev.openlayers.org/docs/files/OpenLayers/Format/GeoJSON-js.html)

*   GeoJSON in GDAL: [http://www.gdal.org/drv_geojson.html](http://www.gdal.org/drv_geojson.html)

*   GeoJSON in GitHub:[https://help.github.com/articles/mapping-geojson-files-on-github](https://help.github.com/articles/mapping-geojson-files-on-github)

*   GeoJSON in Leaflet: [http://leafletjs.com/examples/geojson.html](http://leafletjs.com/examples/geojson.html)


## Shapefile

| **Current Status** | Wide Adoption |
| --- | --- |
| **Version Number** | No version numbers – last update was July 1998 |
| **Key Contacts** | Esri |
| **Implementing Agencies** | Companies, Education Organizations, Government Agencies that create, store and manipulate geospatial data |
| **Documentation** | [http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) |
| **Founding/Sponsoring Organizations** | Esri |

**Background**
<br>
The shapefile was originally developed by the Geographic Information Systems software company, Esri, for the storage of geospatial data. Though not technically an open, community standard, Esri published the specification in the 1990’s and it is has become an extremely common data format for the storage and distribution of spatial data.

A shapefile is a file format used to store the geometric location and attribute information of geographic features. Geographic features in a shapefile can be represented by points, lines, or polygons (areas).

The shapefile is in fact a grouping of several files formatted to represent different aspects of geodata:

* _.shp_— shape format; the feature geometry itself.

* _.shx_— shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly.

* _.dbf_— attribute format; columnar attributes for each shape, in dBase IV format.

* .prj — projection format; an optional file; coordinate system and projection information

* .lyr — layer format; an option file; contains display specifications for ArcGIS software including color, labeling, etc.

**Analysis**
<br>
Because shapefiles are stored as multiple files, they are not the simplest way to store and transfer data; however they do a successful job in storing additional data about geospatial dataset such as attributes, projection, zymology and metadata.Newer data formats such as GeoJSON and KML allow for the easier transfer and quick visualization of data, especially on the web, but key attributes are not as successfully stored. For simple point features, tabular CSV (comma separated values) is popular for the distribution of data with coordinates, though no metadata or embedded projection is possible. There are limitations of size (1 gb of data) and field length which is limiting when storing complex or large datasets.

For web mapping, many online tools have adapted to the structure of the shapefile and enabled the ability to upload a zipped shapefile for web visualization.

**Additional Resources**

*   [http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm)

*   [http://shapelib.maptools.org/](http://shapelib.maptools.org/)

*   [http://wiki.openstreetmap.org/wiki/Shapefiles](http://wiki.openstreetmap.org/wiki/Shapefiles)

*   [https://code.google.com/p/pyshp/](https://code.google.com/p/pyshp/)

*   [http://www.gdal.org/drv_shapefile.html](http://www.gdal.org/drv_shapefile.html)

*   [http://mapserver.org/input/vector/shapefiles.html](http://mapserver.org/input/vector/shapefiles.html)


## OGC GeoPackage

| **Current Status** | Adopted in early 2014 and beginning to be integrated into software tools; not yet widely used but significant demand for mobile applications |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | info@opengeospatial.org |
| **Implementing Agencies** | Organizations using Open GeoSpatial Data Formats |
| **Documentation** | [http://www.opengeospatial.org/standards/geopackage](http://www.opengeospatial.org/standards/geopackage) |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium |

**Background**
<br>
This standard was developed as a successor to the popular shapefile format. This OGC Encoding Standard defines GeoPackages for exchange and GeoPackage SQLite Extensions for direct use of vector geospatial features and / or tile matrix sets of earth images and raster maps at various scales.

This direct use allows support by an environment, like an API, and means the user can access and edit data in a native storage format without intermediate format transactions. Identical requests from different client applications produce identical access and edit results and maintain data integrity.

GeoPackages are compatible with all computing environments, but are especially useful in areas with limited connectivity and bandwidth on mobile devices.

**Analysis**
<br>
Unlike shapefiles, this spatial data format supports both vector and raster data formats and can support relational data models as well as multi-user and disconnected editing use cases.The standard was only recently finalized but is already supported in both commercial and open source software.It responds to a significant gap in mobile data collection and the poor match between existing data structures and disconnected editing use cases.

**Additional Resources**

*   Github Issue Tracking: [https://github.com/opengis/geopackage/issues](https://github.com/opengis/geopackage/issues)

*   Submit Change Request: [https://portal.opengeospatial.org/public_ogc/change_request.php](https://portal.opengeospatial.org/public_ogc/change_request.php)

*   [http://www.geopackage.org/](http://www.geopackage.org/)

*   [https://bitbucket.org/luciad/libgpkg](https://bitbucket.org/luciad/libgpkg)

*   [http://demo.luciad.com/GeoPackage/](http://demo.luciad.com/GeoPackage/)

*   [http://www.gdal.org/drv_geopackage.html](http://www.gdal.org/drv_geopackage.html)


## OGC WMS/WFS/WCS/WMTS/WPS

| **Current Status** | Wide Adoption |
| --- | --- |
| **Version Number** | Varies |
| **Key Contacts** | info@opengeospatial.org |
| **Implementing Agencies** | Organizations using Open GeoSpatial Data Formats |
| **Documentation** | See Below |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium |

**Background**
<br>
_Web Map Service (WMS) 1.3_
<br>
The geographic layers and area of interest to be processed are defined by the WMS request. One or more geo-referenced images are returned and can be displayed in a browser application.
[http://www.opengeospatial.org/standards/wms](http://www.opengeospatial.org/standards/wms)

_Web Feature Service (WFS) 2.0_
<br>
Instead of sharing geographic information at the file level using a File Transfer Protocol (FTP), the WFS provides direct access to geographic information at the feature and feature property level.
[http://www.opengeospatial.org/standards/wfs](http://www.opengeospatial.org/standards/wfs)

_Web Coverage Service (WCS) 2.0_
<br>
Web Coverage Service (WCS) coverage data is multi-dimensional and can be accessed over the internet.
[http://www.opengeospatial.org/standards/wcs](http://www.opengeospatial.org/standards/wcs)

_Web Map Tile Service (WMTS) 1.0_
<br>
The Web Map Tile Service (WMTS) offers scalable, high-performance services for distribution of maps on the web.
[http://www.opengeospatial.org/standards/wmts](http://www.opengeospatial.org/standards/wmts)

_Web Processing Service (WPS) 1.0_
<br>
Rules for stadardization of inputs and outputs for geospatial processing services are provided by the Web Processing Service (WPS).
[http://www.opengeospatial.org/standards/wps](http://www.opengeospatial.org/standards/wps)

**Analysis**
<br>
The OGC publishes a broad range of standards, most of which are not widely adopted. However, this core set of web map publishing standards is in broad use in both open source and commercial software tools and continues to provide value and have active communities of people using and improving upon them.
