# Spatiotemporal-Analysis-of-Malnutrition-and-Vegetation-Change
## Project Overview
### This project explores the evolving relationship between malnutrition and environmental conditions in East Africa using spatiotemporal analysis and geospatial techniques. By examining trends in malnourished populations and vegetation health (NDVI) in 5-year intervals, working backward from 2020 to 2000, we aim to identify regional disparities and environmental patterns that contribute to food insecurity. This focused approach will support targeted insights for food security planning and climate adaptation efforts.

#### Research Questions

1.)How have malnourished population rates varied by region over each 5-year period from 2020 to 2000?

2.) How do changes in vegetation health (measured by NDVI) correspond with patterns of malnutrition across regions and time?

####  Objective

1.) Visualize the spatial distribution of malnourished populations by year and region.

### Data Sources
This project integrates multiple datasets related to famine occurrences and climate patterns:

##### Climate Data from:

- NOAA Climate Data
- FAO Climate & Agriculture Data
- Dryad Climate Dataset

##### NDVI (Vegetation Index): 

- MODIS Vegetation Indices (MOD13Q1)

##### Famine Occurrence Data from:
- FEWS NET 
- FAO Food Security Indicators 
- Humanitarian Data Exchange (HDX)

##### Geospatial Data (country boundaries, admin regions) from:

-Natural Earth

### Tools & Technologies

This project leverages Python and GIS tools for data processing, mapping, and analysis:

##### Programming & Data Processing:

- pandas, numpy, geopandas (for data handling)
- matplotlib, seaborn, folium (for visualization)

##### Geospatial Analysis:

- GeoPandas, Shapely, rasterio (for GIS operations)
- QGIS, Google Earth Engine, ArcGIS (for spatial mapping)
