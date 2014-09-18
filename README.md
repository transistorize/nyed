nyed
====

NY State Election District Maps


This is a project to coalesce all the public geographic data about election districts and other infrequently used administrative designations. Many parties offer geographic data on congressional districts at the federal and sometimes the state level, but election districts are harder to come by.

All Shape and Geojson format files are converted to [Topojson](https://github.com/mbostock/topojson/wiki) to keep the file sizes down. Compressed Geojson files are ok, but I believe are not natively [displayed](https://github.com/blog/1541-geojson-rendering-improvements) within Github. All data files should have a source file listed, so that one can confirm the origin of the data and the process of transformation.


If you use this data to make visualizations, let me know and I will list it below.

----

Other sources of data to clean up or use directly:

1. [SAGE](http://pubgeo.nysenate.gov/docs/html/index.html) and the [NY Senate Geo API][https://github.com/nysenate/GeoApi]
2. [Voter Information Google API](https://votinginfoproject.org/projects/view/google_api)
3. [Albany Board of Election](http://acvcloud.albanycounty.com/acviz/boe_ac.html) - the [backing data](https://www.google.com/fusiontables/DataSource?docid=1b5wJ8qSqWC-RiKtVRy6AHKdE-1aneq-WOAxgEHg) could be cleaned up and coverted to Topojson. The data may be out of date, according their site. 
4. [NYC OpenData](https://data.cityofnewyork.us/City-Government/Election-Districts/h2n3-98hq) - many other sources available for NYC area, but I could not find the election districts for the whole state.
5. [NY Board of Elections](http://www.elections.ny.gov/index.html) and the [2014 Enrollment Statistics](http://www.elections.ny.gov/2014EnrollmentED.html). I've written a hand-cobbled scraper for these statistics that I will publish soon.
6. [MapZen](https://mapzen.com/data) - See all the data sources and their [announcement](https://mapzen.com/blog/cfa-announcement) of funding.
7. [Wikipedia](http://en.wikipedia.org/wiki/List_of_counties_in_New_York) - list of counties
8. [Mapping the Nation](http://mappingthenation.net/about.html)
9. [National Historic Geographic Information System](http://nhgis.org)
