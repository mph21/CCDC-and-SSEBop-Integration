This folder contains the Python scripts required for access CCDC data, generate synthetic Landsat data, and then run SSEBop to get actual evapotranspiration (ETA) estimates. Finally, there is an R script to show the visualization of the CCDC and LANDSAT data comparisons. 

1.	Run Coloardo_LST_ETA in a SSEBop virtual python environment to generate ETA estimates for a given X, Y point in EPSG 5070 and the .csv file of Landsat IDs required for Auto_Colorado_Forest.ipynb.

2.	Make sure the three functions .ipynb files are in the same USGS Virtual Desktop Environment folder as Auto_Colorado_Forest.ipynb before running in the virtual CCDC python environment. 

3.	Run Auto_Colorado_Forest.ipynb for desired X, Y point

4.	Upload resulting CCDC raster files to Google Earth Engine

5.	Run Colorado_CCDC_ETa.ipynb on the CCDC data in Google Earth Engine to produce ETA estimates. 

6.	Visualize the results in Six Panel ETA.rmd
