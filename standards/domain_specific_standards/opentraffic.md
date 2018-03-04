# OpenTraffic

| Item | Description |
| --- | --- |
| **Current Status** |Developed by World Bank and partner organizations  |
| **Version Number** |v 2  |
| **Key Contacts** |  |
| **Implementing Agencies** | World Bank, government transportation agencies |
| **Documentation** | [OpenTraffic project](http://opentraffic.io/) |
| **Founding/Sponsoring Organizations** | World Bank, Conveyal, MapZen |
<br>

## Background
OpenTraffic, a collaborative project of the World Bank, Conveyal, and Mapzen, is coordinating efforts to develop an open source data and software platform for sharing, display, and analysis of anonymized traffic statistics.

The OpenTraffic project is part of the [SharedStreets project](sharedstreets.md) project.

## Analysis

While U.S. State DOTs and local transportation agencies conduct significant additional traffic surveys and distribute data, there is not wide adoption of a standard. Additional data sources from private firms, like Streetlytics, Google Maps, Waze, and others, are not available in open formats.

OpenTraffic is an effort to create a platform that will enable accurate routing, estimated time of arrival, and travel statistical calculations based on traffic feeds. It includes both software tools and a traffic data exchange format. The v1 data structure includes both a baseline tile structure and a current conditions structure, organized in a binary protocol buffer format. In v2, a [linear referencing system for OpenStreetMap (OSMLR)](https://github.com/opentraffic/osmlr) is used.

## Additional Resources

* [OpenTraffic project](http://opentraffic.io/) - collaboration between the World Bank, Conveyal and Mapzen
* [OpenTraffic v2 Platform Overview](https://github.com/opentraffic/otv2-platform)
* [OpenTraffic OSMLR introduction](https://github.com/opentraffic/osmlr/blob/master/docs/intro.md)
* [OpenTraffic v1 Traffic Data Exchange Format](https://github.com/opentraffic/traffic-data-exchange-format)
* US DoT Traffic Volume Trends (TVT) - [http://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm](http://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm)
* US DoT Travel Monitoring Guide - [http://www.fhwa.dot.gov/policyinformation/tmguide/](http://www.fhwa.dot.gov/policyinformation/tmguide/)

