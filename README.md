# BoundaryLayerAnalysis
Investigating the differences in boundary layer behavior between dry and wet days using observational datasets. Includes data processing and time series analysis

# Boundary Layer Time Series Comparison: Dry vs. Wet Conditions

This repository contains a Jupyter Notebook (`Investigating Boundary Layer Variation.ipynb`) that performs a time series analysis of atmospheric boundary layer (ABL) characteristics, specifically comparing a selected dry day with a wet day. The goal is to visualize and understand how moisture influences the temporal evolution of key meteorological variables within the ABL.

**Project Overview:**

The notebook processes a combined meteorological dataset (likely using the xarray library) to extract and compare time series of:

* Air Temperature
* Wind Speed and Direction (U and V components)
* Dew Point Temperature
* Boundary Layer Height 

The analysis focuses on a user-defined dry day and a contrasting wet day, generating plots to visually highlight the differences in these variables throughout the day.

**Contents:**

* `Investigating Boundary Layer Variation.ipynb`: The Jupyter Notebook containing the Python code for data loading, processing, and visualization.

**Key Steps in the Notebook:**

1.  **Data Loading and Preprocessing:** Loading the meteorological dataset and preparing it for analysis (likely using xarray).
2.  **Dry/Wet Day Selection:** Identifying and subsetting the data for a specific dry day and a specific wet day.
3.  **Variable Extraction:** Extracting the time series data for the key meteorological variables mentioned above.
4.  **Visualization:** Generating time series plots (using matplotlib) to compare the evolution of each variable on the dry and wet days.

**Python Libraries Used:**

* [xarray](http://xarray.pydata.org/en/stable/): For handling multi-dimensional meteorological data.
* [matplotlib](https://matplotlib.org/): For creating informative time series plots.
* [pandas](https://pandas.pydata.org/): May be used for data manipulation and time series handling.
* [numpy](https://numpy.org/): For numerical operations.


**Potential Extensions:**

* Analyze more dry/wet day pairs.
* Calculate and compare statistical properties of the time series (e.g., mean, variance).
* Investigate the relationship between different variables on dry versus wet days.
* Add interactive visualizations.

Eugene Jamil Asante
