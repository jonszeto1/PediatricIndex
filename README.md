The two files in this respository were used to generate the land surface temperature anomaly and climate change projections datasets used in this research project. The code was used in Google Earth Engine. For these codes, shapefiles need to be imported for the ROI. The Climate Gridded Normal Dataset from NOAA also needs to be imported for the code to run (https://www.ncei.noaa.gov/products/land-based-station/us-climate-normals)


Climate_Mid_Late_Delta_projection: This code generates a raster dataset of the "delta" or difference in temperatures on a 1km basis across the contiguous United States between the moderate (RCP4.5) and high emission (RCP8.5) scenarios in both the mid and late century.  


LandSurfaceTemperature_Raster_Generation: This code generates a raster dataset of a 1 km spatial resolution of the number of days in which the Maximum Temperature is greater than Climate Normal across the contiguous United States from 2012-2024 during the summer months. Datasources used was the LST dataset from MODIS and land surface temperature dataset from NOAA.
