For the files ny*.14c.topojson files that focus on New York City, the source is the 14c release from the [BYTES of the BIG APPLE](http://www.nyc.gov/html/dcp/html/bytes/districts_download_metadata.shtml) (tm). The Shapefiles were converted to Geojson first, using the GDAL ogr2ogr [commandline tool](http://ben.balter.com/2013/06/26/how-to-convert-shapefiles-to-geojson-for-use-on-github/), and then these files in turn were converted to Topojson using that project's [commandline tool](https://github.com/mbostock/topojson/wiki/Command-Line-Reference). For some reason, trying to convert the Shapefile directly to Topojson did not work. 


If converting the other 14c release files are of interest, please submit an issue or pull request.
