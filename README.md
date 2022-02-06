
# Tunisia Shapefiles

**About:** The shapefiles in this repository were modified or created as part of a research project to map changes in municipal boundaries in Tunisia. They were constructed based on Open Street Map (OSM) and publicly available administrative data, and therefore should be considered as approximations, to be superseded by the publication of official shapefiles. I hope these materials are helpful to other researchers; please contact me with any questions or to report any errors.

**Access:** This dataset is made available under the Open Database License (ODbL 1.0): http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/published.

**Suggested citation:** Clark, Julia. 2021. "Mapping Municipal Change in Tunisia." American Political Science Association MENA Symposium, Spring 2021 Newsletter.

## Description of data

The `edited_shapefiles` folder contains ESRI-formatted files (*.shp*, *.cpg*, *.dbf*, *.prj*, *.shx*) for the following administrative and political levels:

 - All of Tunisia: *TN_tunisia.shp*
 - Regions: *TN_regions.shp*
 - Governorates: *TN_governorates.shp*
 - Electoral districts: *TN_districts.shp*
 - Delegations: *TN_delegations_2014.shp* (c. 2014) *TN_delegations_2018.shp* (c. 2018)
 - Municipalities: *TN_municipalities_2014.shp* (c. 2014) and *TN_municipalities_2018.shp* (c. 2018)
 - Sectors: *TN_sectors.shp*

All files use the WGS84 coordinate system, and include some or all of the following standardized fields depending on their level:

 - reg: Abbreviation of geographic region (CE, CW, NE, NW, SE, SW)
 - reg_ar: Region name in Arabic
 - reg_en: Region name in English
 - gov_id: Governorate identifier (used by official sources)
 - gov_ar: Governorate name in Arabic
 - gov_en: Governorate name in English
 - dis_id: Electoral district identifier (used by official sources)
 - dis_ar: District name in Arabic
 - dis_en: Governorate name in English
 - del_id_2014: 2014 Delegation identifier (used by official sources)
 - del_ar_2014: 2014 Delegation name in Arabic
 - del_en_2014: 2014 Delegation name in English
 - del_id_2018: 2018 Delegation identifier (used by official sources)
 - del_ar_2018: 2018 Delegation name in Arabic
 - del_en_2018: 2018 Delegation name in English
 - mun_uid: Municipality unique identifier (created to standardize with other datasets before the release of new official numbers for the newly created 2018 municipalities)
 - mun_id_2014: 2014 Municipality identifier (used by official sources)
 - mun_ar_2014: 2014 Municipality name in Arabic
 - mun_en_2014: 2018 Municipality name in English
 - mun_ar_2018: 2018 Municipality name in Arabic
 - mun_en_2018: 2018 Municipality name in English
 - sec_uid: Sector unique identifier (created to standardize with other datasets)
 - sec_ar: Sector name in Arabic
 - sec_en: Sector name in English
 - osm_id: ID in OSM data
 - km2: Calculated area of shape
 - cent_long: Calculated longitude of shape's centroid
 - cent_lat: Calculated latitude of shape's centroid

## Sources

These shapefiles rely on the following data sources:

 - Shapefiles from the OSM/Citizen Mapping project
 - 2016 reports from the Ministry of Local Affairs (MAL) that have PDF maps of new municipalities and their sectors
 - 2014 census data from INS that provides communal (i.e., municipal) population by sector
 - 2018 municipal election results from ISIE are used to update sector/municipal mapping from the 2016 MAL report

Specific details on shapefile edits and coding choices can be found in `coding_notes.md`.

## Methodology

For detailed methodology, see Clark, Julia. 2021. "Mapping Municipal Change in Tunisia." American Political Science Association MENA Symposium, Spring 2021 Newsletter.
