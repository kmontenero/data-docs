AVHRR data was collected via direct broadcast using the L-band satellite dish under the care of Doug Myhre.
This system processed the images into hdf SST files manually "navigated" with ground control points.
The data collection became worse over time and in late 2019 collection was halted.

Raw files can be found in `/srv/imars-objects/fullpass/hdf_avhrr_usf_sst/`
Until 2017 the L0 files were processed by a perl-based orchestration system running on modis, cylops, and dods into png images.
The resulting full-pass png images can be found in `/srv/imars-objects/fullpass`.

