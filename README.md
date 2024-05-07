# NR 427 Final Project
## Eileen McGinnity - May 6, 2024

The purpose of this project is to investigate the safety of Colorado's jurisdictional dams. A jurisdictional dam is a dam large enough to pose a threat to human life and/or cause damage, should the dam break. Colorado's Department of Water Resources (DWR) Decision Support Systems inspect these dams and reports on the hazard level. The hazard levels are defined as follows:

* High: high chance of deaths and widespread damage if one of these dams break.
* Significant: no deaths expected, but significant damage will occur if one of these dams break.
* Low: no expected deaths, but some non-critical infrastructural damage expected.
* No Public Hazard (NPH): the public should not be directly affected by a dam break.

The main tasks of this notebook are:
Importing libraries and data; setting up paths
* Editing/cleaning data
* Creating pie charts to display data
* Performing buffers and spatial joins
* Creating an interactive folium map

Dam data from the DWR's Decision Support System was used to filter data, calculate dams per hazard level and per county, plot locations on a map, and perform buffers around the locations. The Colorado State Demography Office's 2020 census tract data was used to calculate statistics on how many people would be affected by a dam break of each hazard level within a 10 mile radius. Colorado Department of Local Affairs' county boundary shapefile was used to display popups for each county on the interactive map.

This notebook only uses open source python libraries.

TWO NOTES BEFORE RUNNING:
1. Remember to change the main_path to the location where this file is saved.
2. kaleido version 0.1.0 is required. This is NOT the latest version; use the code included in the notebook to install.
