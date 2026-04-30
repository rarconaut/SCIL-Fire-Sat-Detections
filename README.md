# SCIL-Fire-Sat-Detections
## Satellite-Based Active Fire Detections (VIIRS/MODIS/GOES)

Organization:
SCIL-WIFIRE

Creator Name:
Rawaf al Rawaf

Last Updated:
April 30, 2026 at 7:00 PST

These Jupyter Notebooks allow users to view and download satellite heat detections from the UC San Diego Societal Computing and Innovation Lab's WIFIRE Program using the Firemap Geoserver API. The user must select one of the satellite source notebooks (VIIRS, MODIS, OR GOES) and then specify a coordinate bounding box, start datetime, and end datetime. Executing the entire PYNB notebook returns a JSON and downloads JSON, CSV, and/or zipped Shapefile of the features, including the geographic coordinates and timestamps for fire hotspot detections corresponding to the user-defined parameters.

Instructions
The user must select one of the satellite source notebooks (VIIRS, MODIS, OR GOES) and then specify a coordinate bounding box, start datetime, and end datetime.

Objectives
Generate time lapse videos of satellite detections using the AIC:W virtual constellation.

IMPORTANT: 
- The first available VIIRS detection starts from 2016-08-11T09:20:00Z.
- The first available MODIS detection starts from 2017-05-20T21:35:00Z.
- The first available GOES detection starts from 2021-01-20T18:00:25Z, with the majority of coverage in southern California and Arizona.

Data and Resources
- Satellite Detections Retrieval - Jupyter Notebooks
- Satellite Detections Retrieval GitHub Repository: https://github.com/rarconaut/SCIL-Fire-Sat-Detections/tree/main

Tags
hotspots

Firemap

Geoserver

nasa

satellite

viirs

modis

goes

wildfire

