## how to access images from windows?
    - `\\lab_share\datashare\regions\{region_name}\{product_name}`
## where to put images on the server?
    - `/srv/imars-objects/{region_name}/{product_name}`

* `region_name`s:
    - see [github/USF-IMARS/data-docs](https://github.com/USF-IMARS/data-docs/blob/master/docs/worldview/regions_worldview.md)
    
* `product_name`s:
    - `soalchi_r_rs_wv2`  (Rrs)
    - `soalchi_tif_rrs_wv2`
    - `soalchi_tif_classification`

## licensing
These images **cannot** be publicly shared. Please read the NextView license at [data-docs/worldview/NextView_License.pdf](https://github.com/USF-IMARS/data-docs/blob/master/docs/worldview/NextView_License_Information_Paper_20170503.pdf) for details.

## ingest
Worldview files have been ingested from Digital Globe, the Polar Geospatial center, and the CAD4NASA program.
Images are broken out into regions within imars-objects.
An overview of these areas for the Gulf of Mexico is given in regions_worldview.md.

## specific locations
Worldview files are split by satellite: WV02 and WV03.
Imagery can be found in multiple places:
* `{region}/zip_wv2_ftp_ingest` - imagery "bundles" with shape, xml, and ntf files.
* `{region}/ntf_wv2_m1bs` - ntf data files managed by imars-etl
* `{region}/tif_rrs_wv2` - data files with atmosphere removed
* `{region}/tif_r_rs_wv2` - data files with atmosphere and water removed (Rrs)
* `{region}/tif_classification` - land cover class images
* `{region}/worldview` - images ingested from the PGC. Not split up by file product type.
* `cozumel:/cozumel/imars-objects/complete` - images from Digital Globe not yet ingested
* `cozumel:/cozumel/imars-objects/PGC_Imagery_2019jan18` - images from PGC not yet ingested
* `cozumel:/cozumel/imars-objects/circe_ingest` and `cozumel:/cozumel/imars-objects/circe_output` - image classification files from Matt not yet ingested
* `corals:/srv/imars-objects/corals/WV2/` - images of Egypt not ingested
* `thing1:/mnt/raid/imars_objects/fiji` - images of Fiji not ingested
* `/srv/imars-objects/extra_data/WV02/` and `/srv/imars-objects/extra_data/WV03/` older data; I don't know what region(s) are covered.

## Shapefiles
Alongside the xml and ntf files you should find some shapefiles (.shp, .prj, .shx, .dbf). 
These files are sometimes bundled inside a .tar file.
Inside the tar file directory like `DG_ftp000751/502512222030_01/GIS_FILES` you will find:
   * PIXEL_SHAPE
   * ORDER_SHAPE
   * PRODUCT_SHAPE
   * STRIP_SHAPE
   * TILE_SHAPE
   
The ones we care about are the `PIXEL_SHAPE` files.
These files define the shape of the .ntf file contents.
The other files are larger areas surrounding the .ntf area.
