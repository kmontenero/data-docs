This is a list of the requests put in to CAD4NASA in reverse chronological order

## 2020-04 Rookery Bay NERR
```
 From: druedaro@usf.edu <druedaro@usf.edu>
Sent: Thursday, April 8, 2021 1:31 PM
To: Nickeson, Jaime (GSFC-618.0)[SCIENCE SYSTEMS AND APPLICATIONS INC] <jaime.nickeson@nasa.gov>; Wagner, William C. (GSFC-618.0)[SCIENCE SYSTEMS AND APPLICATIONS INC] <william.c.wagner@nasa.gov>; Neigh, Chris (GSFC-6180) <christopher.s.neigh@nasa.gov>
Subject: [EXTERNAL] Request Form Submitted: ID# 1005

Here is the Search Query from druedaro@usf.edu

Request ID: 1005
Request Date: 2021-04-08 

Bounding Box Request
UL Lat Coords: 26.2
UL Lon Coords: -81.8
LR Lat Coords: 25.8
LR Lon Coords: -81.4

Buffer Size:
Study Area: Rookery Bay Estuarine Research Reserve, U.S.

From Date: 2010-01-01
  To Date: 2021-12-31

Sensor Filter Input 
GeoEye:
WorldView1:
WorldView2: Yes
WorldView3: Yes
QuickBird:
OrbView:
IKONOS:

MS and Pan:
 Cloud cover % filter: 90
 
Comments: 8-band/SWIR\r\nImages will be used to asses changes on mangrove coverage over time.\r\nThis area polygon can be downloaded at: \r\nhttps://gcc02.safelinks.protection.outlook.com/?url=http:%2F%2Fimars.usf.edu%2F~digna%2FPolygonRookeryBay%2FAOI_Rookery.txt%2Fr%2Fn&amp;data=04%7C01%7Cwilliam.c.wagner%40nasa.gov%7Cab84b0ba85f045c864a308d8fab41c17%7C7005d45845be48ae8140d43da96dd17b%7C0%7C0%7C637534998756509239%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=c60z6V6XCAL6RclIgqJwS3BQ55Q3y0%2FyCF17Ipckhwg%3D&amp;reserved=0
```

Completed 2021-06-10. 
Downloads started 2021-06-11.

```bash
[root@thing1 wv_cad4nasa_zip]# pwd
/mnt/raid/imars_objects/rookery/wv_cad4nasa_zip
[root@thing1 wv_cad4nasa_zip]# lftp -u user_2o2l https://cad4nasa.gsfc.nasa.gov/restricted_data/Muller-Karger/Req1005/
Password: 
cd ok, cwd=/restricted_data/Muller-Karger/Req1005                                                     
lftp user_2o2l@cad4nasa.gsfc.nasa.gov:/restricted_data/Muller-Karger/Req1005> mirror --use-pget-n=4
```

## 2020-12 Jobos Bay NERR

```
Here is the Search Query from tylarmurray@mail.usf.edu

Request ID: 978
Request Date: 2020-12-04

Bounding Box Request
UL Lat Coords: 17.99
UL Lon Coords: -66.41
LR Lat Coords: 17.9
LR Lon Coords: -66.14

Buffer Size:
Study Area: JBNERR

From Date: 2010-01-01
  To Date: 2020-12-04

Sensor Filter Input
GeoEye:
WorldView1:
WorldView2: Yes
WorldView3: Yes
QuickBird:
OrbView:
IKONOS:
```

Images were ingested into `/srv/imars-objects/rookery` (oops!) 2021-02.

```bash
lftp -u user_2o2l https://cad4nasa.gsfc.nasa.gov/restricted_data/Turner/Req978/
```
