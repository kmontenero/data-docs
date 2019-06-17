Worldview data is sourced from both Digital Globe and The Polar Geospatial Center.
Data is from worldview-2 & worldview-3 satellites.

Worldview imagery is separated into regions.
The FL regions are based on [USGS FCMaP regions](https://www.usgs.gov/media/images/florida-regions).
The rest of the Gulf of Mexico coast was divided into similarly-sized regions by @cestes :

## Regions from west to east: 

I broke up Texas at Corpus Christi-Galveston (SW Texas), Galveston-Port Arthur (Central Texas), and Port Arthur-Louisiana (NE Texas). 
Louisiana was broken up at Lafayette (W Louisiana and E Louisiana). 
Mississippi and Alabama are only one polygon each. 
I followed the FCMaP guidelines for Florida: Alabama-Tallahassee(Florida Panhandle), Tallahassee-Hernando Beach (Big Bend), Hernando Beach-Monroe County (SW Florida), Monroe County-Miami (Monroe), Miami-Melbourne (SE Florida), and Melbourne-rest of the images (NE Florida).

Each area has two layers (ex. Alabama and AL). 
The label with the state abbreviation (AL) is just the polygon. 
The other one has all the images in them. All the directions are abbreviated for each label except Central Texas (NE, SE etc.)

ArcGIS exports the tables as xls files so I converted them to csv (folder) and made a large workbook with all the regions combined (All_regions).

I have saved the ArcMap (Gulf_Coast_Polygons) and csv for each region on labshare at  `\\yin.marine.usf.edu\lab_share\cestes\WV_data`

Let me know if we need to change anything.
