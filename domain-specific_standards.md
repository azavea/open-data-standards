# Domain-Specific Standards


## Akoma Ntoso



| **Current Status** | Limited adoption in the US but broader in some other countries |
| --- | --- |
| **Version Number** | 3.0 |
| **Key Contacts** | Prof. Monica Palmirani - email: monica.palmirani@unibo.it |
| **Implementing Agencies** | Courts and Parliaments |
| **Documentation** | [http://examples.akomantoso.org/categorical.html](http://examples.akomantoso.org/categorical.html) |
| **Founding/Sponsoring Organizations** | United Nations Department of Economic and Social Affairs |


**Background**
<br>
Parliaments and courts produce large quantities of documents during debates, committee briefs, journals, legislation life cycle and judgments.

Akoma Ntoso defines a set of machine readable data structures (in XML format) of parliamentary, legislative and judiciary documents. The main purposes of this standard are to define a common document format, model for document interchange, data schema, metadata schema and ontology, and schema for citation and cross referencing. This will increase the level of efficiency and accountability in parliamentary and judicial contexts.


**Analysis**
<br>
This data standard empowers the authors of these documents, the citizen analyzing the documents, those drafting and assembling the documents, and the civic hacker who builds solutions around the data. It allows the easy access, interpretation and dissemination of these documents quickly and easily.

Strategic goals include the creation of a common language for the interchange of parliamentary and legislative documents between institutes, facilitation of the long term storage and access of the documents, creation of common data and metadata models for information retrieval and the development of mechanisms for naming and linking documents. Additionally, the intent is for this standard to be both self-explanatory and extensible to allow for modifications within the framework for local customization.

**Additional Resources**

*   [http://examples.akomantoso.org/categorical.html](http://examples.akomantoso.org/categorical.html)



## Common Alerting Protocol (CAP)

| **Current Status** | Broadly adopted, mature, used internationally |
| --- | --- |
| **Version Number** | 1.2 |
| **Key Contacts** | ipaws@dhs.gov |
| **Implementing Agencies** |  |
| **Documentation** | [http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.pdf](http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.pdf) |
| **Founding/Sponsoring Organizations** |  |

**Background**
<br>
The Common Alerting Protocol (CAP) is a digital format for exchanging emergency alerts that allows a consistent alert message to be disseminated simultaneously over many different communications systems. It was developed by FEMA in collaboration with local entities and is maintained by the Organization for the Advancement of Structured Information Standards (OASIS). OASIS has helped to extend the standard for international use.

**Additional Resources**

*   Adapting CAP for Emergency Alerting Systems - [http://www.eas-cap.org/ECIG-CAP-to-EAS_Implementation_Guide-V1-0.pdf](http://www.eas-cap.org/ECIG-CAP-to-EAS_Implementation_Guide-V1-0.pdf)


## Election Markup Language (EML)

| **Current Status** | Published but very limited adoption |
| --- | --- |
| **Version Number** | v7.0 |
| **Key Contacts** | John Borras, Individual johnaborras@yahoo.co.uk |
| **Implementing Agencies** | Election commissions, e-voting companies |
| **Documentation** | [http://docs.oasis-open.org/election/eml/v7.0/eml-v7.0.html](http://docs.oasis-open.org/election/eml/v7.0/eml-v7.0.html) |
| **Founding/Sponsoring Organizations** | [OASIS](https://www.oasis-open.org/) |

**Background**
<br>
The Organization for the Advancement of Structured Information Standards (OASIS) created the Voter Services Technical Committee in 2001 to develop XML standards for election and voter services information. To establish the specifics of the XML schemas, the committee also developed a generic election process model based on the work by election.com’s CTO.

**Analysis**
<br>
Election Markup Language is designed to be multinational, so that it could be adopted globally. However, it has had little in the way of adoption in the United States. The vast diversity in the types of democratic systems globally may be a major obstacle to the widespread adoption of this system. The EML standard could be more widely adopted if e-voting, or internet voting, took off in a more substantial way.Since the EML standard covers the end-to-end process of voting, it could streamline and simplify the process of setting up such a system. The United Kingdom experimented with using the EML standard for an e-voting pilot and Belgium currently uses EML in its local government elections.

**Additional Resources**

*   [https://www.oasis-open.org/standards](https://www.oasis-open.org/standards)


## General Transit Feed Specification (GTFS)

| **Current Status** | Adopted and broadly implemented |
| --- | --- |
| **Version Number** | Last update February 3, 2016 |
| **Key Contacts** | Bibiana McHugh - Portland TriMet IT Manager |
| **Implementing Agencies** | Public transportation agencies |
| **Documentation** | Docs: [https://developers.google.com/transit/gtfs/](https://developers.google.com/transit/gtfs/) |
| **Founding/Sponsoring Organizations** | Google and Portland TriMet |

**Background**
<br>
Until 2005, there was no mapping platform that allowed to trip planning in anything other than a car. That year, Bibiana McHugh, the IT Manager at Portland, Oregon’s TriMet contacted Google and found that Chris Harrelson, a software engineer, was working on that problem. TriMet worked closely with Google to format the agencies transit schedules to work with the Google Transit Trip Planner and it launched in December 2005\. In 2006, five more cities got on board and the project became branded Google Transit Feed Specification. Recently, the standard was renamed General Transit Feed Specification to acknowledge the agnostic aspect of the data’s purpose.

**Analysis**
<br>
GTFS has become the common language for transit. Over 700 agencies worldwide have adopted the GTFS standard for reporting public transit schedules. While mainly used for trip planning, GTFS data can also be used for data visualization and maps, measures of accessibility and timetable creation.

**Additional Resources**

*   Transit Land - reference and site for transit agencies to connect with developers : [https://transit.land/](https://transit.land/)

*   Transit Feeds - repositories built on Github: [http://transitfeeds.com/](http://transitfeeds.com/)


## GTFS-RT (Real-Time)

| **Current Status** | Adopted |
| --- | --- |
| **Version Number** | Last updated July 29, 2015 |
| **Key Contacts** |  |
| **Implementing Agencies** | Public transit agencies |
| **Documentation** | Docs: [https://developers.google.com/transit/gtfs-realtime/](https://developers.google.com/transit/gtfs-realtime/) |
| **Founding/Sponsoring Organizations** | Google, Live Transit Updates agencies |

**Background**
<br>
Introduced in 2011, the specification was created through a partnership of Google’s Live Transit Updates agencies, transit developers and Google.

**Analysis**
<br>
GTFS-RT is an extension of GTFS (and essentially, a new standard) to allow public transit agencies to submit real-time location and status information about their fleets.It is currently implemented by about a dozen transit agencies worldwide.One obstacle to adoption may be the initial investment of fleet tracking systems as well as the wireless bandwidth required to communicate positions of every vehicle in a large fleet.Another factor may be the NextBus Company, which installs and maintains an enterprise GPS system for many public transit agencies.There have also been active patent disputes with ArrivalStar, a non-practicing entity (aka “patent troll”) that had been bringing patent suits against transit agencies.ArrivalStar agreed to stop pursuing transit agencies in late 2013, and this has cleared the way for agencies to release more tools that would leverage GTFS-RT.

**Additional Resources**

*   Directory of transit feeds: [http://transitfeeds.com/search?q=gtfsrt](http://transitfeeds.com/search?q=gtfsrt)


## Google Civic Information API

| **Current Status** | Relatively new, but well supported and documented |
| --- | --- |
| **Version Number** | 2.0 |
| **Key Contacts** |  |
| **Implementing Agencies** | N/A (Google assembles data from several sources) |
| **Documentation** | [https://developers.google.com/civic-information/docs/v2/](https://developers.google.com/civic-information/docs/v2/) |
| **Founding/Sponsoring Organizations** | Google, Pew Charitable Trusts (for VIP data) |

**Background**
<br>
The Google Civic Information API was originally released in private beta as a unified source for elections, polling places and other data from the Voting Information Project (see below). In fall 2013, it was extended to include the ability to look up elected office holders at the local, state and national levels. The API currently supports:

*   Elections (based in VIP)
*   Representatives
*   Divisions

**Analysis**
<br>
While not, strictly speaking, an open standard, the Google Civic Information aggregates several data sources, including the Voting Information Project (VIP), Cicero and others. It implements the OCD Identifier standard.

**Additional Resources**

*   API Forum: [https://developers.google.com/civic-information/docs/ci_forum](https://developers.google.com/civic-information/docs/ci_forum)

*   Using the API: [https://developers.google.com/civic-information/docs/using_api](https://developers.google.com/civic-information/docs/using_api)


## House Facts

| **Current Status** | Still evolving, limited adoption |
| --- | --- |
| **Version Number** | 0.2.3 |
| **Key Contacts** | [https://sites.google.com/site/housefactsdatastandard/home/contributors](https://sites.google.com/site/housefactsdatastandard/home/contributors) |
| **Implementing Agencies** | San Francisco, Las Vegas, Bloomington, Kansas City, Gary IN, Olathe KS (these have committed to implementing the standard, but only San Francisco and Kansas City were confirmed to have published using the standard) |
| **Documentation** | [https://sites.google.com/site/housefactsdatastandard/home](https://sites.google.com/site/housefactsdatastandard/home) |
| **Founding/Sponsoring Organizations** | The Civic Engine, Accela, Code for America, Civic Insight and Socrata. |

**Background**
<br>
The House Facts data standard provides a common format for reporting government data on the operation, safety, and performance of residential buildings. Reported information may include specifics regarding building structure, function, habitability safety and environmental performance. The initial version of the standard is focused on housing inspections.

**Analysis**
<br>
This data standard is intended to have substantial benefits in the civic sphere including: the full disclosure of property regulatory history of property prior to rent or purchase, search of data by property owner or property address, potential analysis by government, civic or academic agencies for patterns in inspection results, creation of city benchmarking for housing health and safety and most importantly general encouragement of improved property maintenance for homeowners.

**Additional Resources**

*   San Francisco: [https://data.sfgov.org/Housing-and-Buildings/Housing-Code-Violations-San-Francisco-CA/739v-w6y3](https://data.sfgov.org/Housing-and-Buildings/Housing-Code-Violations-San-Francisco-CA/739v-w6y3)

*   Kansas City: [https://odn.demo.socrata.com/Housing/Housefacts-Kansas-City/acmj-4g7g](https://odn.demo.socrata.com/Housing/Housefacts-Kansas-City/acmj-4g7g)


## Local Inspector Value Entry Specification (LIVES)

| **Current Status** | Published and adopted by a few large cities |
| --- | --- |
| **Version Number** | 2.0 |
| **Key Contacts** | https://www.codeforamerica.org/our-work/data-formats/LIVES/ |
| **Implementing Agencies** | Washington DC, San Francisco, New York |
| **Documentation** | [http://www.yelp.com/healthscores](http://www.yelp.com/healthscores) |
| **Founding/Sponsoring Organizations** | City of San Francisco, YELP, Code for America, City of New York |

**Background**
<br>
Restaurant inspections performed by health agencies usually result in unstructured data, making it difficult for these reports to be interpreted by the public. They were often released in PDF format with no standard structure. Additionally, substantial variations in the ratings and evaluation methods made it impossible to compare results across municipalities. In 2012, Yelp partnered with Code for America and the City of San Francisco to develop an open data standard which allows state and municipal health agencies to collect, format and publish restaurant inspection information on Yelp. The City of New York joined the effort at an early stage as well.

**Analysis**
<br>
This structure was originally developed to align with Yelp’s platform and provide consumers with quick information about restaurant cleanliness but it also encouraged innovative uses with this data by the public resulting from release in a standardized data format directly to the public. One key element is a guide that allows agencies to map qualitative information such as Good, Poor, Fair, A+, B-, etc. to a numeric system. Additionally, this standardization of collection made it possible to easily distribute this data and compare across regions. Now that a standard structure has been introduced, city health agencies often elect to release this data in API format such as Washington, DC.

The wide publication of this data has resulted in closer attention to restaurant cleanliness which studies have found led to 13% decrease in hospitalization due to foodborne illness in the City of Los Angeles. [http://kuafu.umd.edu/~ginger/research/JEH-final.pdf](http://kuafu.umd.edu/~ginger/research/JEH-final.pdf)

One impediment to adoption has been the differing standards for performing health inspections. Philadelphia, for example, has refused to adopt the standard and publish their inspection data on the basis of differing methodologies.

**Additional Resources**

*   DC: [http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e](http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e)

*   San Francisco: [https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb)


## Open311

| **Current Status** | Wide Adoption |
| --- | --- |
| **Version Number** | GeoReport v2, Inquiry v2 (draft) |
| **Key Contacts** | Philip Ashlock, phil@civicagency.org |
| **Implementing Agencies** | City Agencies that collect 311 (or equivalent) data |
| **Documentation** | [http://www.open311.org/2009/09/open311-is-a-specification-for-an-open-platform/](http://www.open311.org/2009/09/open311-is-a-specification-for-an-open-platform/) |
| **Founding/Sponsoring Organizations** | Open Plans |

**Background**
<br>
A 311 phone number allows for non-emergency municipal service issue reporting for situations such as street debris, potholes and nonworking streetlights as well as to obtain municipal information. OpenPlans, a nonprofit technology organization featuring digital solutions for civic problems originally developed the Open311 interoperable system that functions to coordinate standardized, open-access, read/write model for citizens to report on emergency issues. This standardized protocol allows for location based collaboration issue-tracking. A free API allows access to existing 311 services.

**Analysis**
<br>
The Open311 standard is one of the earliest and best established open data standards. It is in wide use across the United States. Some of the most prominent platforms that have adopted this system are FixMyStreet in the UK and SeeClickFix in the US. This standard is utilized by the following cities (among others): Chicago, IL; Toronto, ON; San Francisco, CA; Washington, DC; Boston, MA; New York City, NY. As 311 becomes a more commonplace service provided by municipalities, the further adoption and improvement of this standard is anticipated.

**Additional Resources**

*   Additional documentation

    *   [http://wiki.open311.org/GeoReport_v2/Resources](http://wiki.open311.org/GeoReport_v2/Resources)

    *   [http://wiki.open311.org/API](http://wiki.open311.org/API)

*   Status of Open311 systems in the US:
  *   [http://open311status.herokuapp.com/](http://open311status.herokuapp.com/)


## Open Civic Data

| **Current Status** | In Development; rapidly maturing; broad adoption in software but limited publishing by local and state legislatures |
| --- | --- |
| **Version Number** | Last updated 2015 |
| **Key Contacts** | James Turk, Sunlight Foundation james.p.turk@gmail.com |
| **Implementing Agencies** | Government agencies, election commissions, government information services, [Google Civic Information API](https://developers.google.com/civic-information/), Popolo Project, Granicus, Cicero |
| **Documentation** | Open Civic Data API:[http://docs.opencivicdata.org/en/latest/api/index.html](http://docs.opencivicdata.org/en/latest/api/index.html) |
| **Founding/Sponsoring Organizations** | Google, OpenNorth, Sunlight Foundation |

**Background**
<br>
The Open Civic Data project is a collaborative effort to define schemas and provide tools for collecting and disseminating information on government organizations, officials, legislation and events. Building off the work of the OpenStates project, the Sunlight Foundation sought to create a standard that would enable users to more easily digest election and government information. It is not one standard but rather six that cover several aspects of the democratic process. The most active implementations have been related to OCD IDs (divisions).

**Analysis**
<br>
The Open Civic Data project seeks to define a schema for the following:

* _Division_ - A political geography such as a state, county or congressional district.
  * [http://docs.opencivicdata.org/en/latest/proposals/0002.html](http://docs.opencivicdata.org/en/latest/proposals/0002.html)
* _Jurisdictions_ - A governing body that exists within a division, such as the PA House of Representatives.
  * [http://docs.opencivicdata.org/en/latest/proposals/0003.html](http://docs.opencivicdata.org/en/latest/proposals/0003.html)
* _Civic Events_ - A legislative event, such as a meeting or hearing.
  * [http://docs.opencivicdata.org/en/latest/proposals/0004.html](http://docs.opencivicdata.org/en/latest/proposals/0004.html)
* _Persons, Organizations, Posts and Memberships_ - A politician or government official, a group of people (such as a city council, state senate or committee). The Popolo specification (see above) is the basis for this OCD component.
  * [http://docs.opencivicdata.org/en/latest/proposals/0005.html](http://docs.opencivicdata.org/en/latest/proposals/0005.html)
* _Bills_ - A legislative document and its history, may technically be a resolution, appointment, or contract.
  * [http://docs.opencivicdata.org/en/latest/proposals/0006.html](http://docs.opencivicdata.org/en/latest/proposals/0006.html)
* _Votes_ - The record of a vote taken on a motion, such as a confirmation or passage of a bill.
  * [http://docs.opencivicdata.org/en/latest/proposals/0007.html](http://docs.opencivicdata.org/en/latest/proposals/0007.html)

**Additional Resources**

* GitHub Repository: [https://github.com/opencivicdata](https://github.com/opencivicdata)

* Pupa – software project for scraping OCD data: [https://github.com/opencivicdata/pupa](https://github.com/opencivicdata/pupa)

* OCD ID Lookup Tool for Canada: [http://opennorth.github.io/ocd-id-viewer/](http://opennorth.github.io/ocd-id-viewer/)

* Master List of OCD IDs: [https://github.com/opencivicdata/ocd-division-ids/tree/master/identifiers](https://github.com/opencivicdata/ocd-division-ids/tree/master/identifiers)


## Open Contracting Data Standard (OCDS)

| **Current Status** | Adopted internationally; well-funding; rapidly maturing |
| --- | --- |
| **Version Number** | 1.0 |
| **Key Contacts** | Twitter: [@ocdata](https://twitter.com/ocdata) |
| **Implementing Agencies** | San Mateo County, UK.gov |
| **Documentation** | [http://standard.open-contracting.org/](http://standard.open-contracting.org/) |
| **Founding/Sponsoring Organizations** | Open Contracting Partnership, World Wide Web Foundation |

**Background**
<br>
Governments around the world spend an estimated US $9.5 trillion every year through vendor contracts, but information about the contracting process is generally not made public and, even when public, it is scattered across multiple systems and websites. Public contracts are particularly vulnerable to waste, mismanagement, and corruption. This new standard is intended to give stakeholders access to a unified picture of contracting data and support more effective understanding of how public money is spent on contracts.

**Analysis**
<br>
This is a well-funded effort to improve transparency in government contracting. The standard is clearly aimed at international usage and has the potential for use across all levels of governments. The directory of agencies shows almost 30 governments now publishing using the standard, though most are international.

**Additional Resources**

*   OCDS GitHub: [https://github.com/open-contracting/standard](https://github.com/open-contracting/standard)

*   Directory of contracting data publishers: [http://ocds.open-contracting.org/opendatacomparison](http://ocds.open-contracting.org/opendatacomparison)

*   Software tools and resources: [http://standard.open-contracting.org/latest/en/support/tools/](http://standard.open-contracting.org/latest/en/support/tools/)


## OpenElections

| **Current Status** | In Progress |
| --- | --- |
| **Version Number** | v1 |
| **Key Contacts** | Serdar Tumgoren, Project Lead [https://twitter.com/zstumgoren](https://twitter.com/zstumgoren) |
| **Implementing Agencies** | State and local election commissions, Journalists, civic hackers |
| **Documentation** | Documentation: [http://docs.openelections.net/](http://docs.openelections.net/) |
| **Founding/Sponsoring Organizations** | John S. and James L. Knight Foundation’s Knight News Challenge |

**Background**
<br>
Funded by the Knight News Challenge in 2012, the goal of OpenElections is to create a free, standardized set of election results data for all federal and statewide offices in the United States.

**Analysis**
<br>
Currently, election results data can be hard to find -- especially for historical elections. The OpenElections platform aims to make a standard that journalists and civic developers can easily access for stories and web applications. There has been much progress around documentation of the standard, and assembling lists of election events. The major remaining challenge is the effort to crowdsource the actual election results. OpenElections maintains status information for each state on the homepage for the project. Ideally, election commissions that report results would do so in the OpenElections standard or even submit directly to OpenElections.

**Additional Resources**

*   Github repository: [https://github.com/openelections](https://github.com/openelections)


## OpenReferral

| **Current Status** | Initial drafts complete; implementation in a couple of cities. |
| --- | --- |
| **Version Number** | First draft of Human Services Data Specification |
| **Key Contacts** | Community Group:[https://groups.google.com/forum/#!forum/openreferral](https://groups.google.com/forum/#!forum/openreferral) |
| **Implementing Agencies** | Varies – usually a 211 system; regional United Way; or municipal/county human services agency |
| **Documentation** | Documentation: [https://www.openreferral.org/documentation/](https://www.openreferral.org/documentation/) |
| **Founding/Sponsoring Organizations** | Code for America, Purple Binder, [Ohana Project](http://ohanapi.org/) |

**Background**
<br>
Open Referral is a data structure and API for human services information and referral (I&amp;R) services. It was initiated by the DC Community Resource Project and Code for America. Commercial partners have included both Purple Binder and the Ohana project. Pilot projects using the OpenReferral standard have been launched in Washington DC and San Mateo County, CA.

There are three main components to I&amp;R services: taxonomy, data schema and the service endpoints:

*   _Taxonomy_ – a system for categorizing services – is particularly challenging for human services I&amp;R systems. The AIRS taxonomy has been widely adopted but is proprietary and can only be used if a license fee is paid. [OpenEligibility.org](http://openeligibility.org), is an effort to develop a more open taxonomic standard licensed under Creative Commons.

*   _Data Schemas_ – The AIRS taxonomy has published an AIRS XSD schema document.A more open schema has been proposed by Google to support better search engine indexing and is published by the [W3C Civic Services](http://www.w3.org/wiki/WebSchemas/CivicServices) initiative at Schema.org. The latter is designed for municipal services but could be extended for human services applications. There is also the potential to harmonize the two data schemas.

*   _Service Endpoint_ – The Ohana API is perhaps the best example of an OpenReferral API endpoint.

**Analysis**
<br>
The OpenReferral project consists of a stack of standards and specifications for sharing community resource data. The effort began as a project for San Mateo County by a Code for America team in 2013\. The team received a Knight Foundation grant in 2014 to support continued development of both the standard and the Ohana API.

**Additional Resources**

*   Overview slides of OpenReferral: [https://t.co/jSICPg59jx](https://t.co/jSICPg59jx)

*   Ohana API: [https://github.com/codeforamerica/ohana-api](https://github.com/codeforamerica/ohana-api)


## OpenTrails

| **Current Status** | Recently developed |
| --- | --- |
| **Version Number** | 1.1 |
| **Key Contacts** | Jack Madans: jack@codeforamerica.org |
| **Implementing Agencies** | City of Portland, Oregon, Northeast Ohio (Cuyahoga Valley) |
| **Documentation** | Specification:[https://www.codeforamerica.org/specifications/trails/spec.html](https://www.codeforamerica.org/specifications/trails/spec.html) |
| **Founding/Sponsoring Organizations** | City of Portland, Code for America, Esri Portland R&amp;D Center, Strava, All Trails, National Recreation and Parks Association, GreenInfo Network, Trust for Public Lands, Intertwine Alliance, Trailhead Labs |

**Background**
<br>
The OpenTrails specification was launched in Northeast Ohio through Code for America. It was later introduced to the Portland, Oregon region at the 2014 National Day of Civic Hacking. Several commercial partners have since helped to introduce to the standard to other locations. The standard covers five data types:

*   Trail Segments (GeoJSON)
*   Trailheads (GeoJSON)
*   Named Trails (CSV)
*   Stewards ( CSV)
*   Areas (optional) – parks and preserves

**Analysis**
<br>
While only introduced in spring 2014, the combination of active participation by several commercial firms, a few government agencies and nonprofit organizations suggests that this standard has a strong future.

**Additional Resources**

*   Data Community Website:[http://www.opentraildata.org/](http://www.opentraildata.org/)

*   OpnTrails Github Repo: [https://github.com/opentraildata](https://github.com/opentraildata)

*   August 2014 Webinar Series:[http://www.codeforamerica.org/specifications/trails/](http://www.codeforamerica.org/specifications/trails/)


## Popolo

| **Current Status** | Adopted by OCD but not yet used by government agencies |
| --- | --- |
| **Version Number** | 1.0.1 |
| **Key Contacts** | James McKinney james@opennorth.ca |
| **Implementing Agencies** | Governments, open government organizations |
| **Documentation** | Specification:[http://popoloproject.com/specs/](http://popoloproject.com/specs/) |
| **Founding/Sponsoring Organizations** | OpenNorth |

**Background**
<br>
James McKinney, civic developer, co-founder of OpenNorth, and part of the OpenGovernment.org team, conceived Popolo as a way to create an open government data scheme that could easily be re-used by other civic developers. The project was created and launched in 2013\. While it is a standalone standard, in 2014, Popolo was adopted as the basis for the Open Civic Data (OCD) People, Organization and Membership component.

**Analysis**
<br>
Popolo is an open government specification that seeks to set a standard naming scheme for the basic of any government monitoring website. The ultimate goal of the project is to make it easier and quicker for civic developers to create government transparency and civic engagement websites, by offering them re-usable, well-documented open-source code. Several open source programming packages (python, Node.js, Ruby on Rails) have been created that use the Popolo standard.

**Additional Resources**

* Github repo: [https://github.com/opennorth/popolo-spec](https://github.com/opennorth/popolo-spec)


## Voting Information Project (VIP)

| **Current Status** | In Progress, Adopted by 20 states in 2010 election and by most states in 2012 election |
| --- | --- |
| **Version Number** |  |
| **Key Contacts** | Jared Marcotte, Pew Charitable Trusts, jmarcotte@pewtrusts.org |
| **Implementing Agencies** | Primarily state with some local election commissions |
| **Documentation** | [https://www.votinginfoproject.org/](https://www.votinginfoproject.org/) |
| **Founding/Sponsoring Organizations** | Pew Charitable Trusts, Google |

**Background**
<br>
The idea for the Voting Information Project (VIP) came out of the election analysis report, “Being Online Is Not Enough”, produced by the Pew Charitable Trusts in 2008\. One of the report&#039;s major findings was that providing on-demand access about voting information helps governments save money by reducing phone calls and visits by voters. Following the report, as a joint-effort between the Pew Charitable Trusts and Google, the VIP partnered with 9 states to provide pertinent voting information to citizens. In the 2010 election cycle, 20 states began contributing data feeds to the project.

**Analysis**
<br>
The goal of the VIP is to engage voters and drive voter turnout by ultimately making voting information more accessible. In short, the goals of the VIP, such as to answer common voting questions like “Where is my polling place?” and “What’s on my ballot?” are very important, however the obstacles are very challenging. The main challenge is participation. States must voluntarily contribute voting data to the program through a machine readable format. Thus, getting buy-in from state election commissions is extremely important. In the 2012 election cycle, most states participated by contributing at least some of the data gathered by the VIP project.The VIP project itself does not disseminate information; it relies on developers to build applications to make the data easy to access.In addition, the Google Civic Information API has adopted VIP information as a way to connect voters with their polling place and other VIP information. Several interesting projects have come out of the VIP, and can be found [here](https://www.votinginfoproject.org/projects). They include a mobile application to estimate wait time at a polling place.

**Additional Resources**

*   Election data feeds: [https://votinginfoproject.org/feeds](https://votinginfoproject.org/feeds)

*   Github repo: [https://github.com/votinginfoproject](https://github.com/votinginfoproject)

*   Google Civic Information API: [https://developers.google.com/civic-information/](https://developers.google.com/civic-information/)