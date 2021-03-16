Digital Elevation Model (DEM) files were produced as part of the 3d wetlands project.

There are no same name tiles for all 5 states (TX, LA, MS, LA, and FL).

# Filename Conventions
The filename likes this, utm17ovrlap_290292_3312264.tif.
It means utm 17 zone, and its upper-left corner is at (290292m, 3312264m) of utm17 zone.

Each final DEM tile (40km by 40km) has the two types of files:
* `utm17ovrcount_*.tif` is for number of lidar dataset at a pixel
* `utm17ovrlap_*.tif` is for elevation fused from these datasets at the pixel.

For example, `utm17ovrcount_290292_3312264.tif` and `utm17ovrlap_290292_3312264.tif` are for same tile that its upper-left corner is at (290292m, 3312264m) of utm17 zone.

Each tile has 20000 by 20000 pixels. It means 40km by 40km for 2m pixel.

# Organization of files
## Harte
James's lab at Harte organize the bare-earth surface 2m DEM files as follows:

In total, we have 7 folders.
```
utm16n17_fl/
    utm16_ovrlp_be/
    utm17_ovrlp_be/
utm16_ms_al/
    ovrlp_be/
utm15n16_la/ 
    utm15_ovrlp_be/
    utm16_ovrlp_be/
utm14n15_tx2020/ 
    tx2020_utm14_ovrlp_be/
    tx2020_utm15_ovrlp_be/
```
 
## IMaRS box.com files 
Files from Harte's directory structure were uploaded into a single box.com folder. 
filenames | corresponding Harte directory
----------------- | ------------
`utm14ovrlap_*.tif` | utm14n15_tx2020 -- tx2020_utm14_ovrlp_be.
`utm15ovrlap_*.tif` | utm14n15_tx2020 -- tx2020_utm15_ovrlp_be.
`utm16ovrlap_*.tif` | utm16n17_fl     -- utm16_ovrlp_be.
`utm17ovrlap_*.tif` | utm16n17_fl     -- utm17_ovrlp_be.
```
