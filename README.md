# Advanced-Databases
Learn to Use a Spatial Database 

High-level Description :
We have a dataset which consists of a New York State data. The dataset has many shape files in .shp format. 
We used SpatialLite software to create the database and load the shape files into it in order to perform the queries to it.
Once the data has been uploaded to a SDBMS then we used QGIS software to visualize and for graphical interface for this project.
Using the graphical interface we were able to show the different objects and locations, find distance from one point to another
or compute the area of an object and various other tasks. The dataset we are using consists of the following files:

 nyc_census_blocks.dbf
 nyc_census_blocks.prj
 nyc_census_blocks.shp
 nyc_census_blocks.shx
 nyc_homicides.dbf
 nyc_homicides.prj
 nyc_homicides.shp
 nyc_homicides.shx
 nyc_neighborhoods.dbf
 nyc_neighborhoods.prj
 nyc_neighborhoods.shp
 nyc_neighborhoods.shx
 nyc_streets.dbf
 nyc_streets.prj
 nyc_streets.shp
 nyc_streets.shx
 nyc_subway_stations.dbf
 nyc_subway_stations.prj
 nyc_subway_stations.shp
 nyc_subway_stations.shx
 pagila.backup
We considered the data present in the NYC dataset folder. 
We used QSpatialLite plugin to execute the queries and get the output in tabular format as well as in spatial view or spatial table to represent the output
on map i.e., on QGIS Desktop, we select “Create Spatial View & Load in QGIS” to display the polygons objects and
"Create Spatial Table and Load in QGIS" to display line and point objects.
