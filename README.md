# disastermap
Demonstration map for disaster response and archaeology. For Keeping History Above Water conference, 2017. This data should not be used for official planning or decision making. Demonstration available at [https://aejolene.github.io/disastermap/](https://aejolene.github.io/disastermap/)


 
  
Presentation details:

## Archaeology Disaster Response
A demonstration map for Keeping History Above Water Conference, November 1, 2017
						
### Using the Digital Index of North American Archaeology for Rapid Disaster Response and Reporting

**Jolene Smith, David G. Anderson, Eric Kansa, Joshua Wells, and Stephen Yerka**

![title slide](https://github.com/aejolene/disastermap/blob/master/Slide1.JPG?raw=true)  

![authors](https://github.com/aejolene/disastermap/blob/master/Slide2.JPG?raw=true)  
 

Imagine this scenario: A disaster happens. Let’s say it’s a major hurricane. The storm hits smack dab in the center of the Virginia/Maryland coast, barreling across the usually-protective Eastern Shore barrier islands, tearing across Accomack and Northampton Counties in Virginia and Worcester and Somerset counties in Maryland, crossing the Chesapeake Bay, and making a strong, hard landfall. Storm surge ravages the coast and the tidal rivers. Heavy rainfall causes even more flood damage. The storm passes and we begin to pick up the pieces. 
![Flooding at the Norfolk Naval Base, 2003](https://github.com/aejolene/disastermap/blob/master/Slide3.JPG?raw=true)  

In Virginia, large numbers of historic properties are in geographic areas that would be affected by Category 4 storm surge, including about 20,000 above ground/architectural properties and 3,500 recorded archaeological sites. Many of these coastal areas are rural and have not been subjected to systematic cultural resource survey at all, so their numbers are underrepresented. 

This demonstration and discussion today will focus on archaeological sites in Virginia and Maryland, but it could be easily broadened across state lines and to many more types of disaster response beyond hurricanes and coastal flooding. 

Strong and erratic weather events, and general sea level rise, as products of global climate change projected for future decades, have significant likelihood to ultimately impact a large but unpredictable fraction of both pre-Columbian and historic human habitation of the coastal margin of the mid-Atlantic and Southeast. While archaeologists have raised alarm about the prospect of climate change related destruction, the lack of comprehensive data about archaeological sites has made it difficult to understand the nature and scope of the threats. The Digital Index of North American Archaeology (DINAA), a multi-institutional collaboration aggregating archaeological data from multiple sources, provides a new window on the scope of the challenge.

**Needs and wants**
![Stakeholders include SHPO staff, federal, state, and local government staff.](https://github.com/aejolene/disastermap/blob/master/Slide4.JPG?raw=true)  
In the wake of a disaster like this hypothetical storm, how can we respond to impacts to historic resources?

Stakeholders in these response activities are usually staff at the state historic preservation office (SHPO), federal emergency response personnel at multiple levels, state-level emergency response coordinators and other agencies working with them, as well as local government representatives. 

States and localities first and foremost need efficient assistance to recover from the disaster. Quick and accurate decision-making is critical. SHPO staff need the ability to support compliance with environmental and historic preservation legislation mandated by the respective state and federal governments. SHPO staff also need the ability to convey information about historic resources quickly and without unmanageable additional workload.

Disaster response agencies and localities need to be able to act fast. They need information to be relevant and straightforward. SHPO datasets and online systems are complex and can be overwhelming to people without backgrounds in the jargon of cultural resource management when the applications are designed to serve architectural historians and archaeologists. Responders need to be able to quickly identify if an area is sensitive (or if we are unsure) and they need to know who to contact for more coordination.

Storms happen across state lines, adding more complexity to potentially (or inevitably) chaotic situations. State historic preservation offices’ ways of organizing information vary greatly throughout the country. Some maintain easily accessible web databases. Others have helpful mapping applications. Some provide information on an as-needed basis. And none describe anything in the same way. Variability can make assembling information a significant challenge in the aftermath of an emergency.

**DINAA**
![Open Context screenshot](https://github.com/aejolene/disastermap/blob/master/Slide7.JPG?raw=true)  
Via Open Context, an archaeological data publishing service, the Digital Index of North American Archaeology (DINAA) publicly and openly publishes “site file” data curated by state officials from multiple US states. By ontologically mapping the state datasets together into a common schema and indexing with shared metadata, DINAA creates a unified platform to enable federal, state, and local governmental heritage resource managers and the general public alike to meet through a shared public scientific resource, as well as to identify priorities for protection in a preparatory manner, and respond to impacts in the aftermath of a weather event.
![DINAA map](https://github.com/aejolene/disastermap/blob/master/Slide8.JPG?raw=true)  

![DINAA principles](https://github.com/aejolene/disastermap/blob/master/Slide9.JPG?raw=true)  

In order to create the DINAA system, the project aggregates and renders interoperable the scientific and cultural descriptors utilized by state archaeological site files, all utilized as a base layer. The base layer is then enhanced through a linked open data (LOD) framework to provide further detail about available information such as Federal Register article reporting, academic journal references, and databases available from a variety of governmental, scientific, and curational sources. In combination, these data combine to form a window of archaeological big data through which a viewer may gain a sense of the overall characteristics of heritage resources present within any area of interest. The area of interest may be defined within DINAA’s spatial interface, or by utilizing the DINAA data structure to inform a GIS analysis conducted with more precise coordinates held in governmental heritage offices.

While archaeological site locations are generally considered to be sensitive due to the risk of looting and vandalism, the DINAA geospatial data online is randomized within a large grid for security. Defined occupation time periods and terms (extremely variable from state to state) are linked and cross-referenced, creating interoperable data for the first time. The full DINAA dataset is available to download and reuse, or to tap into in a web application via Open Context’s GeoJSON (an open geospatial standard) API, allowing end users to pull information selectively into a map and answer specific questions.

**Virginia Case Study**
![Virginia disaster response map screenshot](https://github.com/aejolene/disastermap/blob/master/Slide10.JPG?raw=true)  
For Keeping History Above Water, we’ve created a demonstration web map that could be used by emergency response personnel in the aftermath of a severe hurricane. It consists of an interactive map that can be viewed on desktop or mobile. The purpose of the map is to convey high level information from the SHPO to any number of external disaster responders. Since DINAA data is location-obscured, publication here allows us to create a map accessible without login credentials while keeping sensitive location data safe. For this example, the goal is to give a general impression of the archaeological sensitivity of an area and then provide a specific SHPO contact in order to connect people. 
![information flow from SHPO to DINAA to SHPO to public](https://github.com/aejolene/disastermap/blob/master/Slide11.JPG?raw=true)  

The tiles you see shaded represent 16 km x 16 km regions, as defined by the DINAA project. For this particular map we pulled Maryland and Virginia data, although information from eight other coastal states are or will soon be linked. Clicking on each tile displays a summary of total sites, as well as how many are eligible for listing on the National Register of Historic Places and an appropriate SHPO contact person to reach for coordination and additional information.

The red layer along coastal Virginia shows worst case Category 4 storm surge flood areas from the Virginia Department of Emergency Management [2014]. Combined, this information can rapidly give someone responding to or preparing to respond to a disaster an impression of the sensitivity of an area for archaeology, its likelihood to have been impacted, and a contact with whom to communicate.

A tool like this could allow for more immediate action internally within responding agencies, who may not have cultural resource staff available with the depth of expertise required to understand often complex SHPO databases.

Other available geospatial datasets could be added tailored to the audience and purpose for the map, including live, satellite data such as is produced by the E.U.’s Copernicus EMS. This map was built using Leaflet.js (a JavaScript library) and uses freely and openly available information for basemaps and data layers. Using open source software is a priority for the project members, although the DINAA geospatial data can easily be displayed in proprietary GIS applications like Esri Story Maps.

**Potential**
 
This demonstration is designed to show just one scenario in a range of possibilities for using state archaeological sites data from the Digital Index of North American Archaeology for disaster response and planning. Depending on the audience, research or policy question, and technological toolbox available, views of this information could look completely different from what you see here.

As we plan for the future, state data managers are encouraged to think about how to structure their databases and tools as well as how to ensure their data are open and accessible in order to easily interconnect with a larger ecosystem of information when time is of the essence.
![PIDBA and DINAA coastal risk maps](https://github.com/aejolene/disastermap/blob/master/Slide15.JPG?raw=true)  
The DINAA team is also using SHPO site data for long-range climate change planning due to sea level rise, with a peer-reviewed article expected to be published in the journal PLOS ONE within the next week and another forthcoming in the journal Antiquity. Using DINAA data combined with elevation models, the team analyzed nearly 130,000 archaeological sites within 200 km of the modern coastline. The analysis determined that over 19,000 sites will be inundated with a 1 m sea level rise (predicted to occur within a century), and around 25,000 sites submerged with a 3-5 m rise in seas. The sheer size of the multistate DINAA dataset can allow for powerful, high level planning and triage at a regional or continental scale in anticipation of flooding and more frequent severe weather events (Anderson et al. 2016).

DINAA project members looked at sites within 200 km of the present-day coastline, not only to examine the impacts of storms and flooding, but also to consider the effects of displacement of population in coastal areas, which will trigger additional development impacts further inland (Kansa et al., In Press).
![authors](https://github.com/aejolene/disastermap/blob/master/Slide16.JPG?raw=true)  
![authors](https://github.com/aejolene/disastermap/blob/master/Slide17.JPG?raw=true)  


By tapping into multi state archaeological data in DINAA we are able to make customize tools and views of our data that we can deploy immediately on any number of technological platforms. We can create completely customized interactive views, tailored to a specific need, question, or audience. Since all code and data are open other states, agencies, and organizations can adapt or build onto these ideas at no cost. 

Additionally, since we now, for the first time, have access to cross-referenced coastal sites data from multiple states, we can begin to address planning for impacts to archaeological sites by rising seas at a regional or even continental scale.

![acknowledgments and links](https://github.com/aejolene/disastermap/blob/master/Slide18.JPG?raw=true)  

**Works cited**

Anderson, D. G., Bissett, T, Yerka, S.J., Kansa, E.C., Kansa, S.W., DeMuth, C.C, Noack Myers, K.
2016	“Climate Change and Archaeological Site Destruction
in the Southeastern United States: The Role of DINAA (Digital Index of North American Archaeology) in Big Picture Research” A paper presented in the GeoSym 2016 Symposium “Mapping Outside the Lines: Geography as a Nexus for Interdisciplinary and Collaborative Research” Knoxville, Tennessee. 

Kansa, E. C., Kansa, S. W., Wells, J. J., Yerka, S. J., Myers, K. N., DeMuth, R. C., Bissett, T. G., & Anderson, D. G.
In Press 	“The Digital Index of North American Archaeology (DINAA): Networking Government Data to Navigate an Uncertain Future for the Past” Antiquity (Accepted: May 23, 2017)

Copernicus EMS
2017 http://emergency.copernicus.eu/mapping/ems-product-component/EMSR241_01TAMPANORTH_01DELINEATION_MAP/1

As implemented in 2017 Anne Katrien for Houston flooding:
https://annekatrien.github.io/EMSR229_webmap/#9/29.7605/-97.2823

Virginia Department of Emergency Managemnet
2014 Geospatial Dataset: Storm Surge: https://vdemgis.maps.arcgis.com/home/item.html?id=399ecade49144d938ded7a4459e7662e


[Digital Index of North American Archaeology](http://ux.opencontext.org/archaeology-site-data/)  
[Open Context](https://opencontext.org/)  
[Virginia Department of Historic Resources](http://www.dhr.virginia.gov/) 

