Habitat coverage class ground truth data collection was originally led by Matt McCarthy & Mike Barry.
This data contains habitat information collected by an expert (Mike Barry) on the ground.
The data was used to assess the accuracy of land-cover classification methods by Matt.

Data has been collected for Matt's dissertation, the 3d Wetlands project, NERRS-funded research, and via Mike Barry's voluneer time.

The data can be downloaded from [this google drive folder](https://drive.google.com/drive/folders/1OZzDyr8FKzsX-zPFRD2Hn3iFMXoxiDGK?usp=sharing).

This data should not be used for any purpose without permission from USF IMaRS.

# data location(s)

* `/home1/mmccarthy/Matt/USF/Other/CHIMMP/GroundTruth/` : ground truth archive recommended by Matt 2021-08 (data is from 2017-02 at latest)
    * Fort DeSoto coverage reported to be in
        * `TB_GroundTruthv2_basin` 
        * `TB_gtv2_Wetlandnomarsh_FWRI_RS`
        * `TB_gtv2_Upland_FWRI_RS`
* `/home1/tylar/landcover-analysis/data/` : data provided by Matt to Tylar in 2019-03 for the 3d wetlands project
* `/home1/tylar/habitat-ground-truth/` : data emailed to Tylar from Mike Barry mid 2021

## full files listing 2021-08-03

```
[root@seashell ~]# ls /home1/mmccarthy/Matt/USF/Other/CHIMMP/GroundTruth/
AccAssess                          TB_GroundTruthv2_basin.sbx
Liza_GRP_WGS84.dbf                 TB_GroundTruthv2_basin.shp
Liza_GRP_WGS84.prj                 TB_GroundTruthv2_basin.shx
Liza_GRP_WGS84.sbn                 TB_GroundTruthv2_basin_SwampMangrove.dbf
Liza_GRP_WGS84.sbx                 TB_GroundTruthv2_basin_SwampMangrove.prj
Liza_GRP_WGS84.shp                 TB_GroundTruthv2_basin_SwampMangrove.sbn
Liza_GRP_WGS84.shp.xml             TB_GroundTruthv2_basin_SwampMangrove.sbx
Liza_GRP_WGS84.shx                 TB_GroundTruthv2_basin_SwampMangrove.shp
Liza_GRP_WGS84_TB_Builtup.dbf      TB_GroundTruthv2_basin_SwampMangrove.shx
Liza_GRP_WGS84_TB_Builtup.prj      TB_GroundTruthv2_basin_Upland.dbf
Liza_GRP_WGS84_TB_Builtup.sbn      TB_GroundTruthv2_basin_Upland.prj
Liza_GRP_WGS84_TB_Builtup.sbx      TB_GroundTruthv2_basin_Upland.sbn
Liza_GRP_WGS84_TB_Builtup.shp      TB_GroundTruthv2_basin_Upland.sbx
Liza_GRP_WGS84_TB_Builtup.shp.xml  TB_GroundTruthv2_basin_Upland.shp
Liza_GRP_WGS84_TB_Builtup.shx      TB_GroundTruthv2_basin_Upland.shx
Liza_GRP_WGS84_TB.dbf              TB_GroundTruthv2.dbf
Liza_GRP_WGS84_TB.prj              TB_GroundTruthv2.prj
Liza_GRP_WGS84_TB.sbn              TB_GroundTruthv2.sbn
Liza_GRP_WGS84_TB.sbx              TB_GroundTruthv2.sbx
Liza_GRP_WGS84_TB.shp              TB_GroundTruthv2.shp
Liza_GRP_WGS84_TB.shp.xml          TB_GroundTruthv2.shx
Liza_GRP_WGS84_TB.shx              TB_gtv2_Upland_FWRI_RS.dbf
schema.ini                         TB_gtv2_Upland_FWRI_RS.prj
TampaBayGroundTruthing2.csv        TB_gtv2_Upland_FWRI_RS.sbn
TampaBayGroundTruthing_v2.csv      TB_gtv2_Upland_FWRI_RS.sbx
TampaBayGroundTruthing_v2.xlsx     TB_gtv2_Upland_FWRI_RS.shp
TampaBayGroundTruthing.xlsx        TB_gtv2_Upland_FWRI_RS.shp.xml
TB_GroundTruth.dbf                 TB_gtv2_Upland_FWRI_RS.shx
TB_GroundTruth.prj                 TB_gtv2_Wetland_FWRI_RS.dbf
TB_GroundTruth.sbn                 TB_gtv2_Wetland_FWRI_RS.prj
TB_GroundTruth.sbx                 TB_gtv2_Wetland_FWRI_RS.sbn
TB_GroundTruth.shp                 TB_gtv2_Wetland_FWRI_RS.sbx
TB_GroundTruth.shx                 TB_gtv2_Wetland_FWRI_RS.shp
TB_GroundTruthv2_basin.dbf         TB_gtv2_Wetland_FWRI_RS.shp.xml
TB_GroundTruthv2_basin_Marsh.dbf   TB_gtv2_Wetland_FWRI_RS.shx
TB_GroundTruthv2_basin_Marsh.prj   TB_gtv2_Wetlandnomarsh_FWRI_RS.dbf
TB_GroundTruthv2_basin_Marsh.sbn   TB_gtv2_Wetlandnomarsh_FWRI_RS.prj
TB_GroundTruthv2_basin_Marsh.sbx   TB_gtv2_Wetlandnomarsh_FWRI_RS.sbn
TB_GroundTruthv2_basin_Marsh.shp   TB_gtv2_Wetlandnomarsh_FWRI_RS.sbx
TB_GroundTruthv2_basin_Marsh.shx   TB_gtv2_Wetlandnomarsh_FWRI_RS.shp
TB_GroundTruthv2_basin.prj         TB_gtv2_Wetlandnomarsh_FWRI_RS.shp.xml
TB_GroundTruthv2_basin.sbn         TB_gtv2_Wetlandnomarsh_FWRI_RS.shx

[tylar@seashell ~]$ ls /home1/tylar/landcover-analysis/data/
GTPs_touse_points_Developed_test.cpg        GTPs_touse_points_Mud_test.shx
GTPs_touse_points_Developed_test_.dbf       GTPs_touse_points_Mud_train.cpg
GTPs_touse_points_Developed_test.dbf        GTPs_touse_points_Mud_train_.dbf
GTPs_touse_points_Developed_test.ebb        GTPs_touse_points_Mud_train.dbf
GTPs_touse_points_Developed_test.ed1        GTPs_touse_points_Mud_train_.evf
GTPs_touse_points_Developed_test.eq1        GTPs_touse_points_Mud_train_.evf.qtr
GTPs_touse_points_Developed_test_.evf       GTPs_touse_points_Mud_train.prj
GTPs_touse_points_Developed_test.prj        GTPs_touse_points_Mud_train.sbn
GTPs_touse_points_Developed_test.sbn        GTPs_touse_points_Mud_train.sbx
GTPs_touse_points_Developed_test.sbx        GTPs_touse_points_Mud_train.shp
GTPs_touse_points_Developed_test.shp        GTPs_touse_points_Mud_train.shp.xml
GTPs_touse_points_Developed_test.shp.qtr    GTPs_touse_points_Mud_train.shx
GTPs_touse_points_Developed_test.shp.xml    GTPs_touse_points_Sand_test.cpg
GTPs_touse_points_Developed_test.shx        GTPs_touse_points_Sand_test.dbf
GTPs_touse_points_Developed_train.cpg       GTPs_touse_points_Sand_test.ebb
GTPs_touse_points_Developed_train_.dbf      GTPs_touse_points_Sand_test.ed1
GTPs_touse_points_Developed_train.dbf       GTPs_touse_points_Sand_test.eq1
GTPs_touse_points_Developed_train_.evf      GTPs_touse_points_Sand_test.prj
GTPs_touse_points_Developed_train_.evf.qtr  GTPs_touse_points_Sand_test.sbn
GTPs_touse_points_Developed_train.prj       GTPs_touse_points_Sand_test.sbx
GTPs_touse_points_Developed_train.sbn       GTPs_touse_points_Sand_test.shp
GTPs_touse_points_Developed_train.sbx       GTPs_touse_points_Sand_test.shp.qtr
GTPs_touse_points_Developed_train.shp       GTPs_touse_points_Sand_test.shp.xml
GTPs_touse_points_Developed_train.shp.xml   GTPs_touse_points_Sand_test.shx
GTPs_touse_points_Developed_train.shx       GTPs_touse_points_Sand_train.cpg
GTPs_touse_points_Mangrove_test.cpg         GTPs_touse_points_Sand_train_.dbf
GTPs_touse_points_Mangrove_test.dbf         GTPs_touse_points_Sand_train.dbf
GTPs_touse_points_Mangrove_test.ebb         GTPs_touse_points_Sand_train_.evf
GTPs_touse_points_Mangrove_test.ed1         GTPs_touse_points_Sand_train_.evf.qtr
GTPs_touse_points_Mangrove_test.eq1         GTPs_touse_points_Sand_train.prj
GTPs_touse_points_Mangrove_test.prj         GTPs_touse_points_Sand_train.sbn
GTPs_touse_points_Mangrove_test.sbn         GTPs_touse_points_Sand_train.sbx
GTPs_touse_points_Mangrove_test.sbx         GTPs_touse_points_Sand_train.shp
GTPs_touse_points_Mangrove_test.shp         GTPs_touse_points_Sand_train.shp.xml
GTPs_touse_points_Mangrove_test.shp.qtr     GTPs_touse_points_Sand_train.shx
GTPs_touse_points_Mangrove_test.shp.xml     GTPs_touse_points_Upland_test.cpg
GTPs_touse_points_Mangrove_test.shx         GTPs_touse_points_Upland_test.dbf
GTPs_touse_points_Mangrove_train.cpg        GTPs_touse_points_Upland_test.ebb
GTPs_touse_points_Mangrove_train_.dbf       GTPs_touse_points_Upland_test.ed1
GTPs_touse_points_Mangrove_train.dbf        GTPs_touse_points_Upland_test.eq1
GTPs_touse_points_Mangrove_train_.evf       GTPs_touse_points_Upland_test.prj
GTPs_touse_points_Mangrove_train_.evf.qtr   GTPs_touse_points_Upland_test.sbn
GTPs_touse_points_Mangrove_train.prj        GTPs_touse_points_Upland_test.sbx
GTPs_touse_points_Mangrove_train.sbn        GTPs_touse_points_Upland_test.shp
GTPs_touse_points_Mangrove_train.sbx        GTPs_touse_points_Upland_test.shp.qtr
GTPs_touse_points_Mangrove_train.shp        GTPs_touse_points_Upland_test.shp.xml
GTPs_touse_points_Mangrove_train.shp.xml    GTPs_touse_points_Upland_test.shx
GTPs_touse_points_Mangrove_train.shx        GTPs_touse_points_Upland_train.cpg
GTPs_touse_points_Marsh_test.cpg            GTPs_touse_points_Upland_train_.dbf
GTPs_touse_points_Marsh_test.dbf            GTPs_touse_points_Upland_train.dbf
GTPs_touse_points_Marsh_test.ebb            GTPs_touse_points_Upland_train_.evf
GTPs_touse_points_Marsh_test.ed1            GTPs_touse_points_Upland_train_.evf.qtr
GTPs_touse_points_Marsh_test.eq1            GTPs_touse_points_Upland_train.prj
GTPs_touse_points_Marsh_test.prj            GTPs_touse_points_Upland_train.sbn
GTPs_touse_points_Marsh_test.sbn            GTPs_touse_points_Upland_train.sbx
GTPs_touse_points_Marsh_test.sbx            GTPs_touse_points_Upland_train.shp
GTPs_touse_points_Marsh_test.shp            GTPs_touse_points_Upland_train.shp.xml
GTPs_touse_points_Marsh_test.shp.qtr        GTPs_touse_points_Upland_train.shx
GTPs_touse_points_Marsh_test.shp.xml        GTPs_touse_points_Water_test.cpg
GTPs_touse_points_Marsh_test.shx            GTPs_touse_points_Water_test.dbf
GTPs_touse_points_Marsh_train.cpg           GTPs_touse_points_Water_test.ebb
GTPs_touse_points_Marsh_train_.dbf          GTPs_touse_points_Water_test.ed1
GTPs_touse_points_Marsh_train.dbf           GTPs_touse_points_Water_test.eq1
GTPs_touse_points_Marsh_train_.evf          GTPs_touse_points_Water_test.prj
GTPs_touse_points_Marsh_train_.evf.qtr      GTPs_touse_points_Water_test.sbn
GTPs_touse_points_Marsh_train.prj           GTPs_touse_points_Water_test.sbx
GTPs_touse_points_Marsh_train.sbn           GTPs_touse_points_Water_test.shp
GTPs_touse_points_Marsh_train.sbx           GTPs_touse_points_Water_test.shp.qtr
GTPs_touse_points_Marsh_train.shp           GTPs_touse_points_Water_test.shp.xml
GTPs_touse_points_Marsh_train.shp.xml       GTPs_touse_points_Water_test.shx
GTPs_touse_points_Marsh_train.shx           GTPs_touse_points_Water_test.zip
GTPs_touse_points_Mud_test.cpg              GTPs_touse_points_Water_train.cpg
GTPs_touse_points_Mud_test.dbf              GTPs_touse_points_Water_train_.dbf
GTPs_touse_points_Mud_test.ebb              GTPs_touse_points_Water_train.dbf
GTPs_touse_points_Mud_test.ed1              GTPs_touse_points_Water_train_.evf
GTPs_touse_points_Mud_test.eq1              GTPs_touse_points_Water_train_.evf.qtr
GTPs_touse_points_Mud_test.prj              GTPs_touse_points_Water_train.prj
GTPs_touse_points_Mud_test.sbn              GTPs_touse_points_Water_train.sbn
GTPs_touse_points_Mud_test.sbx              GTPs_touse_points_Water_train.sbx
GTPs_touse_points_Mud_test.shp              GTPs_touse_points_Water_train.shp
GTPs_touse_points_Mud_test.shp.qtr          GTPs_touse_points_Water_train.shp.xml
GTPs_touse_points_Mud_test.shp.xml          GTPs_touse_points_Water_train.shx

[tylar@seashell ~]$ ls /home1/tylar/habitat-ground-truth/
IRC_Master_GDB.zip  JBNERR_Groundtruthing.mdb  Picayune_temp_fielddata_GDB.zip
```
