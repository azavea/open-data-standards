# Generic Standards: Data Catalogs


## CKAN API

| **Current Status** | In use by many organizations, well maintained, good documentation |
| --- | --- |
| **Version Number** | v. 3 (CKAN version 2.2) |
| **Key Contacts** | CKAN mailing list ([https://groups.google.com/forum/#!forum/ckan-global-user-group](https://groups.google.com/forum/#!forum/ckan-global-user-group)) |
| **Implementing Agencies** | Many agencies, global |
| **Documentation** | API: [http://docs.ckan.org/en/latest/api/index.html](http://docs.ckan.org/en/latest/api/index.html) |
| **Founding/Sponsoring Organizations** | Open Knowledge Foundation |

**Background**
<br>
The CKAN data catalog has been developed over the course of several years by the Open Knowledge Foundation. It is the leading open source data catalog and supports many key features. The CKAN API supports all of the key features of CKAN, including retrieving lists of data sets, metadata about each data set, search results, add/update/delete data sets and an activity log.

**Analysis**
<br>
The open source CKAN application is well established with many users, including Data.gov.


## Data Catalog Vocabulary (DCAT)

| **Current Status** | Published by W3C as recommendation, but not yet an adopted standard |
| --- | --- |
| **Version Number** | W3C recommendation (Jan. 2014) |
| **Key Contacts** | Mailing list (subscribe at [http://www.w3.org/TR/vocab-dcat/](http://www.w3.org/TR/vocab-dcat/)) |
| **Implementing Agencies** | Unknown |
| **Documentation** | [http://www.w3.org/TR/vocab-dcat/](http://www.w3.org/TR/vocab-dcat/) |
| **Founding/Sponsoring Organizations** | W3C |

**Background**
<br>
DCAT is an RDF vocabulary designed to facilitate interoperability between data catalogs published on the web. DCAT is intended to be used to publish information about datasets in data catalogs. It enables catalog publishers to increase discoverability and helps applications more easily utilize metadata from multiple catalogs in order to facilitate federated search.

**Analysis**
<br>
The DCAT standard is the basis for the Data.json effort, below.


## Project Open Data Metadata Schema

| **Current Status** | Rapidly developed but already in broad use |
| --- | --- |
| **Version Number** | 1.1 |
| **Key Contacts** |  |
| **Implementing Agencies** | Data.gov, several cities |
| **Documentation** | [http://project-open-data.github.io/catalog/](http://project-open-data.github.io/catalog/) |
| **Founding/Sponsoring Organizations** | Project Open Data, Data.gov |

**Background and Analysis**
<br>
Also known as “Slash Data”, this standard was developed by the Project Open Data project sponsored by the White House, and was originally known as Data.json. It is a standardized way to provide published summaries of government open data catalogs. The format was developed in conjunction with a Common Core Metadata standard. While it was developed fairly rapidly, its immediate use by the federal Data.gov portal and active encouragement of adoption by both federal and local data catalogs has driven rapid adoption. The standard is also supported by all of the most common data catalog software tools, including: CKAN, DKAN and Socrata.


## OGC Catalogue Standard (CSW)

| **Current Status** | Broadly implemented in commercial and open source software tools |
| --- | --- |
| **Version Number** | 3.0 |
| **Key Contacts** | OGC |
| **Implementing Agencies** |  |
| **Documentation** | [http://www.opengeospatial.org/standards/cat](http://www.opengeospatial.org/standards/cat) |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium (OGC) |

**Background and Analysis**
<br>
The OGC developed the Catalogue Service specifically to support open geospatial data portals and repositories. While originally limited to geospatial data, it has since been used more broadly for non-spatial data and is implemented in several software tools. However, it is possible that CSW will be displayed by the Project Open Data Metadata Schema in coming years.


## Socrata Open Data API (SODA)

| **Current Status** | Commercial company but broadly used |
| --- | --- |
| **Version Number** | 1.0? (documentation does not list a version number) |
| **Key Contacts** | Unknown |
| **Implementing Agencies** | New York, Chicago, Baltimore and several other large U.S. cities |
| **Documentation** | Getting Started:[http://dev.socrata.com/consumers/getting-started.html](http://dev.socrata.com/consumers/getting-started.html) |
| **Founding/Sponsoring Organizations** | Socrata |

**Background and Analysis**
<br>
The Socrata Open Data API (SODA) is not an open standard in the usual sense – it was developed by a commercial company and the API is not managed through a collaborative process. However, Socrata provides good documentation, and the fact that it is used in several large cities in the United States makes it relevant.

**Analysis**
<br>
Socrata’s data platform continues to grow in importance, and its API is a key source of open data for many cities.
