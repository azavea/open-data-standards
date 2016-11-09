# GeoJSON

| Item | Description |
| --- | --- |
| **Current Status** | Wide Adoption in web apps and APIs |
| **Version Number** | 1.0 |
| **Key Contacts** | [http://lists.geojson.org/listinfo.cgi/geojson-geojson.org](http://lists.geojson.org/listinfo.cgi/geojson-geojson.org) |
| **Implementing Agencies** | Organizations building Web Mapping Applications |
| **Documentation** | [http://geojson.org/geojson-spec.html](http://geojson.org/geojson-spec.html) |
| **Founding/Sponsoring Organizations** | OpenGeo |
<br>
**Background**

This data standard was originally developed by:

*   Howard Butler (Hobu Inc.)
*   Martin Daly (Cadcorp)
*   Allan Doyle (MIT)
*   Sean Gillies (UNC-Chapel Hill)
*   Tim Schaub (OpenGeo)
*   Christopher Schmidt (MetaCarta)

GeoJSON is an open standard format for describing a variety of geographic data structures. A GeoJSON object may represent a geometric feature, or a collection of features. The GeoJSON format supports the following geometry types: Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon, and GeometryCollection. GeoJSON features contain a geometry object along with additional properties. A GeoJSON feature collection represents a list of features. GeoJSON is supported in the OpenLayers client and the GDAL/OGR library. Plug-ins are also available for Geo-Server and CartoWeb. Additional information can be found at: [http://en.wikipedia.org/wiki/GeoJSON](http://en.wikipedia.org/wiki/GeoJSON)

**Analysis**

GeoJSON can also store non-spatial attributes using JavaScript Object Notation. This data standard differs from many other common geospatial data formats because it is maintained by an internet working group of developers as opposed to a formal standards organization. TopoJSON, an extension of GeoJSON, encodes geospatial topology and typically stores data in smaller file sizes. GeoJSON can also be combined with Leaflet to create interactive maps that are mobile friendly. Github recently began to support the rendering of GeoJSON in the web browser.

**Additional Resources**
*   GeoJSON in OpenLayers: [http://dev.openlayers.org/docs/files/OpenLayers/Format/GeoJSON-js.html](http://dev.openlayers.org/docs/files/OpenLayers/Format/GeoJSON-js.html)
*   GeoJSON in GDAL: [http://www.gdal.org/drv_geojson.html](http://www.gdal.org/drv_geojson.html)
*   GeoJSON in GitHub:[https://help.github.com/articles/mapping-geojson-files-on-github](https://help.github.com/articles/mapping-geojson-files-on-github)
*   GeoJSON in Leaflet: [http://leafletjs.com/examples/geojson.html](http://leafletjs.com/examples/geojson.html)

