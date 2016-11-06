# General Standards: Geospatial Data



## OGC GeoPackage

| Item | Description |
| --- | --- |
| **Current Status** | Adopted in early 2014 and beginning to be integrated into software tools; not yet widely used but significant demand for mobile applications |
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

| Item | Description |
| --- | --- |
| **Current Status** | Wide Adoption |
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
