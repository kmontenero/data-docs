```
[root@thing1 rookery]# unzip wv_cad4nasa_zip/WV220150715150031P00.zip -d wv_cad4nasa_unzipped/
[...]
[root@thing1 rookery]# tree wv_cad4nasa_unzipped/
wv_cad4nasa_unzipped/15AUG22145912-M1BS-500395862010_01_P030
├── 15AUG22145912-M1BS-500395862010_01_P030.ATT
├── 15AUG22145912-M1BS-500395862010_01_P030-BROWSE.JPG
├── 15AUG22145912-M1BS-500395862010_01_P030.EPH
├── 15AUG22145912-M1BS-500395862010_01_P030.GEO
├── 15AUG22145912-M1BS-500395862010_01_P030.IMD
├── 15AUG22145912-M1BS-500395862010_01_P030.NTF
├── 15AUG22145912-M1BS-500395862010_01_P030_README.TXT
├── 15AUG22145912-M1BS-500395862010_01_P030.RPB
├── 15AUG22145912-M1BS-500395862010_01_P030.TIL
├── 15AUG22145912-M1BS-500395862010_01_P030.XML
└── NEXTVIEW.TXT
```

`NEXTVIEW.TXT` is the NextView License.


### Ingest Steps

```
[root@thing1 rookery]# find unzip wv_cad4nasa_zip/ -name *.zip -exec unzip -n {} -d wv_cad4nasa_unzipped/ \;
# permissions
[root@thing1 rookery]# find wv_cad4nasa_unzipped/ -type d -exec chmod 750 {} \;
[root@thing1 rookery]# find wv_cad4nasa_unzipped/ -type f -exec chmod 640 {} \;
[root@thing1 rookery]# chown -R 29898:imars-common wv_cad4nasa_unzipped
# mv files we want to separate dir
[root@thing1 rookery]# find wv_cad4nasa_unzipped/ -name *-M1BS-* -name *.NTF -exec cp {} wv_all_m1bs_ntf_xml_only/. \;
[root@thing1 rookery]# find wv_cad4nasa_unzipped/ -name *-M1BS-* -name *.XML -exec cp {} wv_all_m1bs_ntf_xml_only/. \; 
```
