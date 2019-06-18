# data-docs
Public documentation about IMaRS data.

Documents in the `./docs` directory here are in markdown format and provide information about how data is organized at IMaRS.

If you have a question about IMaRS data or want to make your data more available please open an issue in [this repo's github issue tracker](https://github.com/USF-IMARS/data-docs/issues).

## Special Access for IMaRS Researchers
IMaRS researchers can access data in the `\\yin\lab_share\datashare\` folder from windows or `/srv/imars-objects/homes/datashare` on linux.
These directories are managed with puppet by [`profile::imars_datashare_homelinks`](https://github.com/USF-IMARS/imars_puppet/blob/test/modules/profile/manifests/imars_datashare_homelinks.pp).

A basic overview of the directories there:

* `regions` : datasets bounded by a "region". Regions are defined on a per-project basis. For more information consult the imars_product_metadata database managed with puppet by [`role::product_metadata_rows.sql`](https://github.com/USF-IMARS/imars_puppet/blob/test/modules/role/files/sql/product_metadata_rows.sql)
* `mirrored` : datasets copied directly from another source
* `legacy` : older datasets not comforming to current organizational standards
* `ingests` : staging locations for incoming data
* `custom` : other datasets not fitting any of the above
