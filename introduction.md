# Inroduction to the Scripting


---

## Why to use Scripting

+ Automate QGIS geoprocessing tasks

+ Perform geoprocessing tasks

+ Access datasets to test for a condition

+ Create tools/plugins to share your python scripts

---

## Creating custom tools

Custom tools become an integral part of geoprocessing, just like system tools.

---

## Why create your own tools?

+ System tools are designed to perform one small but essential operation on geographic data.

+ Using scripting you execute these tools in a sequence, feeding the output of one tool to the input of another.

+ The model or script you create may be an essential part of your workflow—a task you need to repeat again and again

+  You can build your own library of tools that perform small but essential tasks for your organization.

---
# What is script

+ A script can be defined as a set of instructions in plain text, stored in a file and carried out by a software program, specifically a scripting application program.

+ Each scripting application has its own language, and not all scripting languages can be used to write scripts for geoprocessing

---

# Importance of Script

+ Scripts are similar to models in that they allow you to chain processes together to run more efficiently, and to document and share your methodology with others.

+ Scripts can also add functionality that is not available from the standard system tools.

+ Programming is used with many goals in mind, whether it is automating geoprocessing tasks or implementing an algorithm for all sorts of tasks, programming goes a long way in problem solving. It helps us tackle those tasks which require a different degree of operations, where the problems we are facing need some specific manipulation that is not provided.

+ This is one of the reasons why many GIS software allow access to API for customizing the application according to your specific needs.



---
# Example use of scripts

+ Batch processing of your data. Scripts can loop through multiple datasets performing the same operation on each dataset, such as projecting all shapefiles in a folder or all feature classes in a geodatabase.

+ You can also write your scripts to process based on certain conditions. For instance, a script can check to see if the input data is a line or a polygon feature class and then process the data accordingly.

---

# Scripting Languages used in GIS

## Python

+ Python has become one of the most important languages used in the field. How so? It is easy to learn, thanks to having an outstanding documentation and easy to pickup syntax, plus the variety of tutorials available online for free. Moreover, there is a great support for data analysis and processing through the likes of Numpy or Pandas.

+ Python is incorporated into ArcGIS, QGIS, GRASS GIS, gvSIG, and many other open source projects, that make the language worth knowing.  At the same time, there are quite a few libraries Shapely, Fiona and Rasterio, Folium, and many others that appeared in the past couple of years.

+ Python can be compared to as the swiss army knife for GIS.


---

## Essential Python Geospatial Libraries
| Library  | Use  |
|---     |---   |
| geopandas | Working with spatial data is fun again! |
|shapely | For geometry handling |
|rtree  | For efficiently querying spatial data|
|geographiclib | For solving geodesic problems |
|pyshp | For reading and writing shapefiles (in pure Python) |
|pyproj | For conversions between projections |
|rasterio | A Pythonic way to work with geospatial rasters |
|fiona | For making it easy to read/write geospatial data formats |
|ogr/gdal | For reading, writing, and transforming geospatial data formats |
|pyqgis | For anything and everything GIS |
|geopy | For geolocating and things like that |
|geojsonio.py | For shooting data to the web |
|geog | For a numpy interface to solve geodesic problems |
|h5py | Your pythonic gateway to hdf5 files |
|pyModis | Download and preprocess MODIS data |
|pyspatial | projection aware querying of vector/raster data |

https://github.com/SpatialPython/spatial_python/blob/master/packages.md

---
## Data Analysis Libraries
| Library  | Use  |
|---     |---   |
|scipy | General scientific computing library. Has a spatial module |
|scikit-image | Algorithms for (satellite) image processing |
|scikit-learn | Machine learning for python |
|statsmodels | For models and stats in Python |
|pysal | Spatial econometrics, exploratory spatial and spatio-temporal data analysis, spatial clustering (and more)|
|networkx | For working with networks |
|rasterstats | For analyzing rasters based on vector geometries (zonal statistics) |


---
## Plotting/Mapping

| Library  | Use   |
| ---      | ---   |
|matplotlib | For all my plotting needs |
|cartopy | For plotting spatial data on projections and more |
|folium | Python Data. Leaflet.js Maps |
|nodebox-opengl | For playing around with animations |
|descartes | For plotting geometries in matplotlib |
|basemap | For plotting geospatial data on projections |
|mplleaflet | For creating web-maps |

---

## R for Geo Processing

The language for statistical computing, graphics, data science, and
geospatial analysis.

You can also get R in QGIS as well, so no more worries that you’ll have to run your scripts elsewhere. Thanks to this there are pretty good signs that R will play an important role in the years to come.


URL for R packages : https://cran.r-project.org/web/views/Spatial.html
