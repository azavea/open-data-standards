# OGC GeoPackage
| Item | Description |
| --- | --- |
| **Current Status** | Adopted in early 2014 and beginning to be integrated into software tools; not yet widely used but significant demand for mobile applications |
| **Version Number** | 1.0 |
| **Key Contacts** | info@opengeospatial.org |
| **Implementing Agencies** | Organizations using Open GeoSpatial Data Formats |
| **Documentation** | [http://www.opengeospatial.org/standards/geopackage](http://www.opengeospatial.org/standards/geopackage) |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium |
<br>

## Background

This standard was developed as a successor to the popular [shapefile](../../standards/shapefile.md) format. This OGC Encoding Standard defines GeoPackages for exchange and GeoPackage SQLite Extensions for direct use of vector geospatial features and/or tile matrix sets of earth images and raster maps at various scales.

This direct use allows support by an environment, like an API, and means the user can access and edit data in a native storage format without intermediate format transactions. Identical requests from different client applications produce identical access and edit results and maintain data integrity.

GeoPackages are compatible with all computing environments, but are especially useful in areas with limited connectivity and bandwidth on mobile devices.

## Analysis

Unlike shapefiles, this spatial data format supports both vector and raster data formats and can support relational data models as well as multi-user and disconnected editing use cases.The standard was only recently finalized but is already supported in both commercial and open source software.It responds to a significant gap in mobile data collection and the poor match between existing data structures and disconnected editing use cases.

## Additional Resources

* Github Issue Tracking: [https://github.com/opengis/geopackage/issues](https://github.com/opengis/geopackage/issues)
* Submit Change Request: [https://portal.opengeospatial.org/public_ogc/change_request.php](https://portal.opengeospatial.org/public_ogc/change_request.php)
* [http://www.geopackage.org/](http://www.geopackage.org/)
* [https://bitbucket.org/luciad/libgpkg](https://bitbucket.org/luciad/libgpkg)
* [http://demo.luciad.com/GeoPackage/](http://demo.luciad.com/GeoPackage/)
* [http://www.gdal.org/drv_geopackage.html](http://www.gdal.org/drv_geopackage.html)
