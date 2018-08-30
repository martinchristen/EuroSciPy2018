# EuroSciPy 2018

This repository contains the Jupyter Notebook for my EuroSciPy 2018 Tutorial "Handling Geospatial Data using Python, Part I: Base Modules"

## About

The following modules will be covered:

* Shapely - Manipulation and analysis of geometric objects
* Fiona - The pythonic way to handle vector data
* rasterio - The pythonic way to handle raster data
* pyproj - transforming spatial reference systems
* Creating maps using Basemap & Folium

## Installation

It is assumed Anaconda 5.2 is installed (Python 3.6)

    conda install shapely
    conda install fiona
    conda install rasterio
    conda install geopandas
    conda install folium -c conda-forge
    conda install basemap -c conda-forge



Also make sure Jupyter is installed. We will use jupyter lab for this tutorial.


## Binder

Binder can also be used for this tutorial. [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CharcoalStyles/EuroSciPy2018/master)

Once launched, run the _BinderNotebook.ipynb_ notebook.

Be aware, the dependencies do take a while to download and install.

