# Query RACMO cell value given a coordinate / Bounding box / shapefile 


More information on ```https://www.projects.science.uu.nl/iceclimate/models/racmo.php```


## Requirement

python>3.4<br>
xarray<br>
cartopy<br>
matplotlib<br>
numpy<br>
pandas<br>
regionmask<br>

## Usage
To use **Volume_RACMO_Pt_Query**<br> Input a coordinate <br>
Change 
```aoi_lon```
```aoi_lat```

If your shapefile is smaller than one grid cell, (approximately 27km * 27km) use **Volume_RACMO_Pt_Query** instead. 

To use **Volume_RACMO_Bbox_Query**<br>
Input a Bounding box to ```aoi_shp```as a shapefile. *WAIS_bbox.shp* was used for demo.<br>

To use **Volume_RACMO_Shp_Query**<br>
Input a shapefile to ```aoi_shp```. *Amery_test_tri.shp* was used for demo. 
