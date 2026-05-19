# Monitoring the Mangroves of Belize
*Last updated: May 2026*

## Description
This is a [GitHub](https://github.com) repository of resources related to mangrove monitoring in Belize, principally using Earth observation data, and satellite data in particular. This repository will be updated as regularly as is appropriate.

## Objective
The objective of this repository is to maintain a 'living document' regarding the state of mangrove monitoring in Belize. Among other things, mangrove ecosystems factor significantly into the various iterations of the Government of Belize's Nationally Determined Contributions (NDCs) under the Paris Agreement, with the restoration and increased protection of mangroves cited in the most recent version of Belize's [NDC submission](https://unfccc.int/sites/default/files/2025-06/BELIZE%20FINAL%20NDC%203.0.pdf), in addition to a proposal for adoption of a [Belize Mangrove Alliance Action Plan](https://wwflac.awsassets.panda.org/downloads/bma_action_plan.pdf) (GOB, 2025; WWF, 2022). Mangroves also feature prominently in Belize's [Forest Reference Level (FRL)](https://redd.unfccc.int/media/belize_forest_reference_level_report_2024_modified_jan_20_2026.pdf) reports, with mangroves being one of the key forest ecosystems assessed and with the utility of remote sensing to monitoring Belize's forests overall being noted (GOB, 2026). (In terms of general information on Belize's mangroves, there are two [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) articles, one on [coastal mangroves](https://en.wikipedia.org/wiki/Belizean_Coast_mangroves), and another on [reef mangroves](https://en.wikipedia.org/wiki/Belizean_reef_mangroves).)

## Context
To understand the monitoring of mangrove ecosystems in Belize, and particularly the limitations related to such monitoring, it is useful to understand which species of mangrove are found in Belize, and to understand the structural communities they form. More specific to the issue of the limitations related to monitoring mangroves, it is useful to understand the various Earth observation data resources that are available for such monitoring.

## Species of mangrove
As documented in Murray et al. (2003), there are three species of mangroves in Belize:
* **Black mangrove** (*Avicennia germinans*),
* **Red mangrove** (*Rhizophora mangle*), and
* **White mangrove** (*Laguncularia racemosa*).

In Belize, there is also one noted mangrove associate:
* **Buttonwood** (*Conocarpus erectus*).

These are the same species found in other parts of the wider Caribbean region (Rull, 2023), i.e., there are no mangrove species found in other parts of the Caribbean that cannot be found in Belize.

## Types of mangroves: Structural classification
As described by Zisman (1998) and Murray et al. (2003), in terms of actually mapping mangrove communities - mixes of multiple species - those communities can largely be described regarding structural classes, as follows:

* **Mangrove savanna:** Zisman (1999) defines this as follows: "This community occurs mostly in the northern half of Belize. It consists of salt tolerant herbaceous plants with scattered stunted mangroves and buttonwood, a common mangrove associate."
* **Dwarf mangrove** stands: Zisman (1999) defines this as follows: "This is the most widespread type of mangrove, encompassing scrubs less than 3m-4m. These include communities where mangrove is continuous to where it grows at relatively low density."
* **Medium mangrove** stands: Zisman (1999) defines this as follows: "These consist of mangrove thickets and shorter mangrove forests. Their height range is from 3m-4m to 7m-8m high."
* **Tall mangrove** stands: Zisman (1999) defines this as follows: "These areas form mangrove forests and are over 7m-8m high."

It should be noted that across various efforts, mangrove formations have either been mapped as a single class (i.e., mangroves), as the classes indicated above (with some additions, e.g., "mangroves in open water" or "mangroves in mixed forest"). To date, no efforts have been published mapping stands of individual mangrove species.

## Timeline
The following is an abridged timeline of efforts to monitor Belize's mangrove resources in the recent past:

* **1990:** Publication of Gray et al. (1990)'s "Mapping of the mangroves of Belize" technical report.
* **1993:** Publication of Zisman's "Mangroves in Belize: Their Characteristics, Use, and Conservation" technical report, funded as a consultancy under the Forest Planning and Management Project (FPMP) with the Forest Department.
*  **1994:** Publication of Fairweather & Gray (1994), a report and accompanying map of Belize's land cover, which included a mangrove class in its legend. The limitations of the data were later explored in the subsequent Zisman (1998) dissertation.
* **1998:** Publication of Simon Zisman's doctoral dissertation on the status of mangrove ecosystems in Belize (Zisman, 1998).
* **1999:** Dr. Simon Zisman gave a public presentation of the findings of his 1998 dissertation at the Radisson Fort George hotel in Belize, where he released technical notes on the associated mangrove spatial data (shapefiles) that he shared. Zisman's work presented mangrove cover to 1992.
* **2003:** Publication of Murray et al.'s "The mangroves of Belize: Part 1." Notably, a subsequent article was never published by the team.
* **2009:** The Belize Barrier Reef Reserve System (BBRRS) World Heritage Site (WHS) - the country's only UNESCO World Heritage Site - is placed on the UNESCO List of World Heritage in Danger - where it will remain for almost nine years - because of clearing of mangroves within the protected areas making up the World Heritage Site.
* **2010:** Publication of the Cherrington et al. (2010) report, which updated Zisman (1998)'s work using Landsat data for 1980, 1989, 1994, 2000, 2004, 2010.
* **2011:** Validation of the Cherrington et al. (2010) report, via the Cho-Ricketts & Cherrington (2011) effort, which involved field work conducted by multiple Non-Governmental Organizations (NGOs) across Belize. Gregorio Canto's master's thesis, "A study of mangrove deforestation in Belize from Haulover Bridge to the Sibun River" was also published in 2011.
* **2018:** The Cherrington et al. (2018) technical report is completed and indicates that mangrove clearing within protected areas - including the BBRRS WHS - has slowed to almost nill. The findings are used to demonstrate that the Government of Belize has taken strong actions to cease threats to the BBRRS WHS. At the 42nd session of the World Heritage Committee, the decision was taken to remove the BBRRS WHS from the UNESCO List of World Heritage in Danger.
* **2020:** Publication of multiple reports:
  * Cherrington & Griffin (2020) technical report on mangrove change in Belize, funded in the context of Belize's Marine Climate Change Adaptation Project (MCCAP), implemented by the Coastal Zone Management Authority & Institute (CZMAI).
  * Cherrington et al. (2020) paper on mangroves in Belize, a peer-reviewed version of the 2018 technical report, published in the journal *Remote Sensing of Environment*.
  * CATHALAC (2020) technical report on land cover in Belize, which includes mangroves as one of the classes mapped.
* **2021:** Publication of Cissell et al. (2021), which re-mapped mangrove cover across Belize, using Sentinel-2 imagery.
* **2023:** While not focused exclusively on mangroves, in the context of the [now defunct] NASA / USAID SERVIR program, researchers from the University of Alabama in Huntsville (UAH) - namely Emil Cherrington, Betzy Hernandez, Christine Evans and Lauren Carey - delivered a five-day training workshop in Oct. 2023 on forest monitoring using the Google Earth Engine (GEE) platform. One output of that training was the following GEE code repository, which continues to be updated: https://bit.ly/bz_repo.
* **2024:** In late March 2024, the Belize Forest Department hosted researchers from the University of Alabama in Huntsville (Emil Cherrington and Christine Evans) for a short training on the use of remote sensing for mangrove monitoring and some limited field work.
* **2025:** In September 2025, Emil Cherrington & Rob Griffin of UAH presented their preliminary findings of mangrove change in Belize at the National Forest Monitoring System Symposium in Belize City.
* **2026:** The "Spatial Assessment of Total Mangrove Cover for Belize and Change in Mangrove Cover for Belize (2020-2024)" project is being implemented.

## Earth observation data resources
* **Aerial photography:**
  * **Ortho-photos:** Since colonial times (i.e., circa the mid-20th Century), the United Kingdom's Royal Air Force and the Ordnance Survey imaged Belize's territory multiple times, at a high level of spatial detail. The aquisition of [presumably] the first set of aerial photographs led to the "Land in British Honduras" report (White et al., 1959) which documented the territory's natural resources and produced a 1:250,000 scale map. Repeat acquisitions of aerial photography also formed the basis of the development of at least six series of 1:50,000 scale topographic maps of Belize's territory (divided into 44 individual sheets). The last known set of E755 topographic sheets of Belize were released in 1995, with the notation of being "produced under the direction of the Director General of the Military Survey, Ministry of Defense, United Kingdom." The maps' legend also indicates that, although published in 1995, the source aerial photography was from 1988, with "field completion" in 1990. Since various editions of the maps were available, some of the later editions include a specific mangrove class in terms of the various "vegetation" classes depicted, but Zisman (1998) indicated that such depictions were not comprehensive. In terms of the acquisition of aerial photography as a monitoring option, the cost of acquiring aerial photography of Belize - and processing that imagery to [ortho-photos](https://www.esri.com/about/newsroom/insider/what-is-orthorectified-imagery) - is not known.
  * **UAV (drone) imagery:** The last 10-15 years has also seen a surge in the collection of drone imagery of Belize, although it is doubtful that the drone imagery are processed to orthorectified imagery. Major agencies from the Government of Belize with drone capabilities include (but are not limited to):
    * [Belize Coast Guard](https://bcg.gov.bz/)
    * [Coastal Zone Management Authority & Institute (CZMAI)](https://www.coastalzonebelize.org/), and
    * [Forest Department](https://forest.gov.bz/).
* **Satellite imagery:** Given the relative ease of accessing satellite imagery, the relatively low cost (or no cost), the reality that various satellites can provide complete coverage of Belize's territory, and image archives extending in some cases back to the 1970s, compared to aerial photography, satellite images are a compelling option for monitoring Belize's mangrove ecosystems, providing historical as well as more recent snapshots on the status of mangrove extents.
  * **Multispectral:**
    * **Landsat (1972-present):** Multispectral imagery from the NASA / USGS Landsat program - the longest running civilian Earth observation program in the world - has been regularly collected over Belize since 1972. The first three Landsat satellites (i.e., Landsats 1-3) only possessed four spectral bands ranging from green to near-infrared, at a spatial resolution of 60m. The subsequent Landsat satellites (i.e., Landsats 4, 5, 7, 8, 9) possessed six spectral bands ranging from blue to shortwave infrared (with a 30m resolution), in addition to panchromatic and thermal bands, and the most recent two Landsat satellites also possess two additional spectral bands for detecting coastal aerosols and cirrus clouds. The currently operating Landsat-8 and Landsat-9 satellite constellation images Belize's territory every eight days, and the imagery are openly (freely) available. Even prior to the opening of the Landsat archive in early 2008, Landsat imagery factored into multiple efforts related to mapping Belize's mangroves, as well as mapping other vegetation types. Landsat data are also the preferred input for the LandTrendR algorithm and the data off which the algorithm was developed in 2010 (Kennedy et al. 2010). Given that the LandTrendR algorithm is readily available in the GEE platform, LandTrendR has recently been used in multiple studies for mapping mangrove change in Belize (e.g. Cherrington & Griffin 2020, Punalekar et al. 2024, Evans et al. 2025).
    * **PlanetScope (2015-present):** Planet Labs PBC's PlanetScope satellites have been imaging Belize's territory on a ~daily basis since 2015, at a resolution of ~3m. From 2020-2025, under a contract with Norway's Climate and Forest Initiative (NICFI), Planet Labs made monthly wall-to-wall mosaics of the tropics - including Belize - available, with the last monthly mosaic covering January 2025. Mosaics were made available via GEE, as well as for download. Since the expiration of the NICFI Satellite Data Program as it was called, Belize became a beneficiary of a 3-year project under Planet's Project Centinela, whereby PlanetScope and other Planet imagery of roughly half of Belize are being made available to a consortium including the Belize Forest Department. It should also be noted that monthly PlanetScope image mosaics continue to be generated by Planet, but outside of the context of the now expired NICFI Satellite Data Program.
  * **Hyperspectral:** Research indicates that compared to multispectal images, hyperspectral images can theoretically be used to differentiate species. That said, hyperspectral imagery of Belize is generally harder to come by.
    * **EO-1 Hyperion (2001-2017):** While NASA's EO-1 satellite and its Hyperion hyperspectral sensor was in orbit for over a decade and a half, there aren't many Hyperion images of Belize or Belize's coast. Like Landsat data, Hyperion data are available at a 30m resolution.
    * **EMIT (2022-present):**
    * **PACE OCI (2024-present):**
    * **Planet Tanager (2024-present):**
  * **Synthetic aperture radar:**
    * **ALOS PALSAR (2007-present):**
    * **Biomass (2025-present):** While the Biomass mission 
    * **NISAR (2025-present):** 
    * **Sentinel-1 (2014-present):** 
  * **Thermal infrared:**
    * **Landsat (1984-present):** While Landsat-4 (L4) launched in 1982, there are relatively few available L4 scenes available for Belize (see: https://code.earthengine.google.com/scriptPath=users%2Fservirbz%2Fbz_mrv%3A00_misc%2F_count_images%2F01_count_images_bz_belize_city).
    * **MODIS (2000-present):** Given that mangroves occupy relatively small fringers and given that the finest spatial resolution that MODIS data possess are 250m, it is unlikely that those data have the spatial resolution appropriate for monitoring Belize's mangroves.
    * **VIIRS (2012-present):** Given that mangroves occupy relatively small fringers and given that the finest spatial resolution that VIIRS data possess are 375m, it is unlikely that VIIRS data have the spatial resolution appropriate for monitoring Belize's mangroves.

## Methods: Mapping Changes in Belize's Mangrove Cover
It can be considered that there are two general approaches to looking at mangrove cover and mangrove change in Belize. One approach imvolves choosing an existing baseline and then mapping changes from that baseline. That approach, for instance, has been employed by previous evaluations including the various Cherrington et al. assessments, which treat Zisman's original mangrove data as the baseline from which to map change. The other main approach to mapping mangrove cover specifically is what can be considered one-off approaches which seek to map mangroves from scratch and which essentially ignore earlier efforts as they generally do not incorporate previous knowledge on the state of Belize's mangroves. To that point, an assessment by Cherrington & Evans in 2024 found that estimates of mangrove cover vary widely between Zisman (1998), CATHALAC (2020), Cissell et al. (2021), and the Global Mangrove Watch, temporal differences notwithstanding.

## Workflow for mapping mangrove change from a baseline
1. Selection of a baseline dataset for mangrove cover (e.g., Zisman, 1998), from which change will be estimated.
2. Selection of a method and platform for evaluating change (e.g., spectral mixture analysis-based change using CLASlite, or changes in normalized burn ratio estimated using the LandTrendR algorithm based in the Google Earth Engine platform).
3. Selection of [satellite] image data sources appropriate for the method and platform (e.g., Landsat or Sentinel-2 imagery).
4. Selection of a time period for the change to be mapped (e.g., 2020-2026).
5. Selection of the geographic domain (e.g., all of Belize's territory, or the area known to have mangroves on the coast and inland).
6. Execution of the change detection.
7. Extraction of the results [in a geographic information systems format], preferably as polygon data.
8. Review of the results to confirm changes in mangrove cover, including removal of spurious results.
9. Incorporation of the change data into the baseline map.

## Example workflow for mangrove change mapping using Google Earth Engine

1. 

## References

* Bunting, P., Rosenqvist, A., Lucas, R.M., Rebelo, L.M., Hilarides, L., Thomas, N., Hardy, A., Itoh, T., Shimada, M., Finlayson, C.M. 2018. The Global Mangrove Watch—A new 2010 global baseline of mangrove extent. Remote Sensing, 10 (10): 1669. https://doi.org/10.3390/rs10101669

* Centro del Agua del Trópico Húmedo para America Latina y el Caribe (CATHALAC). 2020. The Development of a Land Use Land Cover Map of 2018 Using Sentinel-2 Images under the REDD+ Readiness Project in Belize. Technical report. Forest Department, Ministry of Fisheries, Forestry, the Environment, and Sustainable Development (MAFFESD). Belmopan, Belize. 171 pp.

* Cherrington, E.A., Hernandez, B.E., Trejos, N.A., Smith, O.A., Anderson, E.R., Flores, A.I., and Garcia, B.C. 2010. Identification of Threatened and Resilient Mangroves in the Belize Barrier Reef System. Technical report to the World Wildlife Fund. Water Center for the Humid Tropics of Latin America and the Caribbean / Regional Visualization & Monitoring System (SERVIR). Panama City, Panama. 28 pp. https://www.researchgate.net/publication/257579955_Identification_of_Threatened_and_Resilient_Mangroves_in_the_Belize_Barrier_Reef_System

* Cherrington, E.A. 2013. Baseline assessment of seagrass and mangrove cover and dynamics in the Port Honduras Marine Reserve, Belize. Technical report to the Toledo Institute for Development and the Environment.  Water Center for the Humid Tropics of Latin America and the Caribbean. Panama City, Panama. 13 pp. https://doi.org/10.13140/RG.2.2.10708.91523

* Cherrington, E.A., Griffin, R.E., Anderson, E.R., Hernandez Sandoval, B.E., Flores Cordova, A.I., Muench, R.E., Markert, K.N. 2018. An assessment of changes in mangrove cover across the Belize Barrier Reef Reserve System World Heritage Site: 1996-2017. Technical report. University of Alabama in Huntsville / Belize Audubon Society. Huntsville, Alabama. 24 pp.

* Cherrington, E.A., Griffin, R.E. 2020. Spatial Assessment of Total Mangrove and Littoral Forest Cover for Belize, 2014-2019. Technical report. Coastal Zone Management Authority & Institute (CZMAI) / Marine Conservation & Climate Adaptation Project (MCCAP). Belize City, Belize. 12 pp.

* Cherrington, E.A., Griffin, R.E., Anderson, E.R., Hernandez Sandoval, B.E., Flores Cordova, A.I., Muench, R.E., Markert, K.N., Adams, E.C., Limaye, A.S., Irwin, D.E. 2020. Use of public Earth observation data for tracking progress in sustainable management of coastal forest ecosystems in Belize, Central America. Remote Sensing of Environment, 245: 111798. https://doi.org/10.1016/j.rse.2020.111798

* Cherrington, E.A. 2023. Bibliography - Remote sensing of Forests in Belize. Dataset. http://bit.ly/bz_rs_biblio. Accessed 05/2026.

* Cherrington, E. 2026. Hyperspectral Data Toolkit (Version 1.0.0.6) Computer software. https://doi.org/10.5281/zenodo.18382541

* Cherrington, E. 2026. PACE OCI data Toolkit (Version 1.0.0.6) Computer software. https://doi.org/10.5281/zenodo.18382540

* Cho-Ricketts, L., Cherrington, E.A. 2011. Validation of the 2010 Belize Mangrove Map. Technical report to the World Wildlife Fund. University of Belize, Water Center for the Humid Tropics of Latin America and the Caribbean. Belmopan, Belize. 13 pp. https://www.researchgate.net/publication/283422391_Validation_of_the_2010_Belize_Mangrove_Cover_Map

* Cissell, J.R., Canty, S.W.J., Steinberg, M.K., Simpson, L.T. 2021. Mapping National Mangrove Cover for Belize Using Google Earth Engine and Sentinel-2 Imagery. Applied Sciences, 11 (9), 4258. https://doi.org/10.3390/app11094258

* Environmental Systems Research Institute (Esri). 2016. What is orthorectified imagery? Web page. https://www.esri.com/about/newsroom/insider/what-is-orthorectified-imagery. Accessed 05/2026.

* Evans, C.E., Carey, L.E., Guerra, F., Cherrington, E.A., Correa, E.S., Quintero, D. 2025. Cloud-Based Solutions for Monitoring Coastal Ecosystems and the Prioritization of Restoration Efforts Across Belize. Remote Sensing, 17(20): 3396. https://doi.org/10.3390/rs17203396

* Gorelick, N., Hancher, M., Dixon, M., Ilyushchenko, S., Thau, D., Moore, R. 2017. Google Earth Engine: Planetary-scale geospatial analysis for everyone. Remote Sensing of Environment, 202: 18-27. https://doi.org/10.1016/j.rse.2017.06.031

* Government of Belize (GOB). 2025. Belize's Third Nationally Determined Contribution: NDC 3.0. Ministry of Sustainable Development, Climate Change, and Solid Waste Management. Technical report to the United Nations Framework Convention on Climate Change (UNFCCC). Belmopan, Belize. 128 pp. https://unfccc.int/sites/default/files/2025-06/BELIZE%20FINAL%20NDC%203.0.pdf

* Government of Belize (GOB). 2026. Belize Modified Forest Reference Level (FRL) 2000-2020. Ministry of Sustainable Development, Climate Change, and Solid Waste Management. Technical report to the United Nations Framework Convention on Climate Change (UNFCCC).  Belmopan, Belize. 196 pp. https://redd.unfccc.int/media/belize_forest_reference_level_report_2024_modified_jan_20_2026.pdf

* Kennedy, R.E., Yang, Z., Cohen, W.B. 2010. Detecting trends in forest disturbance and recovery using yearly Landsat time series: 1. LandTrendr — Temporal segmentation algorithms. Remote Sensing of Environment 114: 2897-2910.

* Kennedy, R.E., Yang, Z., Gorelick, N., Braaten, N., Cavalcante, L., Cohen, W.B., Healey, S. 2018. Implementation of the LandTrendr Algorithm on Google Earth Engine. Remote Sensing 10 (5): 691. https://doi.org/10.1016/j.rse.2010.07.008

* Morrissette, H.K. et al. 2023. Belize Blue Carbon: Establishing a national carbon stock estimate for mangrove ecosystems. Science of the Total Environment 870: 161829. https://doi.org/10.1016/j.scitotenv.2023.161829

* Murray, M.R., Zisman, S.A., Furley, P.A., Munro, D.M., Gibson, J., Ratter, J., Bridgewater, S., Minty, C.D., Place, C.J. 2003. The mangroves of Belize: Part 1. distribution, composition and classification. Forest Ecology and Management 174 (1-3): 265-279. https://doi.org/10.1016/S0378-1127(02)00036-1

* Punalekar, S., Canty, S.W.J., Fergus, C., Huang, Q., Songer, M., Nowakowski, A.J., Connette, G.M. 2024. Characterizing the dynamics of mangrove forests in the Mesoamerican reef region using remote sensing methods. AGU Fall Meeting 2024. Poster. Poster No. 158, id. GC51O-0158. https://ui.adsabs.harvard.edu/abs/2024AGUFMGC51O0158P/abstract

* Punalekar, S., Nowakowski, A.J., Canty, S.W.J., Fergus, C., Huang, Q., Songer, M., Connette, G.M. 2025. Characterizing Role of Spatial Features in Improving Mangrove Classification—A Case Study over the Mesoamerican Reef Region. Remote Sensing 17(16): 2837. https://doi.org/10.3390/rs17162837

* Rull, V. 2023. Rise and fall of Caribbean mangroves. Science of the Total Environment 885: 163851. https://doi.org/10.1016/j.scitotenv.2023.163851

* World Wildlife Fund (WWF). 2022. Belize Mangrove Alliance Action Plan: 2022-2027. Belize City, Belize. 38 pp. https://wwflac.awsassets.panda.org/downloads/bma_action_plan.pdf

* Zisman, S.A. 1998. Sustainability or Status Quo: Elite Influence and the Political Ecology of Mangrove Exploitation in Belize. Doctoral dissertation, Department of Geography, University of Edinburgh. Edinburgh, Scotland. 277 pp. https://www.era.lib.ed.ac.uk/bitstream/handle/1842/22768/ZismanS_1998redux.pdf

## Acknowledgements

This effort was funded through a 2026 collaboration with the Forest Department of the Government of Belize's Ministry of Sustainable Development and Climate Change, MSDCC) (Professional Service Contract no. 114 of 2025/2026). This work builds off of multiple projects previously funded by (in chronological order): the Smithsonian Institution's Healthy Reefs Initiative, the World Wildlife Fund's Mesoamerican Reef (MAR) program, the Toledo Institute for Development and the Environmeng (TIDE), the Belize Audubon Society and the United Nations Development Programme (UNDP) / Global Environment Facility-Small Grants Programme (GEF-SGP), the Coastal Zone Management Authority & Institute (CZMAI) and the Marine Climate Change Adaptation Project (MCCAP). The following individuals at the Belize Forest Department were instrumental to the recent effort: Florencia Guerra (Sustainable Forest Management Program lead), Edgar Correa (Monitoring, Reporting, and Verification lead and current Ph.D. student at Kyushu University), Minerva Gonzalez (Restoration Program lead), Koren Sanchez, Karlene Williams, Anthony Morgan, Wilber Sabido (former Chief Forest Officer), and John Pinelo (current acting Chief Forest Officer).

## Contact information

If you have any questions, feel free to contact Emil Cherrington by :envelope_with_arrow: email: **emil.cherrington [at] uah.edu**.
