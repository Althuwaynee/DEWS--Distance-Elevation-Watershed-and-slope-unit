# DEWS (Distance, Elevation, Watershed and Slope unit) Rain gauge selection tool for rainfall threshold analysis
 
To automatically select the rain gauges around landslide inventory using geomorphological and hydrological relationships. 

. Developed by: Omar AlThuwaynee


## Required Software
QGIS software v.3.9, 3.10, 3.11




--------------------------------


# DEWS: a QGIS tool pack for the automatic selection of reference rain gauges for landslide-triggering rainfall thresholds

Omar F. Al-Thuwaynee , Massimo Melillo, Stefano Luigi Gariano | Research Institute for Geo-Hydrological Protection IRPI, Italian National Research Council, Perugia, Italy
Hyuck Jin Park, Sang-Wan Kim, IT Hwang | Department of Energy and Mineral Resources Engineering, Sejong University, Korea
Luigi Lombardo | Department of Earth Systems Analysis (ESA), University of Twente, Enschede, Netherlands
Paulo Hader | Department of Civil Engineering, São Paulo State University, São Paulo, Brazil
•Meriame Mohajane | Department of Biology, Université Moulay Ismail, Meknès, Morocco
•Renata Pacheco Quevedo | Earth Observation and Geoinformatics Division, National Institute for Space Research, São José dos Campos, Brazil
•Filippo Catani | Department of Geosciences, University of Padova, Padova, Italy
•Ali Aydda | Department of Geology, University Ibn Zohr – Agadir, Agadir, Morocco
--------------------
 
## Abstract

Several regional-scale landslide early warning systems are based on empirical rainfall thresholds for landslide triggering. The calculation process of such thresholds, mainly using rainfall measurements gathered from rain gauges, has been examined frequently, especially by focusing on selection of rain gauges, modeling uncertainties, modeling complexity, spatial assumptions, and analytical tools. In literature, the selection of reference rain gauges is mostly based on the nearest distance location using statistical or manual procedures, without considering the morphological and hydrological settings of the area in which landslides occurred. In this study, by considering the spatial relationship between landslide and rain gauges that might be used to construct the rainfall events responsible for landslide events, thus, we introduce an automatic tool named, DEWS (Distance, Elevation, Watershed, and Slope unit), designed for the purpose of selection the rain gauges representative for rainfall-induced landslides. The output information, i.e. the list of selected reference rain gauges, later can be used as inputs to any landslide-triggering rainfall thresholds model. Specifically, the tool allows for the extraction of rain gauges referring to landslide locations by employing four spatial filters: F1 (Distance), F2 (Elevation), F3 (Watershed), F4 (Slope unit), and requiring 3 data inputs only (DEM, the landslides inventory and rain gauge locations) besides, a set of parameters for each filter. DEWS was implemented in a free tool pack in QGIS software, with default parameter values for non-expert users. To deliver a comprehensive application of DEWS to readers, it  presented here as supplementary and complementary to the CTRL-T tool, (Calculation of Thresholds for Rainfall-induced Landslides Tool), and that to fill the function of “ macro-to-micro scale” rain gauge selections for CTRL-T. The reliability of DEWS spatial selection procedure was tested using 223 landslides and 328 rain gauges in South Korea at a regional scale. Then, as a second step, frequentist rainfall thresholds were calculated. Results of using 10 sets of filter-no filter combinations, testing all the filters with different values, showed an improvement of the rain gauges selection by 33% using DEWS (393 to 266 stations) from using CTRL-T alone, while the shape of the threshold curve was maintained. The current findings confirmed the need to incorporate topographical, hydrological and geomorphological relationship between landslide and reference rain gauges in selection criteria, rather than merely focus on closest distance and quantity of rain gauges.

Keywords:
Open source, QGIS, LEWS, threshold, landslide, toolpack, south korea


