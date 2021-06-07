# About

How to run Notebook:

This notebook is ran on a pangeo-binder. To run click the link below:

[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=AWS+us-west-2&color=orange)](http://binder.pangeo.io/v2/gh/ted80810/optimal_fish_temperature_pangeo/HEAD)

For a quick view of this notebook click on the link below to view with nbviewer:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/ted80810/optimal_fish_temperature_pangeo/blob/master/Optimum_Temperature_forAngling_Bonefish.ipynb)

This notebook is ran on a pangeo-binder. To run click the link below:
Water temperatures dominate bonefish (Albula spp.) movements and feeding patterns in coastal flats. 
For this project, I will be utilizing the Pangeo ecosystem tools to visualize 
Multi-Scale Ultra High Resolution (MUR) Sea Surface Temperature (SST) grids around the Marls, a popular 
catch and release angling site, in Abaco, Bahamas. Bonefish angling tournaments and eco-tourism are a 
significant contributor to the local community in the Bahamas. Since bonefish are ectothermic, they are 
highly sensitive to temperature changes in their environment and respond to these changes. Bonefish 
rarely occupy areas that exceed their critical temperature 28ºC. In addition, little is known about how 
bonefish will respond to increasing sea temperatures. Studies show that even minor increases in optimal 
temperature and critical temperature will negate access to feeding areas. This translates to less Bonefish 
migrating into tidal creeks and thus affecting the local economy. This Jupyter Notebook will demonstrate 
the value of reproducible, cloud-based notebooks by analysing open-access oceanic data with economic value 
to the Bahamian community. The notebook will use tools from the Pangeo ecosystem (like xarray, dask, zarr) 
to access the MUR dataset from the AWS public dataset program, and subset data to the Marls region and 
compare data from past angling events. Using xarray, this notebook will identify optimal temperature grids 
throughout the Marls and visualize differences in sst from past angling tournaments. It will also test sea 
surface temperature forecast for the Marls region using publicly available operational forecasts like the 
NOAA High Resolution Rapid Refresh Model (available on AWS) and the Fleet Numerical Meteorology and 
Oceanography Center (FNMOC) global-scale operational ocean prediction system (available from NCEI). The final 
executable notebook can be a valuable asset to the local eco-tourism community providing access to a large 
public dataset and scientific analysis compatible with their business.
