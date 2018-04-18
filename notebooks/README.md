# Summary

This directory contains the 4 Jupyter notebooks that were used for this project. In addition, it also contains the **NY_neighborhoods.geojson** file that has the boundaries of all NYC neighborhoods.

# Notebooks

**01_neighborhood_mapping.ipynb**

* Used to add neighborhoods from latitude and longitude coordinates for all Uber and Citibike rides, as well as MTA subway stations.

**02_uber_pickup_timeseries.ipynb**

* All the timeseries-only analysis and baseline models are in this notebook.

**03_neighborhood_forecasting.ipynb**

* This notebook adds the citibike and MTA subway data to the Prophet model from the previous notebook. In addition, it dives into the specific neighborhoods to analyze increases and decreases in accuracy of neighborhood-level forecasts. 

**04_creating_additional_regressors.ipynb**

* This notebook creates the additional regressors in a format that can be used by the previous notebook.