# Simple Change Detection using Jupyter, TERN web services and Google Earth Engine

## Abstract

Will your research use a time series of satellite images for change detection? 
Do you want to see Python and Jupyter Notebook in action? 

This notebook demonstrates using Python and Jupyter Notebooks to access a time-series of Landsat images via TERN web services and the Google Earth Engine and to detect changes over time.

## Presentation Outline

This notebook will outline some simple online interaction with some of the **JRSRP Landsat seasonal mosaics** as well as with the **Google Earth engine** for a comparison of techniques.  There are of course other online systems, one of the major ones in Australia at the moment is the [open data cube](https://github.com/opendatacube) project which I hope to cover in a future example.

We'll treat the data hosted on http://qld.auscover.org.au as files and use the [RasterIO](https://www.mapbox.com/blog/rasterio-announce/) package to interact with the data and undertake some typical remote sensing tasks. 
Will then have a look at setting up the Google Earth engine in the python environment and run through some simple visualisation examples. The Google Earth engine has extensive online documentation and training and I would encourage anyone interested in Earth observation to sign up and explore this service.

In these examples will be looking at changes between imagery collected at two different dates. There are many different ways of comparing imagery, typically you would want to run some sort of image classification approach which can be easily done but is beyond the scope of this initial "how to" notebook.  
