# Blue Marble

Image origin: https://neo.sci.gsfc.nasa.gov/view.php?datasetId=BlueMarbleNG-TB

## Build

```shell
$ python3 /usr/local/bin/gdal2tiles.py --s_srs EPSG:4326 --zoom 0-5 BlueMarbleNG-TB_2004-12-01_rgb_3600x1800.TIFF ./tiles
```
