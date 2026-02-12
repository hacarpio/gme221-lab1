# GmE 221-Laboratory Exercise 1
## Overview
This laboratory sets up a spatial analysis environment using Python and PostGIS and performs a parcel-landuse overlay analysis. 

## Environment Setup
-Python 3.x
-PostgreSQL with PostGIS
GeoPandas, SQLAlchemy, psycopg2

# How to Run
Activate the virtual environment 
 Run `main.py` to test the database connection 
Run `overlay.py` to compute landuse percentages

## Outputs
PostGIS table: `parcel_landuse_percentage` - Visualization in QGIS

## Reflection: Interpreting Algorithm Output 
-Spatial overlay and area computations have already been completed in PostGIS. 
-QGIS is displaying the results of those computations
-Each feature represents a spatial relationship between parcels and landuse polygons

## Considering the following 
-Do the percentages make sense given the parcel shapes? Data Validation: Parcel vs Percentage: The percentage assigned to each parcel are derived from the parcel area,  the parcel appears due to map projection--geom--.  
-And yes the percentage make sense relative to the visual shapes and utilize the land use name for specific parcel geometry. 
-Based on my visualization the parcel no data holes " donuts"  

## Required Commit- Visualization and Interpretation Milestone 
-Save the QGIS project file lab1.qgz if created in the folder "C:\Users\Honeylyn\Desktop\GmE 221 Spatial Analysis\gme221-lab1\output/

