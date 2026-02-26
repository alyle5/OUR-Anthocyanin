# OUR-Anthocyanin
----------------------------Code repository for OUR Anthocyanin research-------------------------------------------------------- 

------------All files are tools that have been used to analyze the Geo-spatial Data in this project-----------------------------

---------------------------------All files are date sensitive----------------------------------------------------------------

B5_mARI_ARI_S2_Pull.txt---This should be pasted into Google Earth Engine to pull mARI-ARI and Redness Sentinel-2 reflectance from the study area, incorporating Band 5 for band calculations

ARI_mARI_Redness_distribution.ipynb---This rasterio py script from Dr.Liu classifies ARI-mARI-Redness values by NLCD classes, analyzes and outputs statistics

ARI_mARI_redness_by_Aspect_1_NLCD---This rasterio py script, edited from Dr.Liu's script, takes aspect values from aspect slope and classifies them into their direction, it then extracts ARI values from NLCD classes across these aspects, outputting statistics. 

Raster_calc---This is a straight forward ArcPy ArcGIS script that uses the raster calculator functions to create conditonals,revealing and masking pixels based on NLCD, Aspect and ARI.

yao_li_autotool.py----This is the py script for Dr.Yao-Li's ArcGIS auto tool that takes raster layers and inputs them into a fishnet over the study are.
