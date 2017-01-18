# Local Inspector Value Entry Specification (LIVES)

| Item | Description |
| --- | --- |
| **Current Status** | Published and adopted by a few large cities |
| **Version Number** | 2.0 |
| **Key Contacts** | https://www.codeforamerica.org/our-work/data-formats/LIVES/ |
| **Implementing Agencies** | Washington DC, San Francisco, New York |
| **Documentation** | [http://www.yelp.com/healthscores](http://www.yelp.com/healthscores) |
| **Founding/Sponsoring Organizations** | City of San Francisco, YELP, Code for America, City of New York |
<br>
**Background**

Restaurant inspections performed by health agencies usually result in unstructured data, making it difficult for these reports to be interpreted by the public. They were often released in PDF format with no standard structure. Additionally, substantial variations in the ratings and evaluation methods made it impossible to compare results across municipalities. In 2012, [Yelp](https://www.yelp.com/) partnered with [Code for America](https://www.codeforamerica.org/) and the City of San Francisco to develop an open data standard which allows state and municipal health agencies to collect, format and publish restaurant inspection information on Yelp. The City of New York joined the effort at an early stage as well.

**Analysis**

This structure was originally developed to align with Yelp’s platform and provide consumers with quick information about restaurant cleanliness but it also encouraged innovative uses with this data by the public resulting from release in a standardized data format directly to the public. One key element is a guide that allows agencies to map qualitative information such as Good, Poor, Fair, A+, B-, etc. to a numeric system. Additionally, this standardization of collection made it possible to easily distribute this data and compare across regions. Now that a standard structure has been introduced, city health agencies often elect to release this data in API format such as Washington, DC.

The wide publication of this data has resulted in closer attention to restaurant cleanliness which [studies have found led to 13% decrease in hospitalization due to foodborne illness in the City of Los Angeles](http://kuafu.umd.edu/~ginger/research/JEH-final.pdf).

One impediment to adoption has been the differing standards for performing health inspections. Philadelphia, for example, has refused to adopt the standard and publish their inspection data on the basis of differing methodologies.

**Additional Resources**

* Washington DC: [http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e](http://www.opendatadc.org/dataset/restaurant-inspection-data/resource/b245d2d7-9c32-49b5-a795-6d47ba714d5e)

* San Francisco: [https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores/stya-26eb)
