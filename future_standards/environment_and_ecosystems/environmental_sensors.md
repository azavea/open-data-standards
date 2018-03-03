# Environmental Sensors
| Item | Description |
| --- | --- |
| **Current Status** | Some formal standards but limited adoption |
| **Potential Implementing Agencies** | Commercial sensor developers, corporations required to monitor their pollutant levels, academic institutions |
| **Potential Founding/Sponsoring Organizations** | Environmental Protection Agency, Open Geospatial Consortium, XMPP Standards Foundation |
<br>

## Analysis -- Future Potential and Adoption

Sensor data feeds of key air and water environmental metrics have been deployed for several decades in the United States.For example, the USGS has maintained electronic stream sensors for many years. While originally designed for real-time publication, the USGS now makes available machine-readable streams of data that can be collected and displayed. NOAA’s weather sensors are now augmented by thousands of smaller private weather sensors, many of which are made available as real-time streams of data through Weather Underground.

Almost all environmental sensors have a location component to their output. Recognizing this, the Open Geospatial Consortium (OGC) developed a Sensor Web Enablement (SWE) working group and adopted several related standards – Sensor Planning Service (SPS) and Sensor Observation Service (SOS), SensorML, TransducerML, PUCK, Sensors &amp; Observations (S&amp;O), Sensor Alert Service (SAS), and Web Notification Service (WNS) – beginning in 2002. However, the standards are both complex and verbose and have not enjoyed broad adoption. More recently, the OGC has launched a new working group called Sensor Web for the Internet of Things (IOT). This new group is aimed at developed a more streamlined set of standards that are more in line with contemporary web standards.

In parallel with the OGC, an industry working group, the XMPP Standards Foundation, has begun to apply the Extensible Messaging and Presence Protocol (XMPP) to sensor data feeds. The core ideas behind XMPP were originally developed by Jeremie Miller in 1999 in an effort to create an ability to run a single chat client for several chat networks (AOL, Yahoo and others). This later became the Jabber chat client and protocol and then the XMPP protocol adopted by the IETF. In the past few years, some companies have begun to take a second look at XMPP as a way for sensors to send messages and interoperate.

Finally, the US Environmental Protection Agency (EPA) has also been active in development of standards for measuring air and water quality. The Environmental Sampling, Analysis, and Results (ESAR) Data Standard is an example of one such standard. Published in 2006, ESAR includes four components and outlines standardized ways to share data from field to lab. However, it is clearly aimed at the scientific community and its complexity makes it unlikely to be adopted for publishing data to the public.

These new efforts to develop sensor data standards are being driven by the rapid drop in the cost and increase in capacity of sensors. As costs drop, the number of sensors is increasing quickly, and Cisco now estimates that there were 80 “things” connected to the Internet per second in 2013. Cisco further estimates this will reach 250 “things” connected per second in 2020 for a total of 8 billion new internet-connected devices per year by that time. Most of these new devices will be sensors that will tell us more about our homes, communities and infrastructure. Enabling these devices to transmit data, interoperate, and ensure security will be significant challenges that will require good standards. It remains unclear which, if any, standards will become dominant for US local government to publish sensor data, and, for the time-being, we expect this to continue as an ad hoc affair.

## Additional Resources

*   Sensor Web Enablement Domain Working Group - [http://www.opengeospatial.org/projects/groups/sensorwebdwg](http://www.opengeospatial.org/projects/groups/sensorwebdwg)
*   OGC Sensor Web for IOT overview - [http://www.opengeospatial.org/projects/groups/sweiotswg](http://www.opengeospatial.org/projects/groups/sweiotswg)
*   XMPP Standards Foundation - [http://xmpp.org/](http://xmpp.org/)
*   EPA Next Generation Air Measurement - [https://www.epa.gov/sciencematters/epas-next-generation-air-measuring-research]
*   EPA Data Standards - [http://iaspub.epa.gov/sor_internet/registry/datastds/home/overview/home.do](http://iaspub.epa.gov/sor_internet/registry/datastds/home/overview/home.do)
*   ESAR Overview - [http://www.exchangenetwork.net/standards/ESAR_Overview_01_06_2006_Final.pdf](http://www.exchangenetwork.net/standards/ESAR_Overview_01_06_2006_Final.pdf)
