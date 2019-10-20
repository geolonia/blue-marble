# Blue Marble

Blue Marble is a global topography and bathmetry provided by NASA.

Image origin: https://neo.sci.gsfc.nasa.gov/view.php?datasetId=BlueMarbleNG-TB

## Public Tile URL

https://geolonia.github.io/blue-marble/tiles/{z}/{x}/{y}.png

## Build

```shell
$ python3 /usr/local/bin/gdal2tiles.py \
  --s_srs EPSG:4326 \
  --zoom 0-3 \
  BlueMarbleNG-TB_2004-12-01_rgb_3600x1800.TIFF \
  ./tiles
```
