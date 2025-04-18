# Lake Area Monitoring Sentinel 2
This repository contains code for monitoring the change in lake area over time using MODIS satellite imagery(500m spatial resolution). The project analyzes the Normalized Difference Water Index (NDWI) from MODIS data to track the variation in lake area from 2000. The workflow includes the use of Google Earth Engine for satellite data processing, xarray for managing and visualizing data, and KMeans clustering for identifying water and non-water areas. The results are visualized through annual lake area maps and area calculations.



## Project Overview
The purpose of this project is to analyze the temporal changes in lake area, helping researchers and environmentalists understand the impact of climate change, human activity, and other factors on water bodies. By calculating NDWI over the years, the code extracts the water body and uses clustering to differentiate between water and non-water areas. The analysis then computes the lake area on an annual basis and visualizes these changes.



## Example Outputs
Lake Area Visualizations: Uromia Lake (2000 to 2024)
This project visualizes the annual change in the area of Uromia Lake (or any specified lake) over the years, from 2000 to 2024. The NDWI (Normalized Difference Water Index) is used to identify the water body, and the KMeans clustering technique is applied to differentiate between water and non-water areas.

![image alt](https://github.com/SaeidDaliriSusefi/Lake-Monitoring-Modis/blob/93f692f3a74ce9533a79dca36b00ba9e73c87ac3/Images/urmia%20lake_Area.png)
