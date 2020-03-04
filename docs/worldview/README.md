Worldview files are ingested from Digital Globe and the Polar Geospatial center.
Images are broken out into regions within imars-objects.
An overview of these areas for the Gulf of Mexico is given in regions_worldview.md.

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
