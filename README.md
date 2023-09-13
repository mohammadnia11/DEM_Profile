## Introduction

This project provides a Python-based tool for analyzing Digital Elevation Models (DEMs). It reads DEM data from a .tif file, displays the elevation model using a 2D plot, and allows users to input two geographic coordinates (latitude and longitude). The tool then computes an elevation profile between the two points and plots it.
Features

    Read DEM data from .tif files
    Visualize DEM data using matplotlib
    Convert geographic coordinates to row and column indices in the raster
    Generate elevation profiles between two geographic coordinates
    Compute geodesic distance between two points

## Dependencies

    rasterio: For reading raster files (.tif files)
    numpy: For numerical operations
    matplotlib: For plotting and visualization
    geopy: For distance calculations

To install all dependencies, you can run:

bash

pip install rasterio numpy matplotlib geopy


## Download DEM
**Link:** 
https://appeears.earthdatacloud.nasa.gov/task/area

Navigate to the folder containing the dem_analysis_tool.py file.

Run the Python script:

bash

    python dem_analysis_tool.py

    The script will prompt you to enter the latitude and longitude of two points. After entering these, a 2D plot of the DEM and an elevation profile will be displayed.

Contributing

Feel free to fork the repository, create a pull request, or submit issues and feature requests.
