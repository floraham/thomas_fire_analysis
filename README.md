## Title: Thomas Fire Data Analysis: Visualizing the Thomas Fire's Burn Scar and AQI impacts 
#### Author: Flora Hamilton, Master of Environmental Data Science 
#### Link: https://github.com/floraham/thomas_fire_analysis

This repository contains a Jupyter Notebook (.ipynb) using Python to visualize the Thomas Fire's Burn scar and AQI impacts in Santa Barbara, CA. We use three datasets to conduct this analysis (two for the burn scar visualization, one for AQI). 

#### 1) Burn Scar Data 

##### **First dataset:** 
- A simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite. 
-  The data was accessed and pre-processed in the Microsoft Planetary Computer to remove data outside land and coarsen the spatial resolution ([Landsat Collection in MPC](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)). 

##### **Second dataset:** 
- A shapefile of fire perimeters in California during 2017. 
The [complete file can be accessed in the CA state geoportal](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about).

#### 2) AQI Data

- We use [Air Quality Index (AQI)](https://www.airnow.gov/aqi/aqi-basics/) data from the [US Environmental Protection Agency](https://www.epa.gov) to visualize the impact on the AQI of the 2017 [Thomas Fire](https://en.wikipedia.org/wiki/Thomas_Fire) in Santa Barbara County. 
