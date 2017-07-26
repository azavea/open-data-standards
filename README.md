# Open Data Standards

<a rel="external" href="https://azavea.gitbooks.io/open-data-standards/content/"><img alt="Open Data Standards GitBook" style="border-width:0" src="images/open-data-standards-tiles.jpg" /></a>

## Prepared by:

<a rel="external" href="http://www.azavea.com"><img alt="Azavea - Beyond Dots On A Map" style="border-width:0" src="images/azavea_trans_sm.png" /></a>

990 Spring Garden Street, 5th Floor<br>
Philadelphia, PA 19123<br>
(215) 925-2600<br>
[http://www.azavea.com](http://www.azavea.com)<br>

<a rel="external" href="https://twitter.com/azavea"><img alt="Azavea Twitter" height="24" src="images/twitter_icon.png" /></a>
<a rel="external" href="https://www.facebook.com/Azavea/"><img alt="Azavea Facebook" height="24" src="images/facebook_icon.png" /></a>
<a rel="external" href="https://www.linkedin.com/company/azavea"><img alt="Azavea LinkedIn" height="24" src="images/linkedin_icon.png" /></a>
<a rel="external" href="https://github.com/azavea"><img alt="Azavea GitHub" height="24" src="images/github_icon.png" /></a>

## View and Contribute
The online version of the Open Data Standards Report is available as a [GitBook](https://azavea.gitbooks.io/open-data-standards/content/).

You can view and [contribute](contribute.md) to the project by [working on issues](https://github.com/azavea/open-data-standards/issues/) and issuing pull requests via the [GitHub project](https://github.com/azavea/open-data-standards/).

## Executive Summary
This document is an effort to outline the state of open data standards in several civic domains, as well as to suggest domains in which there is strong potential for developing new standards or some nascent work is complete but adoption is not yet widespread.

## Why write this report?
Azavea is a B Corp with a mission to apply geospatial technology for civic, social, and environmental impact while advancing the state-of-the-art through research. We work on projects that range from climate change to public transit and from homelessness to public safety. Almost every project we develop relies, at least in part, on open data. We also developed and continue to operate the open data portal for Philadelphia, [OpenDataPhilly](http://www.opendataphilly.org/), and we share much of our work by releasing our software under open source licenses (check out a few examples at [OpenTreeMap](http://www.opentreemap.org/), [GeoTrellis](http://geotrellis.io), and [DistrictBuilder](http://www.districtbuilder.org/)). We want to encourage and cultivate broad use of open data, open source, open standards, and open algorithms, because we believe it results in better, more functional cities.


## Why do open data standards matter?

Data analysis and visualization are important advocacy tools and have been used to [help nonprofits acquire funding](http://blogs.edweek.org/edweek/early_years/2014/01/map_shows_pre-k_needs_in_phila_funding_results.html) and government agencies choose priority locations for programming. For these projects to take place, one needs access to open data - but access to data that follows a standard formatting methodology is even better.

Open data is more value when it is formatted according to specified standards. Standardizing open data can improve data quality, compatibility with existing applications, and comparisons of data by location. When combined with open source applications, open data standards support the development of an ecosystem of tools that can be used in several locations.

**Success Stories**

Since 2005, the [General Transit Feed Specification (GTFS)](standards/domain_specific_standards/general_transit_feed_specification_gtfs.md) has become the common language for transit. Currently, over 700 agencies worldwide have adopted the GTFS standard for reporting public transit schedules. Open source software like OpenTripPlanner uses GTFS and OpenStreetMap data to enable journey planning and routing. The Network Analyst extension for Esri ArcMap also incorporates GTFS data for transit routing. While mainly used for trip planning, GTFS data can also be used for data visualization and maps, measures of accessibility, and timetable creation.

[Local Inspector Value Entry Specification (LIVES)](standards/domain_specific_standards/local_inspector_value_entry_specification_lives.html) was developed by Code for America in cooperation with Yelp and the City of San Francisco to enable municipalities to publish restaurant inspection information to Yelp. [According to Yelp](https://www.yelp.com/healthscores/feeds), 20 municipalities have LIVES feeds, to date. The fact that this standard integrates with Yelp, means that the public has easy access to restaurant health score data in the cities that have adopted the standard.


## Criteria for Selecting Standards
This report is organized into two sections, one for standards that have been released and are in use in at least a few cities, and a second section for potential new standards.

The criteria used to select the standards includes the following:

 * *Location-based* - Azavea is a geospatial analysis and visualization company, so we have focused on standards that have a location component; that turns out to not limit us very much as the vast majority of data being released by government has a location component to it.
 
 * *Published standard* – Documentation for the specification has been published and is available online.
 
 * *Machine-readable* - Based on JSON, CSV, XML, or similar structure that can be consumed by software in a consistent, organized way
 
 * *Adoption* - Adopted by at least one large city or heavily used by an aggregator of civic data

## What can I do to support open data standards?

There are several ways you can support open data standards.

* Contact the Open Data Officer for your city to learn about the ways that open data standards are being used in your region.

* Explore the open data portal for your city. If you see open data that is not published to a standard, use the contact information provided on the open data portal to notify the team or contact the government department that manages data efforts.

* [Find your local elected officials](https://live.cicerodata.com/) and contact them to tell them about the importance of supporting open data standards.

* Use open data that is published with a standard in a civic hacking project. Build tools that utilize open data standards - prove their utility!

* Contribute to OpenStreetMap through the IDeditor, Humanitarian OpenStreetMap Team Tasking Manager, or at a Missing Maps Mapathon. OpenStreetMap uses several open data standards to provide a free and collaborative map of the world.


## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br>
The Open Data Standards Report by <a href="http://www.azavea.com">Azavea</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
