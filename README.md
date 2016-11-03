# Open Data Standards {#open-data-standards}

Open Data Standards Report

Prepared by

******![](export/assets/image53png.png)**Description: azavea_RGB_72dpi_white_sm

990 Spring Garden Street, 5th Floor

Philadelphia, PA 19123

(215) 925-2600

[http://www.azavea.com](http://www.azavea.com)





# Overview

## Executive Summary
This document is an effort to outline the state of open data standards in several civic domains, as well as to suggest domains in which there is strong potential for developing new standards.

## Criteria for Selecting Standards
This report is organized into two sections, one for standards that have been released and are in use in at least a few cities, and a second section for potential new standards.

The criteria used to select the standards includes the following:

*   *Location-based* - We will focus on standards that have a location component

*   *Published standard* – There is documentation for the specification

*   *Machine-readable* - Based on JSON, CSV, XML or similar structure

*   *Adoption and used* - Adopted by at least one major US cities or heavily used by an aggregator of municipal data

Domain-Specific Standards

Akoma Ntoso

| **Current Status** | ![](export/assets/image18png.png) Limited adoption in the US but broader in some other countries |
| --- | --- |
| **Version Number** | 3.0 |
| **Key Contacts** | Prof. Monica Palmirani - email: monica.palmirani@unibo.it |
| **Implementing Agencies** | Courts and Parliaments |
| **Documentation** | [http://examples.akomantoso.org/categorical.html](http://examples.akomantoso.org/categorical.html) |
| **Founding/Sponsoring Organizations** | United Nations Department of Economic and Social Affairs |

**Background**

Parliaments and courts produce large quantities of documents during debates, committee briefs, journals, legislation life cycle and judgments.

Akoma Ntoso defines a set of machine readable data structures (in XML format) of parliamentary, legislative and judiciary documents. The main purposes of this standard are to define a common document format, model for document interchange, data schema, metadata schema and ontology, and schema for citation and cross referencing. This will increase the level of efficiency and accountability in parliamentary and judicial contexts.

**Analysis**

This data standard empowers the authors of these documents, the citizen analyzing the documents, those drafting and assembling the documents, and the civic hacker who builds solutions around the data. It allows the easy access, interpretation and dissemination of these documents quickly and easily.

Strategic goals include the creation of a common language for the interchange of parliamentary and legislative documents between institutes, facilitation of the long term storage and access of the documents, creation of common data and metadata models for information retrieval and the development of mechanisms for naming and linking documents. Additionally, the intent is for this standard to be both self-explanatory and extensible to allow for modifications within the framework for local customization.

**Additional Resources**

*   [http://examples.akomantoso.org/categorical.html](http://examples.akomantoso.org/categorical.html)

Common Alerting Protocol (CAP)

| **Current Status** | ![](export/assets/image19png.png)Broadly adopted, mature, used internationally |
| --- | --- |
| **Version Number** | 1.2 |
| **Key Contacts** | ipaws@dhs.gov |
| **Implementing Agencies** |  |
| **Documentation** | [http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.pdf](http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.pdf) |
| **Founding/Sponsoring Organizations** |  |

**Background**

The Common Alerting Protocol (CAP) is a digital format for exchanging emergency alerts that allows a consistent alert message to be disseminated simultaneously over many different communications systems. It was developed by FEMA in collaboration with local entities and is maintained by the Organization for the Advancement of Structured Information Standards (OASIS). OASIS has helped to extend the standard for international use.

**Additional Resources**

*   Adapting CAP for Emergency Alerting Systems - [http://www.eas-cap.org/ECIG-CAP-to-EAS_Implementation_Guide-V1-0.pdf](http://www.eas-cap.org/ECIG-CAP-to-EAS_Implementation_Guide-V1-0.pdf)

Election Markup Language (EML)

| **Current Status** | Published but very limited adoption |
| --- | --- |
| **Version Number** | v7.0 |
| **Key Contacts** | John Borras, Individual johnaborras@yahoo.co.uk |
| **Implementing Agencies** | Election commissions, e-voting companies |
| **Documentation** | [http://docs.oasis-open.org/election/eml/v7.0/eml-v7.0.html](http://docs.oasis-open.org/election/eml/v7.0/eml-v7.0.html) |
| **Founding/Sponsoring Organizations** | [OASIS](https://www.oasis-open.org/) |

**Background**

The Organization for the Advancement of Structured Information Standards (OASIS) created the Voter Services Technical Committee in 2001 to develop XML standards for election and voter services information. To establish the specifics of the XML schemas, the committee also developed a generic election process model based on the work by election.com’s CTO.

**Analysis**

Election Markup Language is designed to be multinational, so that it could be adopted globally. However, it has had little in the way of adoption in the United States. The vast diversity in the types of democratic systems globally may be a major obstacle to the widespread adoption of this system. The EML standard could be more widely adopted if e-voting, or internet voting, took off in a more substantial way.Since the EML standard covers the end-to-end process of voting, it could streamline and simplify the process of setting up such a system. The United Kingdom experimented with using the EML standard for an e-voting pilot and Belgium currently uses EML in its local government elections.

**Additional Resources**

*   [https://www.oasis-open.org/standards](https://www.oasis-open.org/standards)

General Transit Feed Specification (GTFS)

| **Current Status** | ![](export/assets/image16png.png)Adopted and broadly implemented |
| --- | --- |
| **Version Number** | Last update February 3, 2016 |
| **Key Contacts** | Bibiana McHugh - Portland TriMet IT Manager |
| **Implementing Agencies** | Public transportation agencies |
| **Documentation** | Docs: [https://developers.google.com/transit/gtfs/](https://developers.google.com/transit/gtfs/) |
| **Founding/Sponsoring Organizations** | Google and Portland TriMet |

**Background**

Until 2005, there was no mapping platform that allowed to trip planning in anything other than a car. That year, Bibiana McHugh, the IT Manager at Portland, Oregon’s TriMet contacted Google and found that Chris Harrelson, a software engineer, was working on that problem. TriMet worked closely with Google to format the agencies transit schedules to work with the Google Transit Trip Planner and it launched in December 2005\. In 2006, five more cities got on board and the project became branded Google Transit Feed Specification. Recently, the standard was renamed General Transit Feed Specification to acknowledge the agnostic aspect of the data’s purpose.

**Analysis**

GTFS has become the common language for transit. Over 700 agencies worldwide have adopted the GTFS standard for reporting public transit schedules. While mainly used for trip planning, GTFS data can also be used for data visualization and maps, measures of accessibility and timetable creation.

**Additional Resources**

*   Transit Land - reference and site for transit agencies to connect with developers : [https://transit.land/](https://transit.land/)

*   Transit Feeds - repositories built on Github: [http://transitfeeds.com/](http://transitfeeds.com/)

GTFS-RT (Real-Time)

| **Current Status** | ![](export/assets/image17png.png)Adopted |
| --- | --- |
| **Version Number** | Last updated July 29, 2015 |
| **Key Contacts** |  |
| **Implementing Agencies** | Public transit agencies |
| **Documentation** | Docs: [https://developers.google.com/transit/gtfs-realtime/](https://developers.google.com/transit/gtfs-realtime/) |
| **Founding/Sponsoring Organizations** | Google, Live Transit Updates agencies |

**Background**

Introduced in 2011, the specification was created through a partnership of Google’s Live Transit Updates agencies, transit developers and Google.

**Analysis**

GTFS-RT is an extension of GTFS (and essentially, a new standard) to allow public transit agencies to submit real-time location and status information about their fleets.It is currently implemented by about a dozen transit agencies worldwide.One obstacle to adoption may be the initial investment of fleet tracking systems as well as the wireless bandwidth required to communicate positions of every vehicle in a large fleet.Another factor may be the NextBus Company, which installs and maintains an enterprise GPS system for many public transit agencies.There have also been active patent disputes with ArrivalStar, a non-practicing entity (aka “patent troll”) that had been bringing patent suits against transit agencies.ArrivalStar agreed to stop pursuing transit agencies in late 2013, and this has cleared the way for agencies to release more tools that would leverage GTFS-RT.

**Additional Resources**

*   Directory of transit feeds: [http://transitfeeds.com/search?q=gtfsrt](http://transitfeeds.com/search?q=gtfsrt)

Google Civic Information API

| **Current Status** | ![](export/assets/image35png.png) Relatively new, but well supported and documented |
| --- | --- |
| **Version Number** | 2.0 |
| **Key Contacts** |  |
| **Implementing Agencies** | N/A (Google assembles data from several sources) |
| **Documentation** | [https://developers.google.com/civic-information/docs/v2/](https://developers.google.com/civic-information/docs/v2/) |
| **Founding/Sponsoring Organizations** | Google, Pew Charitable Trusts (for VIP data) |

**Background**

The Google Civic Information API was originally released in private beta as a unified source for elections, polling places and other data from the Voting Information Project (see below). In fall 2013, it was extended to include the ability to look up elected office holders at the local, state and national levels. The API currently supports:

*   Elections (based in VIP)

*   Representatives

*   Divisions

**Analysis**

While not, strictly speaking, an open standard, the Google Civic Information aggregates several data sources, including the Voting Information Project (VIP), Cicero and others. It implements the OCD Identifier standard.

Additional Resources

*   API Forum: [https://developers.google.com/civic-information/docs/ci_forum](https://developers.google.com/civic-information/docs/ci_forum)

*   Using the API: [https://developers.google.com/civic-information/docs/using_api](https://developers.google.com/civic-information/docs/using_api)

House Facts

| **Current Status** | ![](export/assets/image36png.png) Still evolving, limited adoption |
| --- | --- |
| **Version Number** | 0.2.3 |
| **Key Contacts** | [https://sites.google.com/site/housefactsdatastandard/home/contributors](https://sites.google.com/site/housefactsdatastandard/home/contributors) |
| **Implementing Agencies** | San Francisco, Las Vegas, Bloomington, Kansas City, Gary IN, Olathe KS (these have committed to implementing the standard, but only San Francisco and Kansas City were confirmed to have published using the standard) |
| **Documentation** | [https://sites.google.com/site/housefactsdatastandard/home](https://sites.google.com/site/housefactsdatastandard/home) |
| **Founding/Sponsoring Organizations** | The Civic Engine, Accela, Code for America, Civic Insight and Socrata. |

**Background**

The House Facts data standard provides a common format for reporting government data on the operation, safety, and performance of residential buildings. Reported information may include specifics regarding building structure, function, habitability safety and environmental performance. The initial version of the standard is focused on housing inspections.

**Analysis**

This data standard is intended to have substantial benefits in the civic sphere including: the full disclosure of property regulatory history of property prior to rent or purchase, search of data by property owner or property address, potential analysis by government, civic or academic agencies for patterns in inspection results, creation of city benchmarking for housing health and safety and most importantly general encouragement of improved property maintenance for homeowners.

**Additional Resources**

*   San Francisco: [https://data.sfgov.org/Housing-and-Buildings/Housing-Code-Violations-San-Francisco-CA/739v-w6y3](https://data.sfgov.org/Housing-and-Buildings/Housing-Code-Violations-San-Francisco-CA/739v-w6y3)

*   Kansas City: [https://odn.demo.socrata.com/Housing/Housefacts-Kansas-City/acmj-4g7g](https://odn.demo.socrata.com/Housing/Housefacts-Kansas-City/acmj-4g7g)

Local Inspector Value Entry Specification (LIVES)

| **Current Status** | ![](export/assets/image37png.png) Published and adopted by a few large cities |
| --- | --- |
| **Version Number** | 2.0 |
| **Key Contacts** | https://www.codeforamerica.org/our-work/data-formats/LIVES/ |
| **Implementing Agencies** | Washington DC, San Francisco, New York |
| **Documentation** | [http://www.yelp.com/healthscores](http://www.yelp.com/healthscores) |
| **Founding/Sponsoring Organizations** | City of San Francisco, YELP, Code for America, City of New York |

**Background**

Restaurant inspections performed by health agencies usually result in unstructured data, making it difficult for these reports to be interpreted by the public. They were often released in PDF format with no standard structure. Additionally, substantial variations in the ratings and evaluation methods made it impossible to compare results across municipalities. In 2012, Yelp partnered with Code for America and the City of San Francisco to develop an open data standard which allows state and municipal health agencies to collect, format and publish restaurant inspection information on Yelp. The City of New York joined the effort at an early stage as well.

**Analysis**

This structure was originally developed to align with Yelp’s platform and provide consumers with quick information about restaurant cleanliness but it also encouraged innovative uses with this data by the public resulting from release in a standardized data format directly to the public. One key element is a guide that allows agencies to map qualitative information such as Good, Poor, Fair, A+, B-, etc. to a numeric system. Additionally, this standardization of collection made it possible to easily distribute this data and compare across regions. Now that a standard structure has been introduced, city health agencies often elect to release this data in API format such as Washington, DC.

The wide publication of this data has resulted in closer attention to restaurant cleanliness which studies have found led to 13% decrease in hospitalization due to foodborne illness in the City of Los Angeles. [http://kuafu.umd.edu/~ginger/research/JEH-final.pdf](http://kuafu.umd.edu/~ginger/research/JEH-final.pdf)

One impediment to adoption has been the differing standards for performing health inspections. Philadelphia, for example, has refused to adopt the standard and publish their inspection data on the basis of differing methodologies.

**Additional Resources**

*   DC: [http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e](http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e)

San Francisco:[https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb)

Open311

| **Current Status** | ![](export/assets/image38png.png) Wide Adoption |
| --- | --- |
| **Version Number** | GeoReport v2, Inquiry v2 (draft) |
| **Key Contacts** | Philip Ashlock, phil@civicagency.org |
| **Implementing Agencies** | City Agencies that collect 311 (or equivalent) data |
| **Documentation** | [http://www.open311.org/2009/09/open311-is-a-specification-for-an-open-platform/](http://www.open311.org/2009/09/open311-is-a-specification-for-an-open-platform/) |
| **Founding/Sponsoring Organizations** | Open Plans |

**Background**

A 311 phone number allows for non-emergency municipal service issue reporting for situations such as street debris, potholes and nonworking streetlights as well as to obtain municipal information. OpenPlans, a nonprofit technology organization featuring digital solutions for civic problems originally developed the Open311 interoperable system that functions to coordinate standardized, open-access, read/write model for citizens to report on emergency issues. This standardized protocol allows for location based collaboration issue-tracking. A free API allows access to existing 311 services.

**Analysis**

The Open311 standard is one of the earliest and best established open data standards. It is in wide use across the United States. Some of the most prominent platforms that have adopted this system are FixMyStreet in the UK and SeeClickFix in the US. This standard is utilized by the following cities (among others): Chicago, IL; Toronto, ON; San Francisco, CA; Washington, DC; Boston, MA; New York City, NY. As 311 becomes a more commonplace service provided by municipalities, the further adoption and improvement of this standard is anticipated.

**Additional Resources**

*   Additional documentation

    *   [http://wiki.open311.org/GeoReport_v2/Resources](http://wiki.open311.org/GeoReport_v2/Resources)

    *   [http://wiki.open311.org/API](http://wiki.open311.org/API)

*   Status of Open311 systems in the US: [http://open311status.herokuapp.com/](http://open311status.herokuapp.com/)

Open Civic Data

| **Current Status** | ![](export/assets/image39png.png)In Development; rapidly maturing; broad adoption in software but limited publishing by local and state legislatures |
| --- | --- |
| **Version Number** | Last updated 2015 |
| **Key Contacts** | James Turk, Sunlight Foundation james.p.turk@gmail.com |
| **Implementing Agencies** | Government agencies, election commissions, government information services, [Google Civic Information API](https://developers.google.com/civic-information/), Popolo Project, Granicus, Cicero |
| **Documentation** | Open Civic Data API:[http://docs.opencivicdata.org/en/latest/api/index.html](http://docs.opencivicdata.org/en/latest/api/index.html) |
| **Founding/Sponsoring Organizations** | Google, OpenNorth, Sunlight Foundation |

**Background**

The Open Civic Data project is a collaborative effort to define schemas and provide tools for collecting and disseminating information on government organizations, officials, legislation and events. Building off the work of the OpenStates project, the Sunlight Foundation sought to create a standard that would enable users to more easily digest election and government information. It is not one standard but rather six that cover several aspects of the democratic process. The most active implementations have been related to OCD IDs (divisions).

**Analysis**

The Open Civic Data project seeks to define a schema for the following:

_Division_ - A political geography such as a state, county or congressional district.

[http://docs.opencivicdata.org/en/latest/proposals/0002.html](http://docs.opencivicdata.org/en/latest/proposals/0002.html)

_Jurisdictions_ - A governing body that exists within a division, such as the PA House of Representatives.

[http://docs.opencivicdata.org/en/latest/proposals/0003.html](http://docs.opencivicdata.org/en/latest/proposals/0003.html)

_Civic Events_ - A legislative event, such as a meeting or hearing.

[http://docs.opencivicdata.org/en/latest/proposals/0004.html](http://docs.opencivicdata.org/en/latest/proposals/0004.html)

_Persons, Organizations, Posts and Memberships_ - A politician or government official, a group of people (such as a city council, state senate or committee). The Popolo specification (see above) is the basis for this OCD component. [http://docs.opencivicdata.org/en/latest/proposals/0005.html](http://docs.opencivicdata.org/en/latest/proposals/0005.html)

_Bills_ - A legislative document and its history, may technically be a resolution, appointment, or contract.

[http://docs.opencivicdata.org/en/latest/proposals/0006.html](http://docs.opencivicdata.org/en/latest/proposals/0006.html)

_Votes_ - The record of a vote taken on a motion, such as a confirmation or passage of a bill.

[http://docs.opencivicdata.org/en/latest/proposals/0007.html](http://docs.opencivicdata.org/en/latest/proposals/0007.html)

**Additional Resources**

*   GitHub Repository: [https://github.com/opencivicdata](https://github.com/opencivicdata)

*   Pupa – software project for scraping OCD data: [https://github.com/opencivicdata/pupa](https://github.com/opencivicdata/pupa)

*   OCD ID Lookup Tool for Canada: [http://opennorth.github.io/ocd-id-viewer/](http://opennorth.github.io/ocd-id-viewer/)

Master List of OCD IDs: [https://github.com/opencivicdata/ocd-division-ids/tree/master/identifiers](https://github.com/opencivicdata/ocd-division-ids/tree/master/identifiers)

Open Contracting Data Standard (OCDS)

| **Current Status** | ![](export/assets/image40png.png) Adopted internationally; well-funding; rapidly maturing |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | Twitter: [@ocdata](https://twitter.com/ocdata) |
| **Implementing Agencies** | San Mateo County, UK.gov |
| **Documentation** | [http://standard.open-contracting.org/](http://standard.open-contracting.org/) |
| **Founding/Sponsoring Organizations** | Open Contracting Partnership, World Wide Web Foundation |

**Background**

Governments around the world spend an estimated US $9.5 trillion every year through vendor contracts, but information about the contracting process is generally not made public and, even when public, it is scattered across multiple systems and websites. Public contracts are particularly vulnerable to waste, mismanagement, and corruption. This new standard is intended to give stakeholders access to a unified picture of contracting data and support more effective understanding of how public money is spent on contracts.

**Analysis**

This is a well-funded effort to improve transparency in government contracting. The standard is clearly aimed at international usage and has the potential for use across all levels of governments. The directory of agencies shows almost 30 governments now publishing using the standard, though most are international.

**Additional Resources**

*   OCDS GitHub - [https://github.com/open-contracting/standard](https://github.com/open-contracting/standard)

*   Directory of contracting data publishers - [http://ocds.open-contracting.org/opendatacomparison](http://ocds.open-contracting.org/opendatacomparison)

*   Software tools and resources: [http://standard.open-contracting.org/latest/en/support/tools/](http://standard.open-contracting.org/latest/en/support/tools/)

OpenElections

| **Current Status** | ![](export/assets/image41png.png)In Progress |
| --- | --- |
| **Version Number** | v1 |
| **Key Contacts** | Serdar Tumgoren, Project Lead [https://twitter.com/zstumgoren](https://twitter.com/zstumgoren) |
| **Implementing Agencies** | State and local election commissions, Journalists, civic hackers |
| **Documentation** | Documentation: [http://docs.openelections.net/](http://docs.openelections.net/) |
| **Founding/Sponsoring Organizations** | John S. and James L. Knight Foundation’s Knight News Challenge |

**Background**

Funded by the Knight News Challenge in 2012, the goal of OpenElections is to create a free, standardized set of election results data for all federal and statewide offices in the United States.

**Analysis**

Currently, election results data can be hard to find -- especially for historical elections. The OpenElections platform aims to make a standard that journalists and civic developers can easily access for stories and web applications. There has been much progress around documentation of the standard, and assembling lists of election events. The major remaining challenge is the effort to crowdsource the actual election results. OpenElections maintains status information for each state on the homepage for the project. Ideally, election commissions that report results would do so in the OpenElections standard or even submit directly to OpenElections.

**Additional Resources**

*   Github repository: [https://github.com/openelections](https://github.com/openelections)

OpenReferral

| **Current Status** | ![](export/assets/image42png.png)Initial drafts complete; implementation in a couple of cities. |
| --- | --- |
| **Version Number** | First draft of Human Services Data Specification |
| **Key Contacts** | Community Group:[https://groups.google.com/forum/#!forum/openreferral](https://groups.google.com/forum/#!forum/openreferral) |
| **Implementing Agencies** | Varies – usually a 211 system; regional United Way; or municipal/county human services agency |
| **Documentation** | Documentation: [https://www.openreferral.org/documentation/](https://www.openreferral.org/documentation/) |
| **Founding/Sponsoring Organizations** | Code for America, Purple Binder, [Ohana Project](http://ohanapi.org/) |

**Background**

Open Referral is a data structure and API for human services information and referral (I&amp;R) services. It was initiated by the DC Community Resource Project and Code for America. Commercial partners have included both Purple Binder and the Ohana project. Pilot projects using the OpenReferral standard have been launched in Washington DC and San Mateo County, CA.

There are three main components to I&amp;R services: taxonomy, data schema and the service endpoints:

*   _Taxonomy_ – a system for categorizing services – is particularly challenging for human services I&amp;R systems. The AIRS taxonomy has been widely adopted but is proprietary and can only be used if a license fee is paid. [OpenEligibility.org](http://openeligibility.org), is an effort to develop a more open taxonomic standard licensed under Creative Commons.

*   _Data Schemas_ – The AIRS taxonomy has published an AIRS XSD schema document.A more open schema has been proposed by Google to support better search engine indexing and is published by the [W3C Civic Services](http://www.w3.org/wiki/WebSchemas/CivicServices) initiative at Schema.org. The latter is designed for municipal services but could be extended for human services applications. There is also the potential to harmonize the two data schemas.

*   _Service Endpoint_ – The Ohana API is perhaps the best example of an OpenReferral API endpoint.

**Analysis**

The OpenReferral project consists of a stack of standards and specifications for sharing community resource data. The effort began as a project for San Mateo County by a Code for America team in 2013\. The team received a Knight Foundation grant in 2014 to support continued development of both the standard and the Ohana API.

**Additional Resources**

*   Overview slides of OpenReferral: [https://t.co/jSICPg59jx](https://t.co/jSICPg59jx)

*   Ohana API: [https://github.com/codeforamerica/ohana-api](https://github.com/codeforamerica/ohana-api)

OpenTrails

| **Current Status** | ![](export/assets/image32png.png) Recently developed |
| --- | --- |
| **Version Number** | 1.1 |
| **Key Contacts** | Jack Madans: jack@codeforamerica.org |
| **Implementing Agencies** | City of Portland, Oregon, Northeast Ohio (Cuyahoga Valley) |
| **Documentation** | Specification:[https://www.codeforamerica.org/specifications/trails/spec.html](https://www.codeforamerica.org/specifications/trails/spec.html) |
| **Founding/Sponsoring Organizations** | City of Portland, Code for America, Esri Portland R&amp;D Center, Strava, All Trails, National Recreation and Parks Association, GreenInfo Network, Trust for Public Lands, Intertwine Alliance, Trailhead Labs |

**Background**

The OpenTrails specification was launched in Northeast Ohio through Code for America. It was later introduced to the Portland, Oregon region at the 2014 National Day of Civic Hacking. Several commercial partners have since helped to introduce to the standard to other locations. The standard covers five data types:

*   Trail Segments (GeoJSON)

*   Trailheads (GeoJSON)

*   Named Trails (CSV)

*   Stewards ( CSV)

*   Areas (optional) – parks and preserves

**Analysis**

While only introduced in spring 2014, the combination of active participation by several commercial firms, a few government agencies and nonprofit organizations suggests that this standard has a strong future.

**Additional Resources**

*   Data Community Website:[http://www.opentraildata.org/](http://www.opentraildata.org/)

*   OpnTrails Github Repo: [https://github.com/opentraildata](https://github.com/opentraildata)

*   August 2014 Webinar Series:[http://www.codeforamerica.org/specifications/trails/](http://www.codeforamerica.org/specifications/trails/)

Popolo

| **Current Status** | ![](export/assets/image33png.png)Adopted by OCD but not yet used by government agencies |
| --- | --- |
| **Version Number** | 1.0.1 |
| **Key Contacts** | James McKinney james@opennorth.ca |
| **Implementing Agencies** | Governments, open government organizations |
| **Documentation** | Specification:[http://popoloproject.com/specs/](http://popoloproject.com/specs/) |
| **Founding/Sponsoring Organizations** | OpenNorth |

**Background**

James McKinney, civic developer, co-founder of OpenNorth, and part of the OpenGovernment.org team, conceived Popolo as a way to create an open government data scheme that could easily be re-used by other civic developers. The project was created and launched in 2013\. While it is a standalone standard, in 2014, Popolo was adopted as the basis for the Open Civic Data (OCD) People, Organization and Membership component.

**Analysis**

Popolo is an open government specification that seeks to set a standard naming scheme for the basic of any government monitoring website. The ultimate goal of the project is to make it easier and quicker for civic developers to create government transparency and civic engagement websites, by offering them re-usable, well-documented open-source code. Several open source programming packages (python, Node.js, Ruby on Rails) have been created that use the Popolo standard.

**Additional Resources**

Github repo:[https://github.com/opennorth/popolo-spec](https://github.com/opennorth/popolo-spec)

Voting Information Project (VIP)

| **Current Status** | ![](export/assets/image34png.png)In Progress, Adopted by 20 states in 2010 election and by most states in 2012 election |
| --- | --- |
| **Version Number** |  |
| **Key Contacts** | Jared Marcotte, Pew Charitable Trusts, jmarcotte@pewtrusts.org |
| **Implementing Agencies** | Primarily state with some local election commissions |
| **Documentation** | [https://www.votinginfoproject.org/](https://www.votinginfoproject.org/) |
| **Founding/Sponsoring Organizations** | Pew Charitable Trusts, Google |

**Background**

The idea for the Voting Information Project (VIP) came out of the election analysis report, “Being Online Is Not Enough”, produced by the Pew Charitable Trusts in 2008\. One of the report&#039;s major findings was that providing on-demand access about voting information helps governments save money by reducing phone calls and visits by voters. Following the report, as a joint-effort between the Pew Charitable Trusts and Google, the VIP partnered with 9 states to provide pertinent voting information to citizens. In the 2010 election cycle, 20 states began contributing data feeds to the project.

**Analysis**

The goal of the VIP is to engage voters and drive voter turnout by ultimately making voting information more accessible. In short, the goals of the VIP, such as to answer common voting questions like “Where is my polling place?” and “What’s on my ballot?” are very important, however the obstacles are very challenging. The main challenge is participation. States must voluntarily contribute voting data to the program through a machine readable format. Thus, getting buy-in from state election commissions is extremely important. In the 2012 election cycle, most states participated by contributing at least some of the data gathered by the VIP project.The VIP project itself does not disseminate information; it relies on developers to build applications to make the data easy to access.In addition, the Google Civic Information API has adopted VIP information as a way to connect voters with their polling place and other VIP information. Several interesting projects have come out of the VIP, and can be found [here](https://www.votinginfoproject.org/projects). They include a mobile application to estimate wait time at a polling place.

**Additional Resources**

*   Election data feeds: [https://votinginfoproject.org/feeds](https://votinginfoproject.org/feeds)

*   Github repo: [https://github.com/votinginfoproject](https://github.com/votinginfoproject)

*   Google Civic Information API: [https://developers.google.com/civic-information/](https://developers.google.com/civic-information/)

Generic Standards – Data Catalogs

CKAN API

| **Current Status** | ![](export/assets/image25png.png)In use by many organizations, well maintained, good documentation |
| --- | --- |
| **Version Number** | v. 3 (CKAN version 2.2) |
| **Key Contacts** | CKAN mailing list ([https://groups.google.com/forum/#!forum/ckan-global-user-group](https://groups.google.com/forum/#!forum/ckan-global-user-group)) |
| **Implementing Agencies** | Many agencies, global |
| **Documentation** | API: [http://docs.ckan.org/en/latest/api/index.html](http://docs.ckan.org/en/latest/api/index.html) |
| **Founding/Sponsoring Organizations** | Open Knowledge Foundation |

**Background**

The CKAN data catalog has been developed over the course of several years by the Open Knowledge Foundation. It is the leading open source data catalog and supports many key features. The CKAN API supports all of the key features of CKAN, including retrieving lists of data sets, metadata about each data set, search results, add/update/delete data sets and an activity log.

**Analysis**

The open source CKAN application is well established with many users, including Data.gov.

Data Catalog Vocabulary (DCAT)

| **Current Status** | ![](export/assets/image26png.png)Published by W3C as recommendation, but not yet an adopted standard |
| --- | --- |
| **Version Number** | W3C recommendation (Jan. 2014) |
| **Key Contacts** | Mailing list (subscribe at [http://www.w3.org/TR/vocab-dcat/](http://www.w3.org/TR/vocab-dcat/)) |
| **Implementing Agencies** | Unknown |
| **Documentation** | [http://www.w3.org/TR/vocab-dcat/](http://www.w3.org/TR/vocab-dcat/) |
| **Founding/Sponsoring Organizations** | W3C |

**Background**

DCAT is an RDF vocabulary designed to facilitate interoperability between data catalogs published on the web. DCAT is intended to be used to publish information about datasets in data catalogs. It enables catalog publishers to increase discoverability and helps applications more easily utilize metadata from multiple catalogs in order to facilitate federated search.

**Analysis**

The DCAT standard is the basis for the Data.json effort, below.

Project Open Data Metadata Schema

| **Current Status** | ![](export/assets/image27png.png)Rapidly developed but already in broad use |
| --- | --- |
| **Version Number** | 1.1 |
| **Key Contacts** |  |
| **Implementing Agencies** | Data.gov, several cities |
| **Documentation** | [http://project-open-data.github.io/catalog/](http://project-open-data.github.io/catalog/) |
| **Founding/Sponsoring Organizations** | Project Open Data, Data.gov |

**Background and Analysis**

Also known as “Slash Data”, this standard was developed by the Project Open Data project sponsored by the White House, and was originally known as Data.json. It is a standardized way to provide published summaries of government open data catalogs. The format was developed in conjunction with a Common Core Metadata standard. While it was developed fairly rapidly, its immediate use by the federal Data.gov portal and active encouragement of adoption by both federal and local data catalogs has driven rapid adoption. The standard is also supported by all of the most common data catalog software tools, including: CKAN, DKAN and Socrata.

OGC Catalogue Standard (CSW)

| **Current Status** | ![](export/assets/image28png.png)Broadly implemented in commercial and open source software tools |
| --- | --- |
| **Version Number** | 3.0 |
| **Key Contacts** | OGC |
| **Implementing Agencies** |  |
| **Documentation** | [http://www.opengeospatial.org/standards/cat](http://www.opengeospatial.org/standards/cat) |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium (OGC) |

**Background and Analysis**

The OGC developed the Catalogue Service specifically to support open geospatial data portals and repositories. While originally limited to geospatial data, it has since been used more broadly for non-spatial data and is implemented in several software tools. However, it is possible that CSW will be displayed by the Project Open Data Metadata Schema in coming years.

Socrata Open Data API (SODA)

| **Current Status** | ![](export/assets/image29png.png)Commercial company but broadly used |
| --- | --- |
| **Version Number** | 1.0? (documentation does not list a version number) |
| **Key Contacts** | Unknown |
| **Implementing Agencies** | New York, Chicago, Baltimore and several other large U.S. cities |
| **Documentation** | Getting Started:[http://dev.socrata.com/consumers/getting-started.html](http://dev.socrata.com/consumers/getting-started.html) |
| **Founding/Sponsoring Organizations** | Socrata |

**Background and Analysis**

The Socrata Open Data API (SODA) is not an open standard in the usual sense – it was developed by a commercial company and the API is not managed through a collaborative process. However, Socrata provides good documentation, and the fact that it is used in several large cities in the United States makes it relevant.

**Analysis**

Socrata’s data platform continues to grow in importance, and its API is a key source of open data for many cities.

Generic Standards – Geospatial Data

KML

| **Current Status** | ![](export/assets/image30png.png) Open Standard by Open Geospatial Consortium; broad use |
| --- | --- |
| **Version Number** | 2.3 |
| **Key Contacts** | KML 2.3 Standards Working Group [http://www.opengeospatial.org/projects/groups/kmlswg](http://www.opengeospatial.org/projects/groups/kmlswg) |
| **Implementing Agencies** | Various – KML support is included in Google products as well as several open source and commercial products. Open source libraries have also been released to support desktop software integration. |
| **Documentation** | [http://www.opengeospatial.org/standards/kml/](http://www.opengeospatial.org/standards/kml/) |
| **Founding/Sponsoring Organizations** | Created by [Keyhole, Inc](http://en.wikipedia.org/wiki/Keyhole,_Inc), which was acquired by [Google](http://en.wikipedia.org/wiki/Google) in 2004\. Later submitted to Open Geospatial Consortium, which now oversees the standard. |

**Background**

Keyhole Markup Language (KML) is an XML notation for expressing geographic annotation and visualization. This notation can be viewed within web-based and two-dimensional maps and three-dimensional Earth browsers. KML was originally named Keyhole Earthviewer and developed for use with Google Earth software. It was created by Keyhole, Inc, which was acquired by Google in 2004\. In 2008, the Open Geospatial Consortium adopted KML as an international standard. While Google Earth was the first program able to view and edit KML files, it was later supported in several mapping software tools.

**Analysis**

KML is widely used for use of sharing 2D and 3D geospatial data in xml format on the web. It is well suited for sharing styled geographic data but attribute data (tabular information conventionally attached to a geometry feature) is not well supported. Metadata is also not supported. The use of KML as an interchange standard is declining. Further, a new version of the standard that would be harmonized with other OGC standards was never released and no new versions have been released since it was submitted by the OGC.

*   KML support in GDAL/OGR - [http://www.gdal.org/drv_libkml.html](http://www.gdal.org/drv_libkml.html)

*   Google LibKML - [https://github.com/google/libkml](https://github.com/google/libkml)

*   LibKML resources - [https://code.google.com/p/libkml/w/list](https://code.google.com/p/libkml/w/list)

GeoJSON

| **Current Status** | ![](export/assets/image31png.png)Wide Adoption in web apps and APIs |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | [http://lists.geojson.org/listinfo.cgi/geojson-geojson.org](http://lists.geojson.org/listinfo.cgi/geojson-geojson.org) |
| **Implementing Agencies** | Organizations building Web Mapping Applications |
| **Documentation** | [http://geojson.org/geojson-spec.html](http://geojson.org/geojson-spec.html) |
| **Founding/Sponsoring Organizations** | OpenGeo |

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

Shapefile

| **Current Status** | ![](export/assets/image20png.png)Wide Adoption |
| --- | --- |
| **Version Number** | No version numbers – last update was July 1998 |
| **Key Contacts** | Esri |
| **Implementing Agencies** | Companies, Education Organizations, Government Agencies that create, store and manipulate geospatial data |
| **Documentation** | [http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) |
| **Founding/Sponsoring Organizations** | Esri |

**Background**

The shapefile was originally developed by the Geographic Information Systems software company, Esri, for the storage of geospatial data. Though not technically an open, community standard, Esri published the specification in the 1990’s and it is has become an extremely common data format for the storage and distribution of spatial data.

A shapefile is a file format used to store the geometric location and attribute information of geographic features. Geographic features in a shapefile can be represented by points, lines, or polygons (areas).

The shapefile is in fact a grouping of several files formatted to represent different aspects of geodata:

_.shp_— shape format; the feature geometry itself.

_.shx_— shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly.

_.dbf_— attribute format; columnar attributes for each shape, in dBase IV format.

.prj — projection format; an optional file; coordinate system and projection information

.lyr — layer format; an option file; contains display specifications for ArcGIS software including

color, labeling, etc.

**Analysis**

Because shapefiles are stored as multiple files, they are not the simplest way to store and transfer data; however they do a successful job in storing additional data about geospatial dataset such as attributes, projection, zymology and metadata.Newer data formats such as GeoJSON and KML allow for the easier transfer and quick visualization of data, especially on the web, but key attributes are not as successfully stored. For simple point features, tabular CSV (comma separated values) is popular for the distribution of data with coordinates, though no metadata or embedded projection is possible. There are limitations of size (1 gb of data) and field length which is limiting when storing complex or large datasets.

For web mapping, many online tools have adapted to the structure of the shapefile and enabled the ability to upload a zipped shapefile for web visualization.

**Additional Resources**

*   [http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//005600000002000000.htm)

*   [http://shapelib.maptools.org/](http://shapelib.maptools.org/)

*   [http://wiki.openstreetmap.org/wiki/Shapefiles](http://wiki.openstreetmap.org/wiki/Shapefiles)

*   [https://code.google.com/p/pyshp/](https://code.google.com/p/pyshp/)

*   [http://www.gdal.org/drv_shapefile.html](http://www.gdal.org/drv_shapefile.html)

*   [http://mapserver.org/input/vector/shapefiles.html](http://mapserver.org/input/vector/shapefiles.html)

OGC GeoPackage

| **Current Status** | ![](export/assets/image21png.png)Adopted in early 2014 and beginning to be integrated into software tools; not yet widely used but significant demand for mobile applications |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | info@opengeospatial.org |
| **Implementing Agencies** | Organizations using Open GeoSpatial Data Formats |
| **Documentation** | [http://www.opengeospatial.org/standards/geopackage](http://www.opengeospatial.org/standards/geopackage) |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium |

**Background**

This standard was developed as a successor to the popular shapefile format. This OGC Encoding Standard defines GeoPackages for exchange and GeoPackage SQLite Extensions for direct use of vector geospatial features and / or tile matrix sets of earth images and raster maps at various scales.

This direct use allows support by an environment, like an API, and means the user can access and edit data in a native storage format without intermediate format transactions. Identical requests from different client applications produce identical access and edit results and maintain data integrity.

GeoPackages are compatible with all computing environments, but are especially useful in areas with limited connectivity and bandwidth on mobile devices.

**Analysis**

Unlike shapefiles, this spatial data format supports both vector and raster data formats and can support relational data models as well as multi-user and disconnected editing use cases.The standard was only recently finalized but is already supported in both commercial and open source software.It responds to a significant gap in mobile data collection and the poor match between existing data structures and disconnected editing use cases.

**Additional Resources**

*   Github Issue Tracking: [https://github.com/opengis/geopackage/issues](https://github.com/opengis/geopackage/issues)

*   Submit Change Request: [https://portal.opengeospatial.org/public_ogc/change_request.php](https://portal.opengeospatial.org/public_ogc/change_request.php)

*   [http://www.geopackage.org/](http://www.geopackage.org/)

*   [https://bitbucket.org/luciad/libgpkg](https://bitbucket.org/luciad/libgpkg)

*   [http://demo.luciad.com/GeoPackage/](http://demo.luciad.com/GeoPackage/)

*   [http://www.gdal.org/drv_geopackage.html](http://www.gdal.org/drv_geopackage.html)

OGC WMS/WFS/WCS/WMTS/ WPS

| **Current Status** | ![](export/assets/image22png.png)Wide Adoption |
| --- | --- |
| **Version Number** | Varies |
| **Key Contacts** | info@opengeospatial.org |
| **Implementing Agencies** | Organizations using Open GeoSpatial Data Formats |
| **Documentation** | See Below |
| **Founding/Sponsoring Organizations** | Open Geospatial Consortium |

**Background**

_Web Map Service (WMS) 1.3_

The geographic layers and area of interest to be processed are defined by the WMS request. One or more geo-referenced images are returned and can be displayed in a browser application.

[http://www.opengeospatial.org/standards/wms](http://www.opengeospatial.org/standards/wms)

_Web Feature Service (WFS) 2.0_

Instead of sharing geographic information at the file level using a File Transfer Protocol (FTP), the WFS provides direct access to geographic information at the feature and feature property level.

[http://www.opengeospatial.org/standards/wfs](http://www.opengeospatial.org/standards/wfs)

_Web Coverage Service (WCS) 2.0_

Web Coverage Service (WCS) coverage data is multi-dimensional and can be accessed over the internet.

[http://www.opengeospatial.org/standards/wcs](http://www.opengeospatial.org/standards/wcs)

_Web Map Tile Service (WMTS) 1.0_

The Web Map Tile Service (WMTS) offers scalable, high-performance services for distribution of maps on the web.

[http://www.opengeospatial.org/standards/wmts](http://www.opengeospatial.org/standards/wmts)

_Web Processing Service (WPS) 1.0_

Rules for stadardization of inputs and outputs for geospatial processing services are provided by the Web Processing Service (WPS).

[http://www.opengeospatial.org/standards/wps](http://www.opengeospatial.org/standards/wps)

**Analysis**

The OGC publishes a broad range of standards, most of which are not widely adopted. However, this core set of web map publishing standards is in broad use in both open source and commercial software tools and continues to provide value and have active communities of people using and improving upon them.

Areas of Significant Opportunity

The following are topics areas where we believe there is both significant demand and public good that would arise if open data standards were to be developed.

Built Environment

Building Energy Usage

| **Current Status** | ![](export/assets/image24png.png)![](export/assets/image55png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.png Formal, Not Open, Under Development. |
| --- | --- |
| **Potential Implementing Agencies** | Building owners and managers |
| **Potential Founding/Sponsoring Organizations** | Federal Office of Energy Efficiency &amp; Renewable Energy (Energy.gov) |

**Analysis -- Future Potential and Adoption**

Building energy usage is an area of significant interest in many cities. Several cities have now passed building energy benchmarking ordinances and are beginning to report energy usage to the EPA through the Portfolio Manager application. While some cities are beginning to publish the annual energy benchmarking data they are collecting from building owners, there are not yet any standards for doing so. The House Facts standard (see above) has suggested that this may be part of a future version, but it is not yet part of the standard. The EPA is also working on a standard and the development process was launched in late 2013\. The Building Energy Data Exchange Specification (BEDES) is designed to support analysis of the measured energy performance of commercial, multifamily and residential buildings, by providing a common data format, definitions, and an exchange protocol for building characteristics, efficiency measures, and energy use.

An open standard could include discourse on the usefulness of this data standard, not just in use by the Federal government but by local government agencies and other organizations.

**Additional Resources**

*   [http://energy.gov/eere/buildings/building-energy-data-exchange-specification-bedes](http://energy.gov/eere/buildings/building-energy-data-exchange-specification-bedes)

*   [http://bedes.lbl.gov/](http://bedes.lbl.gov/)

Zoning and Zoning Overlays

| **Current Status** | ![](export/assets/image57png.png)Informal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Municipal, County, and State Planning Agencies that maintain Zoning Ordinances |
| **Potential Founding/Sponsoring Organizations** | American Planning Association |

**Analysis -- Future Potential and Adoption**

Zoning determines allowable uses for land in a community, and while a few cities have rejected zoning, most cities in the United States have a form of zoning code. An Open Zoning Data standard was proposed by Andrew Salzberg at the Open Data Day 2013 Hackathon in DC.

Zonability is a startup that attempts to process parcels and analyze for size and zoning requirements. This type of organization could potentially be interested in developing data standards.

**Additional Resources**

*   Andrew Salzberg draft - [http://andrewsalzberg.wordpress.com/2013/02/22/lets-build-an-open-zoning-data-standard/](http://andrewsalzberg.wordpress.com/2013/02/22/lets-build-an-open-zoning-data-standard/)

*   Zonability - [http://www.zonability.com/](http://www.zonability.com/)

Land Use

| **Current Status** | ![](export/assets/image58png.png)Informal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Municipal and county planning agencies |
| **Potential Founding/Sponsoring Organizations** | American Planning Association |

**Analysis -- Future Potential and Adoption**

Municipal and county governments have a deep interest in land use.Though land use is related to zoning, it is not necessarily the same.Most cities in the United States have some kind of zoning code, but not all of them, and actual land use is often equally important for planning purposes. The American Planning Association (APA) has developed the Land Based Classification Standards which provides planners with a consistent model for classifying land uses based on their characteristics.

**Additional Resources**

*   [https://www.planning.org/lbcs/](https://www.planning.org/lbcs/)

Building Permits and Construction Inspection

| **Current Status** | ![](export/assets/image59png.png)Informal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Local and State Agencies Responsible for Issuing Building Permits |
| **Potential Founding/Sponsoring Organizations** | Code for America |

**Analysis -- Future Potential and Adoption**

House Facts (see above) may be suitable for adaption, but it currently does not include building permit data. A discussion within the Code for America Brigade debated the available standards and the need for new building permit standardization in this thread: [https://groups.google.com/a/codeforamerica.org/forum/#!topic/brigade/KQrNGaHFJyc](https://groups.google.com/a/codeforamerica.org/forum/#!topic/brigade/KQrNGaHFJyc)

Other Safety Inspections

| **Current Status** | ![](export/assets/image60png.png)No standards for local inspection data |
| --- | --- |
| **Potential Implementing Agencies** | Local and State agencies responsible for inspection safety of buildings, infrastructure, and workplaces |
| **Potential Founding/Sponsoring Organizations** | United States Department of Labor |

**Analysis -- Future Potential and Adoption**

There are several types of safety inspections performed by government entities. Health inspections are addressed under the LIVES entry (see above). Infrastructure, such as bridges, embankments and water inlets, also received regular inspections and the transparency of this data varies a great deal between jurisdictions. For workplace safety inspections, OSHA maintains large amounts of data on safety inspections. Much of this data is released in aggregate by industry and location, but OSHA also maintains a work-related injury and illness database under the OSHA Data Initiative (ODI) and the ODI data is available as downloadable machine-readable files from 2002 to 2011.

**Additional Resources**

*   OSHA Stats - [https://www.osha.gov/oshstats/](https://www.osha.gov/oshstats/)

*   OSHA ODI Database - [https://www.osha.gov/pls/odi/establishment_search.html](https://www.osha.gov/pls/odi/establishment_search.html)

Travel Monitoring and Volume

| **Current Status** | ![](export/assets/image61png.png)![](export/assets/image13png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.pngSome formal federal |
| --- | --- |
| **Potential Implementing Agencies** | State Department of Transportation Agencies |
| **Potential Founding/Sponsoring Organizations** | Federal Highway Administration |

**Analysis -- Future Potential and Adoption**

Traffic volume is monitored by several entities.The US Department of Transportation, Federal Highway Administration collects data from 4,000 continuous traffic counting locations in the federal highway system.This Traffic Volume Trends (TVT) is reported by State DoTs monthly and published in PDF and Excel formats.State DOTs and local transportation agencies carry about significant additional traffic surveys.This more detailed data may be published by a few municipalities, but there is no data standard for doing so.The data is most readably available from private firms that aggregate, display or package the data, including Streetlytics, Google Maps, Waze and others.

**Additional Resources**

*   Traffic Volume Trends (TVT) - [http://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm](http://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm)

*   Travel Monitoring Guide - [http://www.fhwa.dot.gov/policyinformation/tmguide/](http://www.fhwa.dot.gov/policyinformation/tmguide/)

*   Houston Regional Traffic Count Map - [http://ttihouston.tamu.edu/hgac/trafficcountmap/](http://ttihouston.tamu.edu/hgac/trafficcountmap/)

*   Additional US DoT Resources:[http://www.fhwa.dot.gov/policyinformation/travelmonitoring.cfm](http://www.fhwa.dot.gov/policyinformation/travelmonitoring.cfm)

Real-time Travel Conditions

| **Current Status** | ![](export/assets/image12png.png)![](export/assets/image15png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.pngFormal, Not Open. |
| --- | --- |
| **Potential Implementing Agencies** | State Department of Transportation Agencies |
| **Potential Founding/Sponsoring Organizations** | Federal Highway Administration |

**Background**

The 511 system was established by the Federal Highway Administration but is implemented separately by each state.Most states have now adopted the standard, and federal funding is provided to support additional extensions.The system provides data on incidents, construction, weather alerts, road closures and traffic speed.Though the “511” moniker implies a phone-based system, many states now provide mobile applications, online maps, and data feeds.However, the system does not have a standard publishing format and it’s use may well suffer from increased use of in-car navigation systems and existing map platforms, such as Google Maps Traffic, that rely on large amounts of crowd-sourced data, rather than a centralized data collection process.

**Additional Resources**

*   National Traffic and Road Closure - [http://www.fhwa.dot.gov/trafficinfo/index.htm](http://www.fhwa.dot.gov/trafficinfo/index.htm)

*   Status of 511 Deployment - [http://www.fhwa.dot.gov/trafficinfo/511.htm](http://www.fhwa.dot.gov/trafficinfo/511.htm)

*   511 Guide - http://www.ops.fhwa.dot.gov/511/resources/publications/[511guide](http://www.ops.fhwa.dot.gov/511/resources/publications/511guide_ver3/511guide3.htm)_ver3/511guide3.htm

Traffic Accidents

| **Current Status** | ![](export/assets/image14png.png)![](export/assets/image09png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.pngFormal, Not Open. |
| --- | --- |
| **Potential Implementing Agencies** | State and Local Departments of Transportation, traffic safety advocacy organizations, Regional Planning Organizations |
| **Potential Founding/Sponsoring Organizations** | National Highway Traffic Safety Administration |

**Analysis -- Future Potential and Adoption**

While there are national standards for reporting crash records and information, the data is generally only required to be submitted to the National Highway Traffic Safety Administration.Therefore, the data is usually available only by request from the steward -- such as a state or local department of transportation. In 2016, the White House released 2015 traffic fatality information along with a call-to-action to analyze the data. However, no open data standard was adopted as part of this data release.

Providing this data in a standardized, machine-readable format would enable civic developers and planners to better communicate this data to citizens.In addition, the public could be more responsive and aware of high crash areas and advocate for safer streets and better planning.

**Additional Resources**

*   Fatality Analysis Reporting System - [http://www.nhtsa.gov/FARS](http://www.nhtsa.gov/FARS)

*   NHTSA Traffic Records Division - [http://www.nhtsa.gov/Data/Traffic+Records](http://www.nhtsa.gov/Data/Traffic+Records)

*   Model Minimum Uniform Crash Criteria reporting standards - [http://www.mmucc.us/](http://www.mmucc.us/)

*   2015 Traffic Fatalities Data Released: A Call to Action to Download and Analyze - [https://www.transportation.gov/fastlane/2015-traffic-fatalities-data-has-just-been-released-call-action-download-and-analyze](https://www.transportation.gov/fastlane/2015-traffic-fatalities-data-has-just-been-released-call-action-download-and-analyze)

Parking

| **Current Status** | ![](export/assets/image08png.png)Formal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | City governments -- streets and highway commissions, parking enforcement agencies |
| **Potential Founding/Sponsoring Organizations** | Streetline |

**Analysis -- Future Potential and Adoption**

Parking data – including lot locations, meter locations and times, street parking regulations, parking lot locations, pricing, availability – is in great demand but is not generally made available by public agencies.In many cities, there may not be a single source of such data with a mix of public and private parking providers.Standardizing and releasing parking data would enable drivers in congested areas to park quickly and efficiently, reducing carbon emissions and frustration.While a few U.S. cities have released some parking information, it remains a fragmented effort.There are several private firms attempting to improve access to parking data.The best open data example we found was in the Netherlands.

**Additional Resources**

*   Streetline - [http://www.streetline.com/](http://www.streetline.com/)

*   Intertraffic - [http://www.intertraffic.com/Pages/default.aspx](http://www.intertraffic.com/Pages/default.aspx)

*   Intertraffic proposal for open data standard -[http://www.intertraffic.com/intertraffic-amsterdam/Documents/Open%20Parking%20Data%20Presentation%2013.30.pdf](http://www.intertraffic.com/intertraffic-amsterdam/Documents/Open%20Parking%20Data%20Presentation%2013.30.pdf)

*   Netherlands (Beter Benutten)- [http://www.beterbenutten.nl/](http://www.beterbenutten.nl/)

Bicycle Infrastructure and Routes

| **Current Status** | ![](export/assets/image11png.png)Informal proposal specifically related to bike share systems |
| --- | --- |
| **Potential Implementing Agencies** | Bike Share Providers, Municipal and County governments, Streets and Highway Commissions, Departments of Transportation |
| **Potential Founding/Sponsoring Organizations** | Michael Schade, Mobility Lab |

**Analysis -- Future Potential and Adoption**

The importance of bicycle infrastructure is growing in the United States as more people use bicycles for both primary and secondary transportation.Public bicycle infrastructure includes bike lanes, dedicated trails, and parking locations.Several cities publish bike lane data and the OpenStreetMap community maintains a global OpenCycleMap of bicycle-related infrastructure.However, no standards have been developed for publishing the data.

In addition to physical infrastructure, there has also been interest in tracking bicycle routes.Unlike the extensive infrastructure devoted to automobile traffic, there is less systematic data available on bicycle route preferences.Some cities are beginning to conduct bicycle traffic surveys but the data is not published in a standardized way.In a few cities, civic hackers have developed bicycle route tracking apps for mobile phones.

In addition to public infrastructure, bike share systems are now operational in over 40 U.S. cities, including New York, Chicago and Boston.Many bike share programs release static snapshots of their database, but there is currently no standard for data structure.Michael Schade of Mobility Lab recently wrote a proposal for a bike share standard, but no bike share providers have adopted the standard as of the writing of this document.The goal of the bike share data standard is to collect information on bike share stations, usage, and bike trips -- which could be implemented for non-bike share infrastructure as well -- to plan for future infrastructure and facilities.

**Additional Resources**

*   Mobility Lab bike share data standard proposal - [http://mobilitylab.org/2014/03/06/an-open-data-standard-would-help-public-discover-bikesharing/](http://mobilitylab.org/2014/03/06/an-open-data-standard-would-help-public-discover-bikesharing/)

*   OpenCycleMap - [http://www.opencyclemap.org/](http://www.opencyclemap.org/)

Public Health

Flu Shots

| **Current Status** | ![](export/assets/image07png.png)Some formal standards but limited adoption |
| --- | --- |
| **Potential Implementing Agencies** | Federal, State and Local Health Agencies |
| **Potential Founding/Sponsoring Organizations** | Center for Disease Control (CDC) |

**Analysis -- Future Potential and Adoption**

Flu vaccinations contribute to overall positive public health. In addition to directly reducing flu illness, the Center for Disease Control (CDC) states that flu vaccinations can help to reduce frequency of visits to the doctor, missed days of work and school, and flu-related hospitalizations. It is important that the general public not only has access to flu shots, but can easily find the location of facilities that offers flu vaccinations.

Local public health officials typically aggregate information on the location of facilities that offer flu shots, but this information is not standardized or made available to the public via easy-to-use applications. Some cities, like Chicago, have developed applications that make the location data available to the public and standardized a data format for the location of facilities that provide flu shots. Other cities, like Philadelphia, are in the process of defining a standardized format.

The development of a standard data format will enable public health agencies to promote the use of location data in web applications and maps.

**Additional Resources**

*   Chicago Flu Shot Clinic Locations, 2013, Standard Format - [https://data.cityofchicago.org/developers/docs/flu-shot-clinic-locations-2013](https://data.cityofchicago.org/developers/docs/flu-shot-clinic-locations-2013)

*   City of Philadelphia Flu Shot Spec - [http://cityofphiladelphia.github.io/flu-shot-spec/](http://cityofphiladelphia.github.io/flu-shot-spec/)

Justice and Public Safety

Crime

| **Current Status** | ![](export/assets/image10png.png)![](export/assets/image06png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.pngFormal, commercial, none are sufficiently established. |
| --- | --- |
| **Potential Implementing Agencies** | Local and State Police Organizations |
| **Potential Founding/Sponsoring Organizations** | Federal Bureau of Investigation |

**Analysis -- Future Potential and Adoption**

There have been several efforts related to publication of crime data. Only one of these, an effort by a commercial company, is aimed at open, public data publishing. Each of the various efforts each deserve some mention, but we believe there remains significant opportunity to develop a standard that is similar to the Open311 system in the sense that it combines both an API and a data structure standard.

SpotCrime Open Crime Standard

SpotCrime, an online aggregator of crime data, has developed a prototype for crime reporting standard known as the SpotCrime Open Crime Standard (SOCS). SpotCrime also offers Catapult, a free software product to export crime records, which reports data in this new standard. However, the effort is based on the private company and does not yet appear to be used by any departments. With the addition of the right partners, we believe it might provide a good starting point for a useful standard. We also believe it would be most useful if it was designed to combine both data structure and API, similar to the Open311 standard.

**Additional Resources**

*   SpotCrime Documentation: [http://blog.spotcrime.com/2014/03/the-spotcrime-open-crime-data-standard.html](http://blog.spotcrime.com/2014/03/the-spotcrime-open-crime-data-standard.html)

UCR Crime Reports

The FBI facilitates the Uniform Crime Reports program through the Office of Management and Budget (OMB) which issues government-wide guidelines that “provide policy and procedural guidance to federal agencies for ensuring and maximizing the quality, objectivity, utility, and integrity of information (including statistical information) disseminated by federal agencies. This is a standard in reporting crime data but additional standards (and open standards) on other public safety data would be beneficial to those that maintain and analyze public safety data.

**Additional Resources**

*   [http://www.fbi.gov/about-us/cjis/ucr/data_quality_guidelines](http://www.fbi.gov/about-us/cjis/ucr/data_quality_guidelines)

National Information Exchange Model (NIEM)

NIEM is a community standard led by the US Department of Justice. The standard is an outgrowth of two earlier justice-related standards efforts, the Global Justice Information Sharing Initiative and initiatives by the Department of Homeland Security. NIEM is not aimed at publication of data to the public, but, rather, on the ability of different justice systems to interoperate. Further, its scope extends beyond crime reports to include arrests, property descriptions, emergency response and a host of other topics. The standard is now at version 3.0 and has been adopted by at least some jurisdictions in all 50 states. It is a very complex standard, however, and we do not believe it is appropriate as an open data standard aimed at publication to the general public.

**Additional Resources**

*   [https://www.niem.gov/](https://www.niem.gov/)

OGC Law Enforcement and Public Safety DWG

The Open Geospatial Consortium (OGC) has been gradually adding to the generic standards outlined above (see KML, GeoPackage, WMS, etc.) by developing domain-specific standards. One of these efforts is the Law Enforcement and Public Safety (LEAPS) Domain Working Group (DWG). The mission of the LEAPS DWG is to develop open geospatial standards for law enforcement, civil security and public safety. The working group includes representatives from several countries and is likely to generate standards with an international character. However, the group has yet to release any draft standards, and we do not currently believe its work will be relevant in the near future.

**Additional Resources**

*   [http://www.opengeospatial.org/projects/groups/leapsdwg](http://www.opengeospatial.org/projects/groups/leapsdwg)

Courts

| **Current Status** | ![](export/assets/image05png.png)No Progress |
| --- | --- |
| **Potential Implementing Agencies** | Local, State and Federal Court Systems |
| **Potential Founding/Sponsoring Organizations** | American Civil Liberties Union |

**Analysis -- Future Potential and Adoption**

Councils and administrative divisions in local government have received a great deal of attention for their open data efforts but the local judicial organizations have not. Open standards for court dockets, decisions, schedules and other judicial documents would greatly benefit the availability and usability of this material. Often, the data is published in PDF and other non-structured formats. Another significant impediment is the degree to which official court documents are processed and published by commercial firms and are only available through a paid subscription. Publishing in a machine readable and standardized formats that are openly available to the public would greatly increase the use within a jurisdiction and compare court records across regional areas.

Environment and Ecosystems

Environmental Sensors

| **Current Status** | ![](export/assets/image52png.png)Some formal standards but limited adoption |
| --- | --- |
| **Potential Implementing Agencies** | Commercial sensor developers, corporations required to monitor their pollutant levels, academic institutions |
| **Potential Founding/Sponsoring Organizations** | Environmental Protection Agency, Open Geospatial Consortium, XMPP Standards Foundation |

**Analysis -- Future Potential and Adoption**

Sensor data feeds of key air and water environmental metrics have been deployed for several decades in the United States.For example, the USGS has maintained electronic stream sensors for many years.While originally designed for real-time publication, the USGS now makes available machine-readable streams of data that can be collected and displayed.NOAA’s weather sensors are now augmented by thousands of smaller private weather sensors, many of which are made available as real-time streams of data through Weather Underground.

Almost all environmental sensors have a location component to their output.Recognizing this, the Open Geospatial Consortium (OGC) developed a Sensor Web Enablement (SWE) working group and adopted several related standards – Sensor Planning Service (SPS) and Sensor Observation Service (SOS), SensorML, TransducerML, PUCK, Sensors &amp; Observations (S&amp;O), Sensor Alert Service (SAS), and Web Notification Service (WNS) – beginning in 2002.However, the standards are both complex and verbose and have not enjoyed broad adoption.More recently, the OGC has launched a new working group called Sensor Web for the Internet of Things (IOT).This new group is aimed at developed a more streamlined set of standards that are more in line with contemporary web standards.

In parallel with the OGC, an industry working group, the XMPP Standards Foundation, has begun to apply the Extensible Messaging and Presence Protocol (XMPP) to sensor data feeds.The core ideas behind XMPP were originally developed by Jeremie Miller in 1999 in an effort to create an ability to run a single chat client for several chat networks (AOL, Yahoo and others).This later became the Jabber chat client and protocol and then the XMPP protocol adopted by the IETF.In the past few years, some companies have begun to take a second look at XMPP as a way for sensors to send messages and interoperate.

Finally, the US Environmental Protection Agency (EPA) has also been active in development of standards for measuring air and water quality.The Environmental Sampling, Analysis, and Results (ESAR) Data Standard is an example of one such standard.Published in 2006, ESAR includes four components and outlines standardized ways to share data from field to lab.However, it is clearly aimed at the scientific community and its complexity makes it unlikely to be adopted for publishing data to the public.

These new efforts to develop sensor data standards are being driven by the rapid drop in the cost and increase in capacity of sensors.As costs drop, the number of sensors is increasing quickly, and Cisco now estimates that there were 80 “things” connected to the Internet per second in 2013.Cisco further estimates this will reach 250 “things” connected per second in 2020 for a total of 8 billion new internet-connected devices per year by that time.Most of these new devices will be sensors that will tell us more about our homes, communities and infrastructure.Enabling these devices to transmit data, interoperate, and ensure security will be significant challenges that will require good standards.It remains unclear which, if any, standards will become dominant for US local government to publish sensor data, and, for the time-being, we expect this to continue as an ad hoc affair.

**Additional Resources**

*   Sensor Web Enablement Domain Working Group - [http://www.opengeospatial.org/projects/groups/sensorwebdwg](http://www.opengeospatial.org/projects/groups/sensorwebdwg)

*   OGC Sensor Web for IOT overview - [http://www.opengeospatial.org/projects/groups/sweiotswg](http://www.opengeospatial.org/projects/groups/sweiotswg)

*   XMPP Standards Foundation - [http://xmpp.org/](http://xmpp.org/)

*   EPA Next Generation Air Measurement - [http://www.epa.gov/research/airscience/next-generation-air-measuring.htm](http://www.epa.gov/research/airscience/next-generation-air-measuring.htm)

*   EPA Data Standards - [http://iaspub.epa.gov/sor_internet/registry/datastds/home/overview/home.do](http://iaspub.epa.gov/sor_internet/registry/datastds/home/overview/home.do)

*   ESAR Overview - [http://www.exchangenetwork.net/standards/ESAR_Overview_01_06_2006_Final.pdf](http://www.exchangenetwork.net/standards/ESAR_Overview_01_06_2006_Final.pdf)

Trees

| **Current Status** | ![](export/assets/image49png.png)Proposed, not adopted. |
| --- | --- |
| **Potential Implementing Agencies** | Parks and Forest Service |
| **Potential Founding/Sponsoring Organizations** | The Foundation for Urban Forest Management |

**Analysis -- Future Potential and Adoption**

Located in both street rights-of-way and parks, trees are an important part of the public infrastructure in many communities. Trees provide stormwater infiltration, carbon sequestration, energy use reduction and other ecosystem services value. They have also been demonstrated to increase both home values and biodiversity in many communities. Despite this important role, most cities do not have comprehensive databases of trees, but many of those cities that do have a tree inventory are publishing it.

Though no generally accepted data standards for trees, and this is another opportunity for an organization. In 2002 the USDA Forest Service developed a white paper to address proper tree data collection and management. There is also a new partnership of arboriculture researchers and practitioners, the Urban Tree Growth and Longevity (UTLG) Working Group that has the potential to develop some standards in this domain.

**Additional Resources**

*   USDA Community Tree Inventory White Paper - [http://www.umass.edu/urbantree/inventorywhitepaper.pdf](http://www.umass.edu/urbantree/inventorywhitepaper.pdf)

*   Urban Tree Growth and Longevity (UTGL) Working Group - [http://www.urbantreegrowth.org/goals.html](http://www.urbantreegrowth.org/goals.html)

Land Records

Street Addresses

| **Current Status** | ![](export/assets/image48png.png)Formal Standards, Proposals |
| --- | --- |
| **Potential Implementing Agencies** | Departments of Transportation, Streets and Highway Commissions, Governments |
| **Potential Founding/Sponsoring Organizations** | URISA, Federal Geographic Data Committee |

**Analysis -- Future Potential and Adoption**

Street address data is widely used and crucial to state and local government operations.It is usually available in one of two general forms:address ranges attached to a GIS road database, and as a list of valid addresses for a particular location.Due to the impact on postal delivery, emergency response, and other activities, there are several U.S. standards related to addressing.However, none of these standards have resulted in open data publishing standards at the municipal or state levels.The exception may be road centerline publication, which has been heavily influenced by the Census Bureau’s TIGER line program its GBF/DIME predecessor.

While the OpenStreetMap database provides a way to encode address information, the most significant effort in this domain is the OpenAddresses project, which both enables upload of unique addresses and supports free download and open APIs for developers.

**Additional Resources**

*   Federal Geographic Data Committee (FGDC) United States Thoroughfare, Landmark and Postal Address Data Standard [https://www.fgdc.gov/standards/projects/FGDC-standards-projects/street-address/index_html](https://www.fgdc.gov/standards/projects/FGDC-standards-projects/street-address/index_html)

*   OpenAddresses - [http://openaddresses.io/](http://openaddresses.io/)

Deed / Mortgage Registrations

| **Current Status** | ![](export/assets/image51png.png)No Progress |
| --- | --- |
| **Potential Implementing Agencies** | Local property information recording agencies (Register of Deeds, Clerk, Recorder) |
| **Potential Founding/Sponsoring Organizations** | Property Records Industry Association, state or national associations of clerks and recorders |

**Analysis -- Future Potential and Adoption**

The County Clerk or Recorder registers many types of documents, including property title transfers (deeds), mortgages, mortgage satisfaction, wills. These documents are increasingly made available as digital data, but are rarely published in an open, machine-readable data format. There is significant opportunity to both improve the transparency of property records and provide better information on how communities are changing.

**Additional Resources**

*   Property Records Industry Association - [http://www.pria.us/](http://www.pria.us/)

Land Administration Model (LADM)

Though there are no data standards designed for publication of open data, the International Standards Organization (ISO) has developed a general land administration data model. This international standard for the land administration domain will, ideally, encourage the use of the data in civic applications and support sustainable development by speeding the use of proper land administration systems.

Countries, states and provinces seeking to eliminate the need to develop their own Land Administration Systems can standardize the system in which deeds (or land titles) are recorded and maintained. The Final Draft International Standard, ISO FDIS 19152, was unanimously passed on 1 November 2012.

This standard may become more important as software tools are developed to support it.

**Additional Resources**

*   Summary of LADM by the International Federal of Surveyors - [http://www.fig.net/news/news_2013/ladm2013/01.pdf](http://www.fig.net/news/news_2013/ladm2013/01.pdf)

Real Estate Sales

| **Current Status** | ![](export/assets/image50png.png)![](export/assets/image45png.png)http://etc-mysitemyway.s3.amazonaws.com/icons/legacy-previews/icons/matte-grey-square-icons-business/118946-matte-grey-square-icon-business-lock6-sc48.pngFormal, Not Open. |
| --- | --- |
| **Potential Implementing Agencies** | Real Estate Industry Partners (vendors, consultants, technology partners) |
| **Potential Founding/Sponsoring Organizations** | Federal |

**Analysis -- Future Potential and Adoption**

Real estate sales are largely carried out between private individuals or organizations, but due to taxation, deed registration and other activities, real estate transactions are of great importance to local governments. The data is generally available, though not always in a digital format, and there are no open standards for publishing the data.

However, because much of the transaction is carried out in the private sector and involves a broad array of companies and services (brokers, title insurance, appraisers, mortgages, etc.), the Real Estate Standards Organization was established to develop and maintain the Real Estate Transaction Standard (RETS). The documentation is public, but the standard is complex, and it is primarily used to support system interoperability between corporate data systems. As such, it is not a good fit for use in publishing open data.

The US General Services Administration (GSA) has established a Federal Real Property Council (FRPC) that has developed a Federal Real Property Profile (FRPP). A startup based in Boston, Opportunity Space, is reportedly developing a local property data standard based on the federal one, but it has not yet been published.

**Additional Resources**

*   Real Estate Standards Organization - [http://www.reso.org/](http://www.reso.org/)

    *   RETS Specification - [http://www.reso.org/assets/RETS/Specifications/rets_1_8.pdf](http://www.reso.org/assets/RETS/Specifications/rets_1_8.pdf)

    *   RETS Data Dictionary - [http://www.reso.org/data-dictionary-1-3](http://www.reso.org/data-dictionary-1-3)

    *   RETS Developer Resources -[http://www.reso.org/developer-resources](http://www.reso.org/developer-resources)

*   Federal Real Property Council - [http://www.gsa.gov/portal/content/104918](http://www.gsa.gov/portal/content/104918)

Real Estate Tax and Appraisals

| **Current Status** | ![](export/assets/image44png.png)No Progress |
| --- | --- |
| **Potential Implementing Agencies** | State and Local Real Estate Tax Commissions |
| **Potential Founding/Sponsoring Organizations** | The Appraisal Foundation (authorized by Congress as the source for appraisal standards and appraiser qualifications) |

**Analysis -- Future Potential and Adoption**

Real estate property tax assessment and tax paid by property owners is generally public information in most locations in the U.S. However, it is rarely made available through APIs or as bulk, machine-readable downloads. When it is, there are no data standards that would make the process more consistent between cities. Great potential exists for the creation of standards around not only tax values for properties but also the means for which tax values are calculated and disclosed to homeowners. This would be beneficial for property owners and buyers as well as individuals in the appraisal and realty industries.

**Additional Resources**

*   Uniform Standards of Professional Appraisal Practice (USPAP) – http://[www.uspap.org](http://www.uspap.org)/

Following the Money

Budget and Expenditures

| **Current Status** | ![](export/assets/image47png.png)Informal discussion |
| --- | --- |
| **Potential Implementing Agencies** | Local, State and Federal Governments |
| **Potential Founding/Sponsoring Organizations** | Open Knowledge Foundation, Local government entities, Data Transparency Coalition |

**Analysis -- Future Potential and Adoption**

Standard data formats for publication of municipal or other government budgets are not yet available. “Open budgeting” is usually part of a larger conversation regarding citizen participation in the budgeting process (“participatory budgeting”). The Open Knowledge Foundation (OKF) has developed a budget publication platform, OpenSpending, that is used by many governments around the world. The software is open source and it provides an API, which could serve as a foundation for an open budget standard. Socrata has also released applications specifically aimed at Open Budget and Open Expenditures. A candidate for City Controller in Philadelphia, Brett Mandel, successfully obtained a copy of the Philadelphia budget and developed an application that supported visualization and research on the local budget.

Government expenditures are an additional, related opportunity for open data standards. The budget sets the overall blueprint for spending, but the companies and individuals on which the budget is spent are an important additional type of data. In May 2014, the Digital Accountability and Transparency Act (DATA Act) was signed into law and calls for open, standardized data and online publication. As the law is enacted, it may spur additional steps at the local level.

**Other Resources**

*   OpenSpending - [https://openspending.org/](https://openspending.org/)

    *   API - [http://community.openspending.org/help/api/](http://community.openspending.org/help/api/)

    *   Resources - [http://community.openspending.org/research/](http://community.openspending.org/research/)

*   Socrata Open Budget and Open Expenditures - [https://socrata.com/products/open-data/](https://socrata.com/products/open-data/)

*   Participatory Budgeting in the US - [http://sunlightfoundation.com/blog/2013/07/15/open-budget-open-process-a-short-history-of-participatory-budgeting-in-the-us/](http://sunlightfoundation.com/blog/2013/07/15/open-budget-open-process-a-short-history-of-participatory-budgeting-in-the-us/)

*   DATA Act information - [http://datacoalition.com/issues/data-act.html](http://datacoalition.com/issues/data-act.html)

*   UK Standards Hub discussion - [http://standards.data.gov.uk/challenge/publishing-data-government-spending](http://standards.data.gov.uk/challenge/publishing-data-government-spending)

*   International Budget Partnership - [http://internationalbudget.org/](http://internationalbudget.org/)

*   World Bank resources on fiscal transparency - [http://wbi.worldbank.org/boost/tools-resources/topics/promoting-open-budgets/fiscal-transparency](http://wbi.worldbank.org/boost/tools-resources/topics/promoting-open-budgets/fiscal-transparency)

Lobbying

| **Current Status** | ![](export/assets/image46png.png)Informal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Lobbyists |
| **Potential Founding/Sponsoring Organizations** | Sunlight Foundation |

**Analysis -- Future Potential and Adoption**

Some states (for example: Indiana [http://www.in.gov/ilrc/2335.htm](http://www.in.gov/ilrc/2335.htm)) have made progress on lobbying data standards but no open standard exists. The Sunlight Foundation developed data recommendations and published a Municipal Lobbying Data Guidebook to help local policymakers and advocates create an environment of stronger lobbying disclosure.

**Additional Resources**

*   Sunlight Foundation Municipal Lobbying Data Guidebook - [http://sunlightfoundation.com/policy/municipal_lobbying_data_guidebook/](http://sunlightfoundation.com/policy/municipal_lobbying_data_guidebook/)

*   Sunlight Foundation Research - [http://sunlightfoundation.com/policy/municipal_lobbying/](http://sunlightfoundation.com/policy/municipal_lobbying/)

Campaign Contributions

| **Current Status** | ![](export/assets/image43png.png)Formal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Local, State and Federal Election and Campaign Monitoring Agencies |
| **Potential Founding/Sponsoring Organizations** | Sunlight Foundation |

**Analysis -- Future Potential and Adoption**

Some effort has been made to promote the disclosure of campaign finance contributions as well as the creation of databases of this information but no formal standard exists.Because of the way address and other affiliation data is maintained by different states, it is incredibly difficult to use this valuable information across geographic regions and years.Due to the lack of standardized publication, organizations such as the Sunlight Foundation, MapLight, and the National Center for Money in State Politics make enormous investments in cleaning data before it can be used.

However, the Sunlight Foundation has made substantial efforts to compile this data at the state and national level and make it available through a single download.More progress is needed to develop and encourage adoption of an open and universal standard.

**Additional Resources**

*   National Institute on Money in State Politics - [http://beta.followthemoney.org/](http://beta.followthemoney.org/)

*   MapLight - [http://maplight.org/](http://maplight.org/)

*   Open Secrets - [http://www.opensecrets.org/news/disclosure.php](http://www.opensecrets.org/news/disclosure.php)

Other Topics

Service Area Boundaries

| **Current Status** | ![](export/assets/image63png.png)Not Established |
| --- | --- |
| **Potential Implementing Agencies** | Local, State and Federal Governments |
| **Potential Founding/Sponsoring Organizations** | Federal Geographic Data Committee |

**Analysis -- Future Potential and Adoption**

The United States has a particularly complex set of local administrative and jurisdictional boundaries. In addition, each municipal and county government usually has several sub-divisions designed for different administrative purposes.Some progress has been made in data standards for “Governmental Units and Other Geographic Area Boundaries”. This does not specifically relate to service areas but could encompass this boundary type. This standard was developed in May 2008 by the Federal Geographic Data Committee as part of their Geographic Information Framework Data Standard. This standard mainly defines governmental, administrative and boundary units. Nonetheless, this FGDC effort has not generally been adopted and we believe there is significant opportunity to develop a standard way for localities to publish service area boundaries in a standardized way.

**Additional Resources**

*   [http://www.fgdc.gov/standards/projects/FGDC-standards-projects/framework-data-standard/GI_FrameworkDataStandard_Part5_GovernmentalUnitBoundaries.pdf](http://www.fgdc.gov/standards/projects/FGDC-standards-projects/framework-data-standard/GI_FrameworkDataStandard_Part5_GovernmentalUnitBoundaries.pdf)

Business Licenses and Registrations

| **Current Status** | ![](export/assets/image62png.png)Informal Discussion |
| --- | --- |
| **Potential Implementing Agencies** | Local and State agencies responsible for issuing business licenses and registrations |
| **Potential Founding/Sponsoring Organizations** | Code for America |

**Analysis -- Future Potential and Adoption**

Local data on business registrations is fragmented and largely unavailable.Private companies, such as Dun and Bradstreet and InfoUSA collect this data from state and local governments, but it is frequently out-of-date.In many municipalities, registration of a new business is required, but the municipality does not require a similar process when a business ceases operation.

The Census Bureau manages a federal standard, National American Industry Classification System (NAICS), for classifying businesses and employment data and would be in a good position to develop an open data standard for use by local and state levels.In addition, a new startup, OpenCorporates, has successfully assembled business registration listings for most countries in the world and now makes this data available through their web site and an API.

**Additional Resources**

*   NAICS - [https://www.census.gov/eos/www/naics/](https://www.census.gov/eos/www/naics/)

*   OpenCorporates - [https://opencorporates.com/](https://opencorporates.com/)

Public Notifications (Zoning, etc.)

| **Current Status** | ![](export/assets/image56png.png)Informal standard, not adopted |
| --- | --- |
| **Potential Implementing Agencies** | State and Local Agencies/Departments |
| **Potential Founding/Sponsoring Organizations** | San Francisco Mayor’s Office of Civic Innovation (SFMOCI) |

**Analysis -- Future Potential and Adoption**

The San Francisco Mayor’s Office of Civic Innovation project, Public Notifications Data Format (PNDF), seeks to establish standards and best practices for notifications from City departments. SFMOCI launched a pilot with several city departments in 2013, but there is little information available on the outcome or results of the pilot. There is the potential for some overlap between an open standard for public notifications -- for example, public notifications could be things like road closures and other events that might be covered by other standards. However, a PNDF could be useful for disseminating information like requests for zoning variances.Property owners or community associations are often required to notify neighbors within a certain radius.

**Additional Resources**

*   PNDF on GitHub: [https://github.com/SFMOCI/pndf](https://github.com/SFMOCI/pndf)

Council / Board Meeting Minutes

| **Current Status** | ![](export/assets/image54png.png)Open source software, but no standard in use |
| --- | --- |
| **Potential Implementing Agencies** | City and County Councils |
| **Potential Founding/Sponsoring Organizations** | MySociety, Open Civic Data, Code for America Brigades |

**Analysis -- Future Potential and Adoption**

Several organizations are currently working to make local government proceedings more open and accessible. The New York City Council recently passed a resolution requiring legislative tracking information and discretionary funding data be made available to the public in a machine readable format through an API. The MySociety organization has released a software component, SayIt, that can be used to both transcribe and search meeting minutes. SayIt is now also a component being supported by the Poplus network. A second open source project, Councilmatic, began in Philadelphia and is now also in use in Chicago for searching meeting minutes. None of these efforts have resulted in an open data standard but they are, nonetheless, in a good position to do so.

There is some overlap in this topic with the OCD Events standard (see above) and that may be another route to a standard.

*   New York City resolution - [http://techpresident.com/news/25023/rules-reform-new-york-city-council-aims-open-api](http://techpresident.com/news/25023/rules-reform-new-york-city-council-aims-open-api)

*   MySociety SayIt - [http://sayit.mysociety.org/](http://sayit.mysociety.org/)

*   SayIt Component on Poplus -[http://sayit.poplus.org/](http://sayit.poplus.org/)

*   Councilmatic - [http://www.councilmatic.org/](http://www.councilmatic.org/)

*   OCD Events standard -[http://docs.opencivicdata.org/en/latest/proposals/0004.html](http://docs.opencivicdata.org/en/latest/proposals/0004.html)

Flu Shot Spec

| **Current Status** | ![](export/assets/image23png.png)Proposed, in use in Philadelphia, Chicago and San Francisco |
| --- | --- |
| **Potential Implementing Agencies** | Public Health Agencies |
| **Potential Founding/Sponsoring Organizations** | City of Philadelphia, Code for America |

**Analysis -- Future Potential and Adoption**

The proposed data specification for flu shot locations is led by the city of Philadelphia in an effort to make flu shot location data more discoverable to the general public. In addition, it will aid city agencies in dissemination of this information, and allow third-party websites and civic applications to integrate the data.

*   Flu Shot Locations Data Spec: [http://cityofphiladelphia.github.io/flu-shot-spec/](http://cityofphiladelphia.github.io/flu-shot-spec/)