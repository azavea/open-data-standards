# OpenReferral
| Item | Description |
| --- | --- |
| **Current Status** | Initial drafts complete; implementation in a couple of cities. |
| **Version Number** | First draft of Human Services Data Specification |
| **Key Contacts** | Community Group: [https://groups.google.com/forum/#!forum/openreferral](https://groups.google.com/forum/#!forum/openreferral) |
| **Implementing Agencies** | Varies – usually a 211 system; regional United Way; or municipal/county human services agency |
| **Documentation** | Documentation: [https://www.openreferral.org/documentation/](https://www.openreferral.org/documentation/) |
| **Founding/Sponsoring Organizations** | Code for America, Purple Binder, [Ohana Project](http://ohanapi.org/) |
<br>

## Background

Open Referral is a data structure and API for human services information and referral (I&amp;R) services. It was initiated by the DC Community Resource Project and Code for America. Commercial partners have included both Purple Binder and the Ohana project. Pilot projects using the OpenReferral standard have been launched in Washington DC and San Mateo County, CA.

There are three main components to I&amp;R services: taxonomy, data schema and the service endpoints:

*   _Taxonomy_ – a system for categorizing services – is particularly challenging for human services I&amp;R systems. The AIRS taxonomy has been widely adopted but is proprietary and can only be used if a license fee is paid. [OpenEligibility.org](http://openeligibility.org), is an effort to develop a more open taxonomic standard licensed under Creative Commons.

*   _Data Schemas_ – The AIRS taxonomy has published an AIRS XSD schema document.A more open schema has been proposed by Google to support better search engine indexing and is published by the [W3C Civic Services](http://www.w3.org/wiki/WebSchemas/CivicServices) initiative at Schema.org. The latter is designed for municipal services but could be extended for human services applications. There is also the potential to harmonize the two data schemas.

*   _Service Endpoint_ – The Ohana API is perhaps the best example of an OpenReferral API endpoint.

## Analysis

The OpenReferral project consists of a stack of standards and specifications for sharing community resource data. The effort began as a project for San Mateo County by a Code for America team in 2013\. The team received a Knight Foundation grant in 2014 to support continued development of both the standard and the Ohana API.

## Additional Resources

*   Overview slides of OpenReferral: [https://t.co/jSICPg59jx](https://t.co/jSICPg59jx)
*   Ohana API: [https://github.com/codeforamerica/ohana-api](https://github.com/codeforamerica/ohana-api)
