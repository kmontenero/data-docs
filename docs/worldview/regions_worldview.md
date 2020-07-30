Worldview data is sourced from both Digital Globe and The Polar Geospatial Center.
Data is from worldview-2 & worldview-3 satellites.

Worldview imagery is separated into regions.
The FL regions are based on [USGS FCMaP regions](https://www.usgs.gov/media/images/florida-regions).
The rest of the Gulf of Mexico coast was divided into similarly-sized regions by @cestes :

## Regions from west to east: 

![screencap](https://github.com/7yl4r/data-docs/blob/master/docs/worldview-regions.png?raw=true)

### Texas 
* texas_sw: Corpus Christi->Galveston 
* texas_central: Galveston->Port Arthur
* texas_ne: Port Arthur->Louisiana
### Louisiana split at Lafayette 
* louisiana_w 
* louisiana_e
### Mississippi only one polygon
* mississippi
### Alabama only one polygon
* alabama
### FCMaP guidelines for Florida
* fl_panhandle: Alabama->Tallahassee
* fl_big_bend: Tallahassee->Hernando Beach 
* fl_sw: Hernando Beach->Monroe County 
* fl_monroe: Monroe County->Miami 
* fl_se: Miami->Melbourne 
* fl_ne: Melbourne->GA

Each area has two layers (ex. Alabama and AL). 
The label with the state abbreviation (AL) is just the polygon. 
The other one has all the images in them. All the directions are abbreviated for each label except Central Texas (NE, SE etc.)

ArcGIS exports the tables as xls files so I converted them to csv (folder) and made a large workbook with all the regions combined (All_regions).

I have saved the ArcMap (Gulf_Coast_Polygons) and csv for each region on labshare at  `\\yin.marine.usf.edu\lab_share\cestes\WV_data`

Let me know if we need to change anything.
